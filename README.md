# Merge-Sort
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje
Merge Sort Project 2
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Cevap:
Merge Sort diziyi tek elemanlı olarak parçalayana kadar sürekli ikiye böler.

Adımlar	Bölme Ve Birleştirme

1.Bölme	[16,21,11] [8,12,22]

2.Bölme	[16] [21,11] [8] [12,22]

3.Bölme	[16] [21] [11] [8] [12] [22]

1.Birleştirme	[16] [11,21] [8] [12,22]

2.Birleştirme	[11,16,21] [8,12,22]

3.Birleştirme	[8,11,12,16,21,22]

Big-O gösterimi:
O(nlogn)
