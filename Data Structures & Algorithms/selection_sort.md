#Insertion Sort 
[22,27,16,2,18,6] n
[22,27`*`,16,2,18,6] n-1
[22,27,16`*`,2,18,6] n-2
[16,22,27,2`*`,18,6] n-3
[2,16,22,27,18`*`,6] n-4
[2,16,18,22,27,6`*`] n-5
[2,6,16,18,22,27] 1

**1-First Step:** The first element, 22, is already considered "sorted", so no operations are performed on it.

**2-Second Step:** We consider 27. Since 27 is greater than 22, it remains in its position.

Array: [22,27,16,2,18,6]

**3-Third Step:** We consider 16. It's less than 27, so we move 16 to the left of 27. Furthermore, since 16 is also less than 22, we move it to the left of 22 as well.

Array: [16,22,27,2,18,6]

**4-Fourth Step:** Next, we consider 2. Since 2 is less than all sorted elements (16, 22, and 27), we move it to the very front.

Array: [2,16,22,27,18,6]

**5-Fifth Step:** We then consider 18. 18 is less than 27 but greater than 16, so we place it between 16 and 22.

Array: [2,16,18,22,27,6]

**6-Sixth Step:** Finally, we consider 6. 6 is greater than 2 but less than 16, so we place it between 2 and 16.

**Final Array:** [2,6,16,18,22,27]

In conclusion, the array [22,27,16,2,18,6] has been sorted to [2,6,16,18,22,27] using the Insertion Sort algorithm.

---
###Time Complexity:

- Best Case: O (n)
- Average Case: O (n²)
- Worst Case: O (n²)

#####Big-O notation: O (n²)
n+(n-1)+(n-2)+(n-3)+(n-4)+1= (n(n+1))/2= n²

After the array is sorted, under which of the following cases would the number 18 fall?

**18 is considered an average case.**

---
##Selection Sort Example Array:
[7,3,5,8,2,9,4,15,6]

**The first four steps of the Selection Sort**

[7,3,5,8,2,9,4,15,6] n
[2,3,5,8,7,9,4,15,6] n-1
[2,3,5,8,7,9,4,15,6] n-2 (No change since 3 is already in the right position.)
[2,3,4,8,7,9,5,15,6] n-3