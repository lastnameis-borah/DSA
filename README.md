# DSA

## Complexity

It basically means the time taken for a particular task to be completed. So, for that we can time the code to tell us how long it took (**runtime**).</br>
</br>
But, this will vary depending on the programming language and the computer you're working with.</br>
</br>
That's why use something more abstract (than runtime) called **time complexity**.

</br>
Relation between time and number of values is linear:</br>
Higher the number of values, higher will be the number of operations (one operation == one iteration) and higher will be the time required.

</br>
<p align="center">
    <img src="img/time_complexity.png" alt="example" width="200">
</p>

</br>
Time complexity becomes more and more relevant when number of values increases.

## Big O Notation

Big O notation is used specifically to find the worst case time complexity for an algorithm.</br>
</br>
It is written as $O(n)$ , where '$n$' is the number of values.

<table>
    <tr><th>Time Complexity</th><th>Algorithm</th></tr>
    <tr><td>$O(1)$</td><td>No matter the size of the array, an element can be looked up directly, it just requires one operation (indexing).</br> Eg: print(arr[5])</td></tr>
    <tr><td>$O(n)$</td><td>The algorithm must do $n$ operations in an array with $n$ values to find the lowest value, because the algorithm must compare each value one time.</br> Eg: Finding the lowest number in an array</td></tr>
    <tr><td>$O(n^2)$</td><td>Large data sets slows down these algorithms significantly. With just an increase in n from 10 to 20 values, the number of operations can increase polynomially.</br> Eg: Bubble sort, Selection sort and Insertion sort </td></tr>
    <tr><td>$O(nlog(n))$</td><td>Lies in middle of the previous two.</br> Eg: Quick sort</td></tr>
</table></br>

Here is the visual representation of the time complexities:

</br>
<p align="center">
    <img src="img/time_complexity_visual.png" alt="example" width="400">
</p>