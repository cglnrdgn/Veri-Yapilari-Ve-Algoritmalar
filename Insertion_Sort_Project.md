# Proje1-Insertion Sort
__________________________________________

## [22,27,16,2,18,6] -> Insertion Sort
__________________________________________

### 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
1.Adım : [2,27,16,22,18,6] 
```
```
2.Adım : [2,6,16,22,18,27] 
```
```
3.Adım : [2,6,16,22,18,27]  2.index'ten küçük sayı olmadığı için sabit kaldı 
```
```
4.Adım : [2,6,16,18,22,27]
```
5.Adım :Finish
__________________________________________

### 2.Big-O gösterimini yazınız.

```
n + (n-1) + (n-2) ... + 1 = n(n+1)/2 then The Time Comlexity is O(n^2)
```
__________________________________________

------------------------------------------
 - Not(!):Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması. 
------------------------------------------

### 3.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

```
18 sayısı dizinin ortasında olduğu için Average Case kapsamına girer.
```
__________________________________________
### 4.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
1.Adım : [2, 3, 5, 8, 7, 9, 4, 15, 6]
```
```
2.Adım : [2, 3, 4, 8, 7, 9, 5, 15, 6]
```
```
3.Adım : [2, 3, 4, 5, 7, 9, 8, 15, 6] 
```
```
4.Adım : [2, 3, 4, 5, 6, 9, 8, 15, 7]
```
__________________________________________
