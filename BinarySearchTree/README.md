# Binary Search Tree Projesi
## Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

## Cevap
- 7 root’tur.
- 5, 7’den küçük → 7'nin soluna 5 eklenir.
- 1, 5’ten küçük → 5’in soluna 1 eklenir.
- 8, 7’den büyük → 7’nin sağına 8 eklenir.
- 3, 1’den büyük → 1’in sağına 3 eklenir.
- 6, 5’ten büyük → 5’in sağına 6 eklenir.
- 0, 1’den küçük → 1’in soluna 0 eklenir.
- 9, 8’den büyük → 8’in sağına 9 eklenir.
- 4, 3’ten büyük → 3’ün sağına 4 eklenir.
- 2, 3’ten küçük → 3’ün soluna 2 eklenir.


```
           7
         /   \
        5     8
       / \     \
      1   6     9
     / \
    0   3
       / \
      2   4 
```