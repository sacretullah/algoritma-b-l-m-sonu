1)
[22,27,16,2,18,6] dizisinin insertion sort aşamalari sirasi ile;

[2,27,16,22,18,6] n
[2,6,16,22,18,27] n-1
[2,6,16,22,18,27] n-2
[2,6,16,18,22,27] n-3
[2,6,16,18,22,27] n-4
[2,6,16,18,22,27] 1

2)
[22,27,16,2,18,6] dizisinin Big-O notasyonu (n.(n+1))/2 'den O(n²) --> (6.(6+1))/2 'den O(6²) olacaktir.
3)
Time Complexity 18 sayisi dizi siralamasindan sonra ortada oldugundan Average case kapsamina girer.
4)
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adimi;

[2,3,5,8,7,9,4,15,6] n
[2,3,5,8,7,9,4,15,6] n-1
[2,3,4,8,7,9,5,15,6] n-2
[2,3,4,5,7,9,8,15,6] n-4
şeklinde olacaktir.

MERGE
[16,21,11,8,12,22]

[16,21,11]    [8,12,22]

[16] [21,11]    [8,12] [22]

[16]    [21]   [11]   [8]   [12]   [22]

[8,11,12,16,21,22]

Big-O gösterimi : O n(logn)



Binary

Binary Search Tree Projesi

root 7

5, 7 den küçük olduğu için soluna gelir

1, 7 ve 5 den küçük olduğu için 5 in soluna gelir

8, 7 den büyük olduğu için 7 nin sağına gelir

3, 7 ve 5 den küçük fakat 1 den büyük olduğu için 1 in sağına gelir

6, 7 den küçük 5 den büyük olduğu için 5 in sağına gelir

0, 7,5 ve 1 den küçük olduğu için 1 in soluna gelir

9, 7 ve 8 den büyük olduğu için 8 in sağına gelir

4, 7,5 den küçük fakat 1 ve 3 den büyük olduğu için 3 ün sağına gelir

2, 7,5 den küçük 1 den büyük fakat 3 den küçük olduğu için 3 ün soluna gelir.
