# Merge-Sort-Projesi
www.patika.dev

1- [16,21,11,8,12,22] Dizisinin Merge Sort Aşamaları:

Diziyi İkiye Bölüyoruz  -> [16,21,11]   -    [8,12,22]	

Sağ ve Sol parçaları tekrar ikiye bölüyoruz -> [16,21]-[11]   -   [8]-[12,22]

Tek Elemana Haline Gelecek Şekilde Ayırıyoruz ->  [16]-[21]  [11]    - [8]    [12]-[22]

İkili Şekilde Sıralayarak Birleştiriyoruz -> [16,21]-[11]   -  [8]-[12,22]

Tekrar ikili şekilde sıralayarak birleştiriyorız -> [11,16,21] - [8,12,22]

Son birleştirme ve sıralama ile dizi elde ediliyor -> [8,11,12,16,21,22]

2- Big-O Gösterimi:

O(n(logn) -> 6(log6)
