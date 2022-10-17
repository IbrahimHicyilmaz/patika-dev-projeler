# Insert Sort Projesi
## [22,27,16,2,18,6] -> Insertion Sort
## Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
### [2,27,16,22,18,6] -> 22 sayısı dizinin sağındaki elemanlar ile karşılaştırılır ve en küçük olan 2 ile yer değişir.
### [2,6,16,22,18,27] -> 27 sayısı dizinin sağındaki elemanlar ile karşılaştırılır ve en küçük olan 6 ile yer değişir.
### [2,6,16,22,18,27] -> 16 sayısı dizinin sağındaki elemanlar ile karşılaştırılır ve yer değiştirmez.
### [2,6,16,18,22,27] -> 22 sayısı dizinin sağındaki elemanlar ile karşılaştırılır ve en küçük olan 18 ile yer değişir.
### [2,6,16,18,22,27] -> 22 sayısı dizinin sağındaki elemanlar ile karşılaştırılır ve yer değiştirmez.
### [2,6,16,18,22,27] -> 27 sayısı dizinin sağında karşılaştırılıcak eleman kalmadığı için yer değiştirmez. 
## Big-O gösterimini yazınız.
### O(n²)
## Time Complexity: 
### Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
### Aradığımız sayı dizinin ortasında olduğu için Average case.