# InsertionSortProjesi
Başlangıç seviye java ile backend web development patikası -> Veri yapıları ve algoritmalar > Insertion sort projesi

# Soru: Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# Cevap: Proje 1

1. 1.Adım - [22],27,16,2,18,6
   2.Adım - [22,27],16,2,18,6
   3.Adım - [16,22,27],2,18,6
   4.Adım - [2,16,22,27],18,6
   5.Adım - [2,16,18,22,27],6
   6.Adım - [2,6,16,18,22,27]

2. O(n^2)
3. Average Case: 18, Worst Case: 27, Best Case: 2
4. Average Case

1.Adım - [7],3,5,8,2,9,4,15,6
2.Adım - [3,7],5,8,2,9,4,15,6
3.Adım - [3,5,7],8,2,9,4,15,6
4.Adım - [3,5,7,8],2,9,4,15,6
