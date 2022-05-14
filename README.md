# Insertion-Sort
patika.dev - Insertion Sort Projesi

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Çözüm

1. Aşama -> [22,27,16,2,18,6] - n
2. Aşama -> [2,27,16,22,18,6] - n-1
3. Aşama -> [2,6,16,22,18,27] - n-2
4. Aşama -> [2,6,16,18,22,27] - n-3

Time Complexity -> n+(n-1)+(n-2)+(n-3)+...+1 = (n+n^2)/2

Big O notation -> O(n^2)

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Best case de aradığımız sayı en başta, worst case de aradığımız sayı en sonda olduğundan ve 18 sayısı dizinin ortasında bulunduğundan, 18 sayısını verilen dizide insertion sort metodu ile arama işleminde time complexity olarak average case ile karşılaşırız.
