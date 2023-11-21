# Chapter 1 Problems

1-1. [3] Show that a+b can be less than min(a,b).

Let a = -1, b = -2.
-1 + -2 < min(-1, -2)
-3 < -2

1-2. [3] Show that a x b can be less than min(a,b).

Let a = -2, b = 2.
-2 x 2 < min(-2, 2)
-4 < -2

1-3. [5] Design/draw a road network with two points a and b such that
the fastest route between a and b is not the shortest route.

```
a - b
|   |
c - d
```

where the distance between a and b is 30 miles at 10 mph,
a and c is 20 miles at 20 mph and c to d is 20 miles at 20 mph.

1-4. [5] Design/draw a road network with two points a and b such that 
the shortest route between a and b is not the route with the fewest
turns.

```
a ----- c
 \      |
  d - e |
       \
	    b
```

1-5. [4] The knapsack problem is as follows: given a set of integers
S = {s1,s2,...,sn}, and a target number T, find a subset of S that 
adds up exactly to T. For example, there exists a subset within
S = {1,2,5,9,10} that adds up to T = 22 but not T = 23.

Find counterexamples to each of the following algorithms for the 
knapsack problem. That is, give an S and T where the algorithm does
not find a solution that leaves the knapsack completely full, even
though a full-knapsack solution exists.

(a) Put the elements of S in the knapsack in left to right order if 
they fit, that is, the first-fit algorithm.

(b) Put the elements of S in the knapsack from the smallest to 
largest, that is, the best-fit algorithm.

(c) Put the elements of S in the knapsack from largest to smallest.
