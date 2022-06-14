# insertion sort projesi

[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
[2,6,16,18,22,27]
[2,6,16,18,22,27]

2-Big-O gösterimini yazınız.
[2,27,16,22,18,6] n
[2,6,16,22,18,27] n-1
[2,6,16,22,18,27] n-2
[2,6,16,18,22,27] n-3
[2,6,16,18,22,27] n-4
[2,6,16,18,22,27] n-5
n*(n+1)/2 kadar işlem
en büyük n*2
Big o Notation Her turda aynı elemanlar üzerinden dolaştığı için en kötü ihtimalle O(n²)dir.

3-Time Complexity Dizi sıralanmasından sonra 18 sayısı ortada olduğundan dolayı Average case kapsamına girer.

4[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6] n 
[2,3,5,8,7,9,4,15,6] n-1 
[2,3,4,8,7,9,5,15,6] n-2 
[2,3,4,5,7,9,8,15,6] 1
