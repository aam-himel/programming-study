# Set STL

## What is set?

1. Set is an Associative Container that contains a sorted set of unique objects of same type

2. It is usually implemented using Red-Block Tree.

3. Insertion, Removal, Search have logirathmic complexity.

4. If we want to store user defined data type in set then we will have to provide compare funtion so that set can store them in sorted order.

5. We can pass the order of sorting while constructiong set object.

```cpp
//Syntax
set<Type> Object;
//Example
set<int> obj = {1, 2, 3, 4};
```
