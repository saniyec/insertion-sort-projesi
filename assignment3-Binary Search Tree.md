Binary Search Tree
Project 3

Array:
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Question:
Write the Binary Search Tree (BST) construction steps for the array above.

Answer:

1) The root is 7.

2) 5 is smaller than 7, so it is inserted to the left of the root.

3) 1 is smaller than 7 → go left,
   smaller than 5 → go left,
   so it is inserted to the left of 5.

4) 8 is greater than 7, so it is inserted to the right of the root.

5) 3 is smaller than 7 → go left,
   smaller than 5 → go left,
   greater than 1 → go right,
   so it is inserted to the right of 1.

6) 6 is smaller than 7 → go left,
   greater than 5 → go right,
   so it is inserted to the right of 5.

7) 0 is smaller than 7 → go left,
   smaller than 5 → go left,
   smaller than 1 → go left,
   so it is inserted to the left of 1.

8) 9 is greater than 7 → go right,
   greater than 8 → go right,
   so it is inserted to the right of 8.

9) 4 is smaller than 7 → go left,
   smaller than 5 → go left,
   greater than 1 → go right,
   greater than 3 → go right,
   so it is inserted to the right of 3.

10) 2 is smaller than 7 → go left,
    smaller than 5 → go left,
    greater than 1 → go right,
    smaller than 3 → go left,
    so it is inserted to the left of 3.
