# marge-sort-proje
1) [16,21,11,8,12,22] -> Birleştir Sırala
Yukarıdaki dizinin türüne göre aşamalarını yazıyorsunuz.

- [16, 21, 11] -- [8, 12, 22]
- [16, 21] [11] -- [8, 12] [22]
- [16] [21] [11] -- [8] [12] [22]
- [16, 21] [11] -- [8, 12] [22]
- [11, 16, 21] -- [8, 12, 22]
-[8, 11,12, 16, 21, 22]

2) Big-O gösterimini yazın.
Adım 1 -> n
Adım 2 -> yok
Adım 3 -> yok
....
Adım (n-1) -> (n-1)/2^(n-2)

toplam = n + n/2 + ... = n(1 + 1/2 + ...) = nlogn
O(nlogn)
