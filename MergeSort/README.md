# Merge Sort Projesi
## Proje 2

[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

---
## Cevaplar
- Aşamalar:
1. Diziyi ikiye böl:  
   Sol:    [16, 21, 11]  
   Sağ:    [8, 12, 22]
2. Alt dizileri tekrar ikiye böl:
      Sol: [16, 21, 11]  
   [16] [21, 11]  
   [16] -> zaten tek eleman  
   [21, 11] -> [21] [11] -> sırala -> [11, 21]  
   Sonuç: [16] + [11, 21] -> merge -> [11, 16, 21]  
      Sağ: [8, 12, 22]  
   [8] [12, 22]  
   [8] -> tek eleman  
   [12, 22] -> [12] [22] -> sırala -> [12, 22]  
   Sonuç: [8] + [12, 22] -> merge -> [8, 12, 22]  

3. İki ana parçayı birleştir:  
[11, 16, 21] ve [8, 12, 22] merge:  
   Karşılaştır ve sırala:
8 < 11 → [8]  
11 < 12 → [8,11]  
12 < 16 → [8,11,12]  
16 < 22 → [8,11,12,16]  
21 < 22 → [8,11,12,16,21]  
22 → [8,11,12,16,21,22]  

Sonuç:  
  [8, 11, 12, 16, 21, 22]

- Big-O Gösterimi  

En iyi (Best Case): O(n log n)  
Ortalama (Average Case): O(n log n)  
En kötü (Worst Case): O(n log n)