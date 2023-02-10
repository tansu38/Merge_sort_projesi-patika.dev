# Merge Sort Projem

[16,21,11,8,12,22]
Merge sort türüne göre aşamaları:

1. Aşama --> dizi iki parçaya ayrılır.
[16,21,11]                        [8,12,22]
2. Aşama --> Elde edilen dizi tekrar ikiye ayrılır.
[16]    [21,11]           [8]       [12,22]
3. Aşama --> Dizideki iki diziler tekrar ikiye ayrılır.
[16]    [21]   [11]       [8]    [12]  [22]
4. Aşama --> 3. aşamada en son böldüğümüz dizileri birleştirmeye başlıyoruz. Birleştirme küçükten büyüğe doğru yapılır.
[16]    [11,21]           [8]       [12,22] 
5. Aşama:
[11,16,21]                        [8,12,22]
6. Aşama:
[8,11,12,16,21,22]

Big-O : nlog(n)

# Site
[patika.dev](https://www.patika.dev/tr)
