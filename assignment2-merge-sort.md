Merge Sort
Proje 2

[16,21,11,8,12,22] -> Merge Sort

Soru:
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Cevap:

Merge Sort Aşamaları

Bölme (Divide):
[16,21,11,8,12,22]
→ [16,21,11] | [8,12,22]
→ [16] [21,11] | [8] [12,22]
→ [16] [21] [11] | [8] [12] [22]

Birleştirme (Merge):
[21] ve [11] → [11,21]
[12] ve [22] → [12,22]

[16] ve [11,21] → [11,16,21]
[8] ve [12,22] → [8,12,22]

[11,16,21] ve [8,12,22]
→ [8,11,12,16,21,22]

Big-O Gösterimi:
O(n log n)
