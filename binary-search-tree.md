Soru:
[7,5,1,8,3,6,0,9,4,2] dizinin Binary-Search-Tree aşamalarını yazınız.

Cevap:
Dizideki ilk eleman olan 7 root olarak seçtim.
Root düğümünden küçük olan elemanları sol tarafa büyük olan elemanları sağ tarafa yerleştirdim.
Bu adımları her bir alt treede tekrarlıyorum.

root:7
root 7'nin soluna 5'i eklerim.
1'i de sola eklerim.
8'i kökün sağına yerleştiririm.
3'ü 5'in soluna eklerim.
6'yı 5'in sağına eklerim.
0'ı 1'in soluna eklerim.
9'u 8'in sağına eklerim.
4'ü 3'ün sağına eklerim.
2'yi 3'ün soluna eklerim.

7
/ \
5  8
/\  \
1 6   9
/\
0 3
  / \
  2  4