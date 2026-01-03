* Given an array of integers, find the largest integer.

1. **Brute Force**: ***Ascending Sort Array and Return Last Index***.




2. **Better**: **Standard Linear Scan**

```C++
// first pass
int largest = array[0];
for (int i = 1; i < n; i++){
    if (array[i] > largest) {largest = array[i];}
}

// second pass
slargest = -1
for (int i = 0; i < n; i++>){
    if (array[i] > slargest) && (array[i] != largest) {slargest = array[i]}
}

```

3. **Optimal**: ****

```C++

int largest = array[0];
slargest = -1 
for (int i = 1; i < n; i++){
    if (array[i] > largest) {
        slargest = largest;
        largest = array[i];
    }
}
```