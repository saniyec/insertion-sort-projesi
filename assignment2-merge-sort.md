# Merge Sort  
## Proje 2

### Dizi
[16,21,11,8,12,22] → Merge Sort

### Soru
Yukarıdaki dizinin Merge Sort algoritmasına göre sıralama aşamalarını yazınız.
Big-O gösterimini yazınız.

### Cevap

Merge Sort Aşamaları

1. Bölme (Divide)
[16,21,11,8,12,22]
→ [16,21,11] | [8,12,22]
→ [16] [21,11] | [8] [12,22]
→ [16] [21] [11] | [8] [12] [22]

2. Birleştirme (Merge)
[21] + [11] → [11,21]
[12] + [22] → [12,22]

[16] + [11,21] → [11,16,21]
[8] + [12,22] → [8,12,22]

[11,16,21] + [8,12,22]
→ [8,11,12,16,21,22]

Big-O Gösterimi
O(n log n)
