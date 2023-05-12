# -dev

Proje 1 - Selection Sort

[22,27,16,2,18,6] -> Insertion Sort
A) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
B) Big-O gösterimini yazınız.
C) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki
case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
D) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını
yazınız.



Cevap
A) I [2,27,16,22,18,6]
 II [2,6,16,22,18,27]
 III [2,6,16,18,22,27]
 
B) n+(n-1)+(n-2).....+1 = n^2/2 = Dominant olan n^2 dir. Big-O = O(n^2).

C) Average case: Aradığımız sayının ortada olması

D) I [2,3,5,8,7,9,4,15,6]
 II [2,3,4,8,7,9,5,15,6]
 III [2,3,4,5,7,9,8,15,6]
 IV [2,3,4,5,6,9,8,15,7]
