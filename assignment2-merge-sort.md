# Merge Sort Project

## Question
Write the steps of the Merge Sort algorithm for the array
[16,21,11,8,12,22].
Also write the Big-O notation.

## Answer

Merge Sort Steps

Divide Phase
[16,21,11,8,12,22]
→ [16,21,11] | [8,12,22]
→ [16] [21,11] | [8] [12,22]
→ [16] [21] [11] | [8] [12] [22]

Merge Phase
[21] + [11] → [11,21]
[12] + [22] → [12,22]

[16] + [11,21] → [11,16,21]
[8] + [12,22] → [8,12,22]

[11,16,21] + [8,12,22]
→ [8,11,12,16,21,22]

Big-O Notation
O(n log n)
