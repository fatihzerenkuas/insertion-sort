## **Sorular**
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## **Cevaplar**
1. 
    * İlk sayı ile dizindeki en küçük sayı yer değiştirecek. (n) **[2,27,16,22,18,6]**
    * İkinci sayı ile dizindeki ikinci en küçük sayı yer değiştirecek. (n-1) **[2,6,16,22,18,27]**
    * Üçüncü sayı (16) zaten üçüncü en küçük sayı o yüzden yerinde kalacak. (n-2) **[2,6,16,22,18,27]**
    * Dördüncü sayı ile dizindeki dördüncü en küçük sayı yer değiştirecek. (n-3) **[2,6,16,18,22,27]**
    * Beşinci sayı (22) zaten beşinci en küçük sayı o yüzden yerinde kalacak. (n-4) **[2,6,16,18,22,27]**
___
2. n+(n-1)+(n-2)...+1 = (n2+n)/2 

    Big-O Notation'da önemli olan dominant sayı olduğu için Time Complexity'si **O(n2)** olarak gösterilir.

___
4. 18 dizinin ortalarında olduğu için Average Case kapsamına girer.
___
*[7,3,5,8,2,9,4,15,6]* sayı dizisi sırasıyla şu adımlardan geçerek sıralanmış olur:
* ***[2,3,5,8,7,9,4,15,16]***
* ***[2,3,4,8,7,9,5,15,16]***
* ***[2,3,4,5,7,9,8,15,16]***
* ***[2,3,4,5,7,8,9,15,16]***
