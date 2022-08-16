# Big O Notation :
**Big O notation**, also called “[asymptotic analysis](https://www.tutorialspoint.com/data_structures_algorithms/asymptotic_analysis.htm)” 
It actually tells us how much time to run and space required (memory) for your program, So,we have to take care of both running time and the memory (RAM) our program uses during execution.
 
How many operations a sorting algorithm takes to completely sort a very large collection of data. This is a measure of efficiency and is how &emsp;you can directly compare one algorithm to another.
 
### When to use ? :
When building a simple app with only a few pieces of data to work through, this sort of analysis is unnecessary. But when working with very &emsp;**large amounts of data, like a social media site or a large e-commerce site with many customers and products, small differences between &emsp;algorithms can be significant**.
 
### O(n) :
Big O notation ranks an algorithms’ efficiency **O(n)** where, \
O is the order of function or growth rate, \
n is the length of array (0,1,2,3,4,5 ,..................,n) ,
 
### Example :
 
_NOTE : Always pick the the terms with higher power ignore the smaller , coefficients, and constants._
 
**12n^5 - 6n^3 + 5** => 12 , 6 are coefficients, and 5 is constant here.
 
In above equation **_select the one with high time complexity_** **( 12n^5)** ignore **6n^3 + 5**, because the higher matters. We are left with **n^5** 
Therefore, this function would have an **order growth rate**, or a **“big O”** rating, of **O(n^5)** .  
 
 
### Some common Algorithms :
 
&emsp;- Quick Sort\
&emsp;- Heap Sort\
&emsp;- Merge Sort
 
They runs at rate of **O(n log n)**.\
Most software use **Quick sort by Default**. Some other sorting algos **Bubble / Insertion / Selection Sort run at O(n²)**. \
So, they take **significantly longer time**
 
>NOTE : Select the algorithm according to your problem because you can't use the same algo for all problems. They have different time complexities for different problems, where they perform as best or worst.
 
**Conclusion** You have to choose the algorithms according to time and space. Like how much time will the code take in execution and the &emsp;space (memory) required for it.
So, with larger data sets you have to take care of both, and with small programs (data) they don't matter much.
 
#### BIG O :
<p align="center">
  <img src="https://user-images.githubusercontent.com/45902447/184523429-3829455a-1104-4614-8f56-7e1ec47b7722.png">
</p>
 
#### DATA structures :
<p align="center">
  <img src="https://user-images.githubusercontent.com/45902447/184523435-29e040f9-733c-4365-8cfc-b68e394c737f.png">
</p>

#### Sorting Algorithms:
<p align="center">
  <img src="https://user-images.githubusercontent.com/45902447/184523438-ada081a4-d739-417e-8513-a662bcfdc58d.png">
</p>

Source : [bigocheatsheet](https://www.bigocheatsheet.com)

_Updates are coming !_
