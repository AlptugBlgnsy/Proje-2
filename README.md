# Proje-2 Veri Yapıları ve Algoritmalar
[Patika.dev](https://www.patika.dev/tr)
[16,21,11,8,12,22] -> Merge Sort

##Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

##Big-O gösterimini yazınız.

ÇÖZÜMLEME

##[16,21,11,8,12,22] dizi öncelikle ikiye bölünür.

  [16,21,11]   [8,12,22]  oluşan iki dizi tekrar ikiye bölünür.

[16,21] [11]   [8]  [12,22] Dizi içersinde tek eleman kalana kadar bölünür.

   [16][21][11][8][12][22] Oluşan dizi tekrar ikili şekilde birleştirlir.
   
## [16][21][11][8][12][22]

[16,21] [11]   [8]  [12,22]

[16,21,11,8,12,22]

##Big-O 

O(nlogn)

-Worst Case: O(nlogn) -Average Case: O(nlogn) -Best Case: O(n*logn)
