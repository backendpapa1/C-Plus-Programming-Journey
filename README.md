# C++ Programming Journey

## Arrays

Learnt arrays is a compound datatype that are fixed size, which means we cannot add or reduce the amount of element in it. There are several ways to initialize an array


### Charasteristics of an array

- Fixed size
- No out of range checker


```c++
  int arr [5]; // This sets the size of the array to 5, 5 element spaces are generated and each contains garbage values.
  int arr [5] {}; // this sets all 5 element space to 0, no garbage at all
  int arr [5] {1,2,3,4,5}; 
  int arr [] {1,2,3,4,5};
```


In accessing this arrays, we can use their indexes or position in the array which always starts at 0

```c++
std::cout<< arr[2] << std::endl;
// result: 3

```

We can pass into it values from the terminal

```c++
  std::cin >> arr[2] >> std::endl;
```
