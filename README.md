# Insertion_sort_project

# Insertion Sort -> [22, 27, 16, 2, 18, 6]

## 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

-First Step : find the smallest element in the array= 2

* Swap 2 with 22 -> [2, 27, 16, 22, 18, 6]
  
-Second Step 

* Swap 27 with 6 -> [2, 6, 16, 22, 18, 27]

-Third Step

* Swap 22 with 18 -> [2, 6, 16, 18, 22, 27]

## 2) Big-O gösterimini yazınız.

* Step 1 -> n

* Step 2 -> n-1

* Step 3 -> n-2

* ....

* Step n-1 -> 1

* sum=(n*(n+1)/2)=(n^(2)+n)/2

 As the input size grows, the term that grows the fastest dominates -> n^(2)

 * Big-O=O(n^2)
  
## 3) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

 Time Complexity:

 -Average case: Aradığımız sayının ortada olması
 
-Worst case: Aradığımız sayının sonda olması

-Best case: Aradığımız sayının dizinin en başında olması.


* 18 sayısı sıralanan dizinin ortasında yer aldığından 'Average Case' kategorisine girer.


## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

* [2,3,5,8,7,9,4,15,6]
* [2,3,5,8,7,9,4,15,6]
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6]