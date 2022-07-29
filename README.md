# insertion-sort
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.
3)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

1)Insertion sort aşamaları:
 [22| 27 16 2 18 6] -< n : First pass
 [2 27| 16 22 18 6] -< n-1:Second pass
 2 16 27 22 18 6
 2 16 22 27 18 6
 2 16 22 18 27 6
 2 16 22 18 6 27
 2 16 22 6 18 27
 2 16 6 22 18 27
 [2 6 16| 22 18 27]-< n-2:Third pass
 
 [2 6 16 22| 18 27] -< 1
 2 6 16 18 22 27
 

 
2)Big-0 : n+n-1+n-2+...+1=(n²+n)/2 ->> O(n²)
 worst case
 
4)18 mid sayıdır =>average case

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

 
                        
 
 
