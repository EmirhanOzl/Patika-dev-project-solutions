# Insertion Sort Projesi

## Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  [22,27,16,2,18,6] -> n
  [2,27,16,22,18,6] -> n-1
  [2,6,16,22,18,27] -> n-2
  [2,6,16,18,22,27] -> n-3

## Big-O gösterimini yazınız.

...
(n*(n+1)/2) = (n^2+n)/2

-> O(n^2)
...

## Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

...
Worst case : Sayının (2) en sonda olması -> [27,22,18,16,6,2]
Average case : Sayının (18) ortada olması -> [2,6,16,18,22,27]
Best case : Sayının (2) en başta olması -> [2,6,16,18,22,27]
...

## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

...
-> 18 sayısı ortada olduğu için.
-> Average case
...

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

...
[7,3,5,8,2,9,4,15,6] -> n
[2,3,5,8,7,9,4,15,6] -> n-1
[2,3,4,8,7,9,5,15,6] -> n-2
[2,3,4,5,7,9,8,15,6] -> n-3
...


[patika.dev](https://app.patika.dev/)

