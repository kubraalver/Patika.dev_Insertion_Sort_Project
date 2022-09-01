# Veri Yapıları ve Algoritmalar
Patika.dev Final Project
# Insertion Sort Project
[22,27,16,2,18,6] - Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2. Big-O gösterimini yazınız.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


---

## Insertion Sort Steps
[22,27,16,2,18,6] - (n)

[2|,27,16,22,18,6] - (n-1)

[2,6|,16,22,18,27] - (n-2)

[2,6,16|,18,22,27] - (n-3)

---

## Big O Notation
Worst Case: O(n²) = n+(n-1)+(n-2)....+1 = n*(n+1)/2= (n^2+n)/2

Average Case: O(n²)

Best Case: O(n)

---


## Time Complexity
Worst Case: [27,22,18,16,6,2] --- O(n²)

Average Case: O(n²)

Best Case: [2,6,16,18,22,27] --- O(n)

---


## Which Case for 18?
The array is sorted from smallest to largest [2,6,16,18,22,27]. The number 18 is the middle of this array. So it falls within the scope of the average case.

---

## First 4 Insertion Sort Steps for [7,3,5,8,2,9,4,15,6]
[2|,3,5,8,7,9,4,15,6]

[2,3|,5,8,7,9,4,15,6]

[2,3,4|,8,7,9,5,15,6]

[2,3,4,5|,7,9,8,15,6]


---


[Patika.dev](https://www.patika.dev/tr)