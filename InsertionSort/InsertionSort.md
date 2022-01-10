
# Proje Konusu ve Cevaplanacak Sorular:

## [22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

* Big-O gösterimini yazınız.

* Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

# Cevaplar:
[22,27,16,2,18,6] :

####  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız:
*[22|27,16,2,18,6]
*[22,27|16,2,18,6] 
*[22,16,27|2,18,6] 
*[16,22,27|2,18,6] 
*[16,22,2,27|18,6] 
*[16,2,22,27|18,6]
*[2,16,22,27|18,6]
*[2,16,22,18,27|6]
*[2,16,18,22,27|6]
*[2,16,18,22,6,27|]
*[2,16,18,6,22,27|]
*[2,16,6,18,22,27|]

* [2,6,16,18,22,27|]

#### Big-O gösterimini yazınız:

* Best Case: O(N)
* Average Case: O(N^2)
* Worst Case: O(N^2)

#### Time Complexity:
* Best Case: 2
* Average Case: 16,18
* Worst Case: 27

#### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?*
* Average Case.

#### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.*

*[3,7|5,8,2,9,4,15,6]
*[3,5,7|8,2,9,4,15,6]
*[3,5,7,8|2,9,4,15,6]

* [3,5,7,2,8|9,4,15,6]
