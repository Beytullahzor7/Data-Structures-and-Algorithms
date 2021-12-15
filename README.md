# Data-Structures-and-Algorithms
Data Structures and Algorithms Homework from PatikaDev


[22,27,16,2,18,6] -> Insertion Sort

##### Yukarıda verilen dizinin Sort türüne göre aşamalarını yazınız.
<ul>
<li>Big-O gösterimini yazınız.
<li>Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.</li>
<li>Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.</li>
</ul> 


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.</li>


```
[22,27,16,2,18,6] => Aşama 1 (n)

[2,27,16,22,18,6] => Aşama 2 (n-1)

[2,6,16,22,18,27] => Aşama 3 (n-2)

[2,6,16,18,22,27] => Aşama 4 (1)
```

```
n + (n-1) + (n-2) + 1 = n.(n+1) / 2 

(n^2 +n) / 2 = O(n^2)
```

```
Average Case
[2,6,16,18,22,27] => 16,18
Worst Case
[2,6,16,18,22,27] => 27
Best Case 
[2,6,16,18,22,27] => 2
```

```
Average Case
```
