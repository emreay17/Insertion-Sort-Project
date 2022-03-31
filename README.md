
# Insertion Sort Projesi 

## Insertion Sort
 
 **Dizi : [22,27,16,2,18,6]**
 Basamaklar : ilk elemandan başlanarak tüm dizi taranır ve küçük olanlar soldan sıralanacak şekilde yer değiştirme yöntemi ile ilerler.
		
		 1-[2,27,16,22,18,6] (n)
		 2-[2,6,16,22,18,27] (n-1)
		 3	-[2,6,16,18,22,27 (n-2)
#### Big-O  notation formülümüz ise ;
	n+(n-1)+(n-2)....+1 = O(n²)
#### Time Complexity :
##### Average Case ; [7,3,5,8,2,9,4,15,6] dizisi nin Insertion Sort a göre ilk 4 adımı şu şekildedir;
	Aradıgımız sayinin ortada olması 
##### Best Case ; 
	Aradıgımız sayinin en başta olması
##### Worst Case ; 
	Aradıgımız sayinin en sonda olması

 **Dizi siralandıktan sonra 18 sayisi Average Case kapsamındadır.**

####  [7,3,5,8,2,9,4,15,6] dizisi nin Insertion Sort a göre ilk 4 adımı şu şekildedir;
	1- [2,3,5,8,7,9,4,15,6]
	2- [2,3,4,8,7,9,5,15,6]
	3- [2,3,4,5,7,9,8,15,6]
	4- [2,3,4,5,6,9,8,15,7]
