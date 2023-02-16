Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

***************************************************************************************************************

# ÇÖZÜM

Adım 1: [16,21,11]  ,  [8,12,22] --> (Diziyi tam ortadan böldük.) <br>
Adım 2: [16] [21,11]  ,  [8,12] [22] --> (Tek eleman kalıncaya kadar parçalıyoruz.) <br>
Adım 3: [16] [21] [11]  ,  [8] [12] [22] --> (Tek elemanları elde ettik.) <br>
Adım 4: [11,16,21]  ,  [8,12,22] --> (Kendi içlerinde sıralı hale getirdik.) <br>
Adım 5: [8,11,12,16,21,22] --> (Sıralama işlemini bitirdik.) <br><br>

Big-O gösterimi: O(nlogn)