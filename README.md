# Insertion-Sort-Projesi

## [22,27,16,2,18,6]

## 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
```

## 2. Big-O gösterimini yazınız.
```
n.(n+1)/2 >>> (n²+n)/2
O(n²)
```

## 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması
### Avarage case
```
[2,16,6,22,18,27]
```
### Worst case
```
[27,22,18,16,6,2]
```
### Best case
```
[2,6,16,18,22,27]
```

## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
Avarage case çünkü sıraladıktan sonra 18 sayısı ortada kalıyor.
```

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1 - [2,3,5,8,7,9,4,15,6]
2-  [2,3,4,8,7,9,5,15,6]
3-  [2,3,4,5,7,9,8,15,6]
4-  [2,3,4,5,6,9,8,15,7]
```
