# Merge-Sort-Project-Patika

Merge Sort aşamaları:


Dizi iki eşit parçaya bölünür.



Her bir parçaya ayrı ayrı merge sort uygulanır.



Her iki parçanın sıralanmış halini birleştirerek dizinin tamamı sıralanır.



[16,21,11,8,12,22] Merge Sort


    [16,21,11]       [8,12,22]
   [16,21] [11]     [8] [12,22]
 [16] [21] [11]    [8] [12] [22]
[16]   [11,21]      [8]    [12,22] 
    [11,16,21]     [8,12,22]
       [8,11,12,16,21,22]



Big-O gösterimi: O(n log n)




Time Complexity: En kötü durumda (worst case) O(n log n) süresi içinde sıralanır.
