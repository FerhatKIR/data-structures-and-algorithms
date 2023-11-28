### Proje 1

1. Insertation Sort aşamaları:
```bash
Step:1  [22,27,16,2,18,6] -> 22 Sayısı 27den büyük olduğundan sıralama yapılmadı
Step:2  [22,16,27,2,18,6] -> 16 sayısı 27 ile yer değiştirdi
Step:3  [16,22,27,2,18,6] -> 16 sayısı 22 ile yer değiştirdi
Step:4  [16,22,2,27,18,6] -> 2  sayısı 27 ile yer değiştirdi
Step:5  [16,2,22,27,18,6] -> 2  sayısı 22 ile yer değiştirdi
Step:6  [2,16,22,27,18,6] -> 2  sayısı 16 ile yer değiştirdi
Step:7  [2,16,22,18,27,6] -> 18 sayısı 27 ile yer değiştirdi
Step:8  [2,16,18,22,27,6] -> 18 sayısı 22 ile yer değiştirdi
Step:9  [2,16,18,22,6,27] -> 6  sayısı 27 ile yer değiştirdi
Step:10 [2,16,18,6,22,27] -> 6  sayısı 22 ile yer değiştirdi
Step:11 [2,16,6,18,22,27] -> 6  sayısı 18 ile yer değiştirdi
Step:12 [2,6,16,18,22,27] -> 6  sayısı 16 ile yer değiştirdi.
```

2. Big-O gösterimi : O(n^2).

3. Dizi sıralandıktan sonra 18 sayısı ***Average Case*** kapsamına girer.

4. [7,3,5,8,2,9,4,15,6] Selection Sort'a göre ilk 4 adımı:
```bash
Step:1 [2,3,5,8,7,9,4,15,6] -> 2 ile 7 yer değişti
Step:2 [2,3,4,8,7,9,5,15,6] -> 5 ile 4 yer değişti
Step:3 [2,3,4,5,7,9,8,15,6] -> 5 ile 8 yer değişti
Step:4 [2,3,4,5,6,9,8,15,7] -> 6 ile 7 yer değişti.
```
Ve devamı;
```bash
Step:5 [2,3,4,5,6,7,8,15,9] -> 6 ile 7 yer değişti
Step:6 [2,3,4,5,6,7,8,9,15] -> 9 ile 15 yer değişti.
```
