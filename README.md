# insertion_sort
[22, 27, 16, 2, 18, 6]----- n
22 27 16 2 18 6 -----------n-1
16 22 27 2 18 6------------n-2
2 16 18 22 27 6------------n-3
2 16 18 22 27 6------------n-4
2 6 16 18 22 27------------1
18 sayısı insseriton sort a göre sıralandığına göre "Avarage Case" e dahil olur.
Big_O Gösterimi ise:
n+ (n-1)+ (n-2)+ (n-3)+ (n-4)+1 = n*(n+1)/2 = n^2
# selection_sort
[7 3 5 8 2 9 4 15 6]
2 3 5 8 7 9 4 15 6
2 3 4 8 7 9 5 15 6
2 3 4 5 7 9 8 15 6
2 3 4 5 6 9 8 15 7
İlk 5 adım izlenmiştir.
