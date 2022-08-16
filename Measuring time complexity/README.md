#### Refresh :

<p align = "center" >
  <img src="https://user-images.githubusercontent.com/45902447/184863549-e256cd4b-4616-4dc8-b649-c052b7fab0a9.png">
  <img src="https://user-images.githubusercontent.com/45902447/184863651-86032b6f-167b-40dc-8f31-3b25cf9c0d8c.png">
</p>

### O(n):

Lets see an example of arrays

when array size increases the time increases , but we don't know there relation,yet/

we have an array, with size increasing n * 100000, n is 1,2,3,4.....n, we can see the is also increasing by 0.01 while this may be different for your system it depends on
your computer speed, environment. Big -O is actually like a rough estimation

`{'ArraySize_0': '0.00', 'ArraySize_100000': '0.01', 'ArraySize_200000': '0.02', 'ArraySize_300000': '0.03', 'ArraySize_400000': '0.04'}`

From this example we can see that time is increasing linearly with array size, let plot it to see visuals.
<p align = "center" >
  <img src="https://user-images.githubusercontent.com/45902447/184865043-dd2ca96d-8404-4159-b5d3-0549d44946e7.png">
</p>

>NOTE : time can be different for high speed computers.

From the above plot we can see clearly there relation it is **linear**. As we know **straight line is y = mx + c**, 
but here **y = time, x = size of an array**.\
&ensp; **time = mn +c or time = m*n + C**\
As we discussed before in **Big O** that we ignore **constants** and **smaller values**, So, this equation will become **time = m * n** , 
Now, we know **"m"** will also **stay constant (not changing)**, remove it, we will be left with **time = n**.

In short we are concerned about the value which keeps growing !\
So, The Big-O time complexity for this program is of Order n or **O(n)**.

__Single loop is an example of O(n), It is like where you don't know the **exact index of element** so you have to **loop through all (n)**, if you know the exact index then it will be **constant O(1)**
The more the computation power your program uses, the more it will take time.__

_update Coming_
