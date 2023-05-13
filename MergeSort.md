Soru: 
[16,21,11,8,12,22] --> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Cevap:
Öncelikle diziyi her adımda parçalara ayırıp
 tek eleman kalıncaya kadar bölmemiz gerekiyor.

İlk adımda diziyi iki eşit parçaya böleriz.
Sol: [16,21,11] Sağ:[8,12,22]
Bu ayırdığımız parçaları da ayrı ayrı tekrar parçalıyoruz.
Sol parça: 
sol: [16] ve sağ: [21,11]
sol kısım tek eleman kaldığı için oradaki bölme işlemimizi bitiriyoruz.
sağ kısmı tekrar ikiye böleriz.
sol:[21] sağ[11]
Parçaları böldükten sonra sıralı şekli;
Sol parça:[21] Sağ Parça:[11]
Daha sonra sıraladığımız parçaları birleştiririz.
[11,16,21]

Sıra ilk adımdaki sağ parçayı bölme işleminde,
Sağ:[8,12,22] dizisini ikiye böleceğiz.
sol:[8] sağ:[12,22]
sol kısım tek eleman kaldığından aynen bırakıyoruz.
sağ kısımı tekrar ikiye bölüyoruz.
sol:[12] sağ:[22]
Parçaları böldükten sonra sıralı şekli;
Sol parça:[12] Sağ parça:[22]
Daha sonra yine sıraladığımız parçaları birleştiririz.
[8,12,22]

Sıralamış olduğumuz iki parçayı birleştiririz.
Sol parça:[11,16,21] Sağ Parça:[8,12,22]

Merge Sort ile sıralanmış Sonuç:[8,11,12,16,21,22]

Big O Gösterimi---> O(nlogn)
