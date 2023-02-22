## Day 0:
Today, I made the following progress.
- Installed and Tested Java Compiler on my Machine
- Played around a little bit with Java to refresh my syntax memory.
- Learnt about basic Time Complexity in Algorithms

# Algorithm Analysis
- Algo analysis can happen either based on time complexity or space complexity.
- Frequency Count Method
- [Learn More Here](https://www.youtube.com/watch?v=xGYsEqe9Vl0&list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O&index=4)
- A Problem can be solved in multiple ways out of which we need to do the solutions in the most effective way
- **Ex**: Sum of n natural numbers can be done as 
```
sum = n*(n+1)/2
```
 or 
```
for i = 1 to n{
    sum = sum + i
}
```
or
```
for i = 1 to n{
    for j= 1 to i{
        sum++;
    }
}
```
- O(1) < O(logn) < O(n^1/2) < O(n) < O(nlogn) < O(n^2) < O(n^3)......< O(2^n) < O(3^n).....