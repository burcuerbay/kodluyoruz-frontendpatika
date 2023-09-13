# Merge Sort
```
        [16,21,11,8,12,22]  n
          /             \
    [16,21,11]      [8,12,22]  n/2
     /    |          |    \
   [16] [21,11]     [8] [12,22]
    |   |    |       |   |   |
  [16] [21] [11]    [8] [12] [22]
    \      |         |      /
    [16] [11,21]    [8] [12,22]
        \                /
     [11,16,21]      [8,12,22]
            \         /
         [8,11,12,16,21,22]

```
**1-Divide Step**

First, let's split the array into two halves:
[16,21,11] and [8,12,22]

**2-Split each of these halves further:**

[16],[21,11] and [8],[12,22]

- Split the [21,11] array into: [21] and [11].
- Split the [12,22] array into: [12] and [22].

**3-Merge Step**

Now, merge these partitions in a sorted manner:

- Merging [21] and [11] gives: [11,21]
- Merging [12] and [22] gives: [12,22]

Next, merge [16] with the [11,21] array:
[11,16,21]

And merge [8] with the [12,22] array:
[8,12,22]

**Finally, merge the arrays [11,16,21] and [8,12,22]:**

**[8,11,12,16,21,22]**

So, the sorted array for [16,21,11,8,12,22] using Merge Sort is [8,11,12,16,21,22].

---

## Big-O notation: O (nlogn)

- n: Represents the number of elements in the array.

- logn: Represents the number of division steps.

```
2^x = n 
x = logn
```