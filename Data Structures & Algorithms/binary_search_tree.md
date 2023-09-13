# Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

**The first element, 7, becomes the root of the tree.**

* 5 is less than 7, so it goes to the left of 7.
* 1 is less than 5, so it goes to the left of 5.
* 8 is greater than 7, so it goes to the right of 7.
* 3 is less than 5 but greater than 1, so it goes to the right of 1.
* 6 is less than 7 but greater than 5, so it goes to the right of 5.
* 0 is less than 1, so it goes to the left of 1.
* 9 is greater than 8, so it goes to the right of 8.
* 4 is less than 5 but greater than 3, so it goes to the right of 3.
* 2 is less than 3 but greater than 1, so it goes to the left of 3 and to the right of 1.

```

              7
            /   \
           5     8
         /  \     \
        1    6     9
      /  \
     0    3
        /   \
       2     4

```