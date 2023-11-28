## Project 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


```bash
                  [16,21,11,8,12,22]

Step1:         [16,21,11] --- [8,12,22]
Step2:     [16,21] - [11] --- [8,12] - [22]
Step3: [16] - [21] - [11] --- [8] - [12] - [22]
Step4:     [16,21] - [11] --- [8,12] - [22]
Step5:         [11,16,21] --- [8,12,22]
Step6:            [8,11,12,16,21,22]
```
Big-O gösterimi O(n*logn)
