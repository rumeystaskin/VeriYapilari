Soru 1-a:
[22,27,16,2,18,6] --> Insertion Sort
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

Cevap 1-a: 
Öncelikle dizideki en küçük elemanı buluruz ve en baştaki sayı ile yer değiştiririz.
En küçük eleman:2 
Bu işleme n-1 olarak sırayla devam ederiz.
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

Sıralamaların sonucu şu şekildedir: [2,6,16,18,22,27]

Soru 1-b:
Big O gösterimini yazınız.

Cevap 1-b:
n(n+1)/2 ----> O(n^2)

Soru 1-c:
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki caselerden hangisinin kapsamına girer?Yazınız

1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.

Cevap 1-c:
Average Case.

Soru 2:
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort a göre ilk 4 adımını yazınız.

Cevap 2:
[7,3,5,8,2,9,4,15,6] n -----:

[2,3,5,8,7,9,4,15,6] n-1
[2,3,4,8,7,9,5,15,6] n-2
[2,3,4,5,7,9,8,15,6] n-3
[2,3,4,5,6,9,8,15,7] n-4

 