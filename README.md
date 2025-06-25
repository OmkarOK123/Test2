<h3>🔢 C Program: Print All Negative Elements in an Array</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print all negative elements in an array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n, i;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter %d elements: "</span>, n);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

printf(<span style="color: brown;">"Negative elements in array are:\n"</span>);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++) {
    <span style="color: blue;">if</span> (arr[i] &lt; 0)
        printf(<span style="color: brown;">"%d "</span>, arr[i]);
}

<span style="color: blue;">return</span> 0;
 

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>User inputs the size of the array and its elements.</li>
  <li>The program iterates through each element and checks if it is negative.</li>
  <li>If a value is negative (<code>&lt; 0</code>), it is printed.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 6
Enter 6 elements: 5 -3 8 -2 0 -7
Negative elements in array are:
-3 -2 -7</pre>


<h3>🔢 C Program: Print Array Elements in Reverse Order</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print array elements in reverse order</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n, i;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter %d elements: "</span>, n);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

printf(<span style="color: brown;">"Array in reverse order:\n"</span>);
<span style="color: blue;">for</span> (i = n - 1; i &gt;= 0; i--)
    printf(<span style="color: brown;">"%d "</span>, arr[i]);

<span style="color: blue;">return</span> 0;
 

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>User inputs the number of elements and the array values.</li>
  <li>The second loop runs from <code>n - 1</code> down to <code>0</code>.</li>
  <li>Each element is printed in reverse order of entry.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 5
Enter 5 elements: 10 20 30 40 50
Array in reverse order:
50 40 30 20 10
</pre>


<h3>🔢 C Program: Sum of All Elements in an Array</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to find the sum of all elements in an array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n, i, sum = 0;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter elements: "</span>);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++) {
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);
    sum += arr[i];
}

printf(<span style="color: brown;">"Sum of array elements = %d\n"</span>, sum);

<span style="color: blue;">return</span> 0;
 

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>User inputs the number of elements and values into an array.</li>
  <li>A loop runs to take input and simultaneously adds each element to <code>sum</code>.</li>
  <li>The total sum is printed after the loop.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 4
Enter elements: 10 20 30 40
Sum of array elements = 100
</pre>


<h3>🔢 C Program: Count Even and Odd Elements</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to count even and odd elements in an array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n, i, even = 0, odd = 0;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter elements: "</span>);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++) {
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);
    <span style="color: blue;">if</span> (arr[i] % 2 == 0)
        even++;
    <span style="color: blue;">else</span>
        odd++;
}

printf(<span style="color: brown;">"Even = %d, Odd = %d\n"</span>, even, odd);

<span style="color: blue;">return</span> 0;
 

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>User inputs the size and elements of the array.</li>
  <li>Each element is checked using modulus <code>%</code> to determine even or odd.</li>
  <li>Separate counters <code>even</code> and <code>odd</code> are incremented accordingly.</li>
  <li>The final count of even and odd numbers is displayed.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 6
Enter elements: 12 7 9 4 2 5
Even = 3, Odd = 3
</pre>


<h3>🔢 C Program: Sort Array in Ascending or Descending Order</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to sort an array in ascending or descending order</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n, i, j, temp, choice;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter elements: "</span>);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

printf(<span style="color: brown;">"1. Ascending\n2. Descending\nEnter your choice: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;choice);

<span style="color: blue;">for</span> (i = 0; i &lt; n-1; i++) {
    <span style="color: blue;">for</span> (j = i + 1; j &lt; n; j++) {
        <span style="color: blue;">if</span> ((choice == 1 &amp;&amp; arr[i] &gt; arr[j]) ||
            (choice == 2 &amp;&amp; arr[i] &lt; arr[j])) {
            temp = arr[i];
            arr[i] = arr[j];
            arr[j] = temp;
        }
    }
}

printf(<span style="color: brown;">"Sorted array:\n"</span>);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++)
    printf(<span style="color: brown;">"%d "</span>, arr[i]);

<span style="color: blue;">return</span> 0;
 

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li><strong>Step 1:</strong> Take input for number of elements and the array itself.</li>
  <li><strong>Step 2:</strong> Ask user if they want to sort in ascending or descending order.</li>
  <li><strong>Step 3:</strong> Use nested loops to compare and swap values as needed (Bubble Sort logic).</li>
  <li><strong>Step 4:</strong> Print the sorted array.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 5
Enter elements: 9 2 7 4 1
1. Ascending
2. Descending
Enter your choice: 1
Sorted array:
1 2 4 7 9
</pre>


<h3>🔢 C Program: Count Duplicate Elements in an Array</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to count duplicate elements in an array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n, i, j, count = 0;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter array elements: "</span>);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

<span style="color: blue;">for</span> (i = 0; i &lt; n; i++) {
    <span style="color: blue;">for</span> (j = i + 1; j &lt; n; j++) {
        <span style="color: blue;">if</span> (arr[i] == arr[j]) {
            count++;
            <span style="color: blue;">break</span>; <span style="color: green;">// Avoid multiple counts for same element</span>
        }
    }
}

printf(<span style="color: brown;">"Total duplicate elements = %d\n"</span>, count);

<span style="color: blue;">return</span> 0;
 

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li><strong>Step 1:</strong> Accept number of elements and store values in an array.</li>
  <li><strong>Step 2:</strong> Use nested loops to compare each element with all others.</li>
  <li><strong>Step 3:</strong> If a match is found, increment the <code>count</code> and break to avoid double-counting.</li>
  <li><strong>Step 4:</strong> Print the total number of duplicate elements.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 6
Enter array elements: 1 2 3 2 4 1
Total duplicate elements = 2
</pre>


<h3>🔢 C Program: Insert Element at a Specific Position</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to insert an element at a specific position in an array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n, i, pos, val;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter elements: "</span>);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

printf(<span style="color: brown;">"Enter position to insert (1 to %d): "</span>, n+1);
scanf(<span style="color: brown;">"%d"</span>, &amp;pos);
printf(<span style="color: brown;">"Enter value to insert: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;val);

<span style="color: blue;">for</span> (i = n; i &gt;= pos; i--)
    arr[i] = arr[i - 1];

arr[pos - 1] = val;
n++;

printf(<span style="color: brown;">"Array after insertion:\n"</span>);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++)
    printf(<span style="color: brown;">"%d "</span>, arr[i]);

<span style="color: blue;">return</span> 0;
 

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li><strong>Step 1:</strong> Take input of number of elements and their values.</li>
  <li><strong>Step 2:</strong> Ask for the position (1-based index) where new value needs to be inserted.</li>
  <li><strong>Step 3:</strong> Shift all elements from the end to the right starting at the position.</li>
  <li><strong>Step 4:</strong> Insert the new value at the given position.</li>
  <li><strong>Step 5:</strong> Print updated array.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 5
Enter elements: 1 2 3 4 5
Enter position to insert (1 to 6): 3
Enter value to insert: 99
Array after insertion:
1 2 99 3 4 5
</pre>


<h3>🔍 C Program: Search Element in an Array</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to search for an element in an array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n, i, key, found = 0;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter elements: "</span>);
<span style="color: blue;">for</span> (i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

printf(<span style="color: brown;">"Enter element to search: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;key);

<span style="color: blue;">for</span> (i = 0; i &lt; n; i++) {
    <span style="color: blue;">if</span> (arr[i] == key) {
        found = 1;
        <span style="color: blue;">break</span>;
    }
}

<span style="color: blue;">if</span> (found)
    printf(<span style="color: brown;">"Element %d found at position %d.\n"</span>, key, i + 1);
<span style="color: blue;">else</span>
    printf(<span style="color: brown;">"Element %d not found.\n"</span>, key);

<span style="color: blue;">return</span> 0;
 

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li><strong>Step 1:</strong> Input the size and elements of the array.</li>
  <li><strong>Step 2:</strong> Input the element (key) to be searched.</li>
  <li><strong>Step 3:</strong> Traverse the array using a <code>for</code> loop.</li>
  <li><strong>Step 4:</strong> If any element matches the key, set <code>found = 1</code> and break.</li>
  <li><strong>Step 5:</strong> Print position if found, otherwise show "not found" message.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 5
Enter elements: 10 20 30 40 50
Enter element to search: 30
Element 30 found at position 3.
</pre>


<h3>📥 C Program: Accept and Print Array Elements (With Argument, No Return)</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to accept and print array elements using a function with argument</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">void</span> printArray(<span style="color: blue;">int</span> arr\[], <span style="color: blue;">int</span> n) {
printf(<span style="color: brown;">"Array Elements are:\n"</span>); <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i < n; i++)
printf(<span style="color: brown;">"%d "</span>, arr\[i]);
}

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n;

 
printf(<span style="color: brown;">"Enter total number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter %d elements:\n"</span>, n);
<span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

printArray(arr, n);

<span style="color: blue;">return</span> 0;
 

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li><strong>Function:</strong> <code>printArray()</code> accepts an array and its size, then prints the elements.</li>
  <li><strong>Main Function:</strong> Accepts array size and elements, then passes to <code>printArray()</code>.</li>
  <li>Function does not return anything; it only performs the task (printing).</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter total number of elements: 5
Enter 5 elements:
10 20 30 40 50
Array Elements are:
10 20 30 40 50
</pre>


<h3>📋 C Program: Copy Array into Another Array (With Argument, No Return)</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to copy one array into another using a function</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">void</span> copyArray(<span style="color: blue;">int</span> src\[], <span style="color: blue;">int</span> dest\[], <span style="color: blue;">int</span> n) { <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i < n; i++)
dest\[i] = src\[i];

 
printf(<span style="color: brown;">"Copied Array:\n"</span>);
<span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; n; i++)
    printf(<span style="color: brown;">"%d "</span>, dest[i]);
 

}

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> src\[100], dest\[100], n;

 
printf(<span style="color: brown;">"Enter total number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter %d elements:\n"</span>, n);
<span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;src[i]);

copyArray(src, dest, n);

<span style="color: blue;">return</span> 0;
 

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li><strong>Function:</strong> <code>copyArray()</code> copies elements from source array to destination array.</li>
  <li>Both arrays and the count are passed as arguments to the function.</li>
  <li>Function also prints the copied array directly.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter total number of elements: 4
Enter 4 elements:
10 20 30 40
Copied Array:
10 20 30 40
</pre>


<h3>🔁 C Program: Display Array Elements Using Recursion</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to display array elements using recursion</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">void</span> display(<span style="color: blue;">int</span> arr\[], <span style="color: blue;">int</span> index, <span style="color: blue;">int</span> n) { <span style="color: blue;">if</span> (index >= n) <span style="color: blue;">return</span>;

 
printf(<span style="color: brown;">"%d "</span>, arr[index]);
display(arr, index + 1, n);
 

}

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter %d elements:\n"</span>, n);
<span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

printf(<span style="color: brown;">"Array elements are:\n"</span>);
display(arr, 0, n);

<span style="color: blue;">return</span> 0;
 

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li>The function <code>display()</code> prints each element of the array one by one using recursion.</li>
  <li><code>index</code> starts from 0 and increases with each recursive call.</li>
  <li>Recursion ends when index becomes equal to or greater than array size <code>n</code>.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 5
Enter 5 elements:
11 22 33 44 55
Array elements are:
11 22 33 44 55
</pre>


<h3>➕ C Program: Find Sum of Elements Using Recursion</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to find sum of array elements using recursion</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> sumArray(<span style="color: blue;">int</span> arr\[], <span style="color: blue;">int</span> index, <span style="color: blue;">int</span> n) { <span style="color: blue;">if</span> (index >= n) <span style="color: blue;">return</span> 0; <span style="color: blue;">return</span> arr\[index] + sumArray(arr, index + 1, n);
}

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter elements:\n"</span>);
<span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

<span style="color: blue;">int</span> sum = sumArray(arr, 0, n);
printf(<span style="color: brown;">"Sum of array elements = %d\n"</span>, sum);

<span style="color: blue;">return</span> 0;
 

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li>The <code>sumArray()</code> function uses recursion to calculate the sum of elements.</li>
  <li>Base Case: When <code>index &gt;= n</code>, return 0 (end of array).</li>
  <li>Recursive Case: Return current element + recursive call for next index.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 4
Enter elements:
10 20 30 40
Sum of array elements = 100
</pre>


<h3>🔼🔽 C Program: Find Maximum and Minimum Using Recursion</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to find maximum and minimum element using recursion</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> findMax(<span style="color: blue;">int</span> arr\[], <span style="color: blue;">int</span> index, <span style="color: blue;">int</span> n, <span style="color: blue;">int</span> max) { <span style="color: blue;">if</span> (index >= n) <span style="color: blue;">return</span> max;

 
<span style="color: blue;">if</span> (arr[index] &gt; max)
    max = arr[index];

<span style="color: blue;">return</span> findMax(arr, index + 1, n, max);
 

}

<span style="color: blue;">int</span> findMin(<span style="color: blue;">int</span> arr\[], <span style="color: blue;">int</span> index, <span style="color: blue;">int</span> n, <span style="color: blue;">int</span> min) { <span style="color: blue;">if</span> (index >= n) <span style="color: blue;">return</span> min;

 
<span style="color: blue;">if</span> (arr[index] &lt; min)
    min = arr[index];

<span style="color: blue;">return</span> findMin(arr, index + 1, n, min);
 

}

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> arr\[100], n;

 
printf(<span style="color: brown;">"Enter number of elements: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Enter array elements:\n"</span>);
<span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; n; i++)
    scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

<span style="color: blue;">int</span> max = findMax(arr, 0, n, arr[0]);
<span style="color: blue;">int</span> min = findMin(arr, 0, n, arr[0]);

printf(<span style="color: brown;">"Maximum = %d\n"</span>, max);
printf(<span style="color: brown;">"Minimum = %d\n"</span>, min);

<span style="color: blue;">return</span> 0;
 

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li><code>findMax()</code> and <code>findMin()</code> are recursive functions that compare current element with max/min so far.</li>
  <li><strong>Base Case:</strong> When index reaches array length, return max or min.</li>
  <li><strong>Recursive Case:</strong> Update max/min if needed, and continue to next index.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 5
Enter array elements:
12 43 9 56 27
Maximum = 56
Minimum = 9
</pre>


<h3>📥📤 C Program: Input and Output of Array Elements</h3>

<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to accept and display array elements</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() {
    <span style="color: blue;">int</span> arr[5];

    <span style="color: green;">// Input</span>
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 5; i++) {
        printf(<span style="color: brown;">"Enter element %d: "</span>, i + 1);
        scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);
    }

    <span style="color: green;">// Output</span>
    printf(<span style="color: brown;">"Array Elements:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 5; i++) {
        printf(<span style="color: brown;">"%d "</span>, arr[i]);
    }

    <span style="color: blue;">return</span> 0;
}
</pre>

<h3>🧠 Program Explanation</h3>
<ul>
  <li>We define an array of size 5 to store 5 integers.</li>
  <li>Using a <code>for</code> loop, we take user input and store it in the array.</li>
  <li>Another <code>for</code> loop is used to display the array elements one by one.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter element 1: 5
Enter element 2: 9
Enter element 3: 2
Enter element 4: 7
Enter element 5: 1
Array Elements:
5 9 2 7 1
</pre>


<h3>➕ C Program: Sum of Array Elements</h3>

<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to find sum of array elements</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() {
    <span style="color: blue;">int</span> arr[5], sum = 0;

    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 5; i++) {
        printf(<span style="color: brown;">"Enter element %d: "</span>, i + 1);
        scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);
        sum += arr[i];
    }

    printf(<span style="color: brown;">"Sum = %d\n"</span>, sum);
    <span style="color: blue;">return</span> 0;
}
</pre>

<h3>🧠 Program Explanation</h3>
<ul>
  <li>Declare an integer array of size 5.</li>
  <li>Use a <code>for</code> loop to accept 5 elements from the user.</li>
  <li>Accumulate the sum of elements during input using <code>sum += arr[i]</code>.</li>
  <li>Display the total sum using <code>printf</code>.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter element 1: 10
Enter element 2: 20
Enter element 3: 15
Enter element 4: 5
Enter element 5: 25
Sum = 75
</pre>


<h3>➖ C Program: Print Negative Elements in an Array</h3>

<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print negative elements in an array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() {
    <span style="color: blue;">int</span> arr[5];

    printf(<span style="color: brown;">"Enter 5 elements:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 5; i++)
        scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

    printf(<span style="color: brown;">"Negative elements:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 5; i++) {
        <span style="color: blue;">if</span> (arr[i] &lt; 0)
            printf(<span style="color: brown;">"%d "</span>, arr[i]);
    }

    <span style="color: blue;">return</span> 0;
}
</pre>

<h3>🧠 Program Explanation</h3>
<ul>
  <li>Accept 5 integer elements into an array using a loop.</li>
  <li>Loop through the array again to check each element.</li>
  <li>If an element is less than 0, print it as a negative number.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter 5 elements:
12 -5 8 -2 0
Negative elements:
-5 -2
</pre>


<h3>🔁 C Program: Reverse an Array</h3>

<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print an array in reverse order</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() {
    <span style="color: blue;">int</span> arr[5];

    printf(<span style="color: brown;">"Enter 5 elements:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 5; i++)
        scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

    printf(<span style="color: brown;">"Array in reverse:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 4; i &gt;= 0; i--)
        printf(<span style="color: brown;">"%d "</span>, arr[i]);

    <span style="color: blue;">return</span> 0;
}
</pre>

<h3>🧠 Program Explanation</h3>
<ul>
  <li>Reads 5 integers from the user into an array.</li>
  <li>Loops from index 4 to 0 to print elements in reverse order.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter 5 elements:
10 20 30 40 50
Array in reverse:
50 40 30 20 10
</pre>


<h3>🔢 C Program: Count Even and Odd Elements</h3>

<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to count even and odd numbers in an array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() {
    <span style="color: blue;">int</span> arr[5], even = 0, odd = 0;

    printf(<span style="color: brown;">"Enter 5 elements:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 5; i++) {
        scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);
        <span style="color: blue;">if</span> (arr[i] % 2 == 0)
            even++;
        <span style="color: blue;">else</span>
            odd++;
    }

    printf(<span style="color: brown;">"Even: %d, Odd: %d\n"</span>, even, odd);
    <span style="color: blue;">return</span> 0;
}
</pre>

<h3>🧠 Program Explanation</h3>
<ul>
  <li>Accepts 5 elements into an array.</li>
  <li>Counts how many are even and how many are odd using modulus operator.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter 5 elements:
3 4 7 2 8
Even: 3, Odd: 2
</pre>


<h3>🔢 C Program: Sort Array in Ascending Order</h3>

<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow-x: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to sort array using Bubble Sort</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() {
    <span style="color: blue;">int</span> arr[5], temp;

    printf(<span style="color: brown;">"Enter 5 elements:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 5; i++)
        scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

    <span style="color: green;">// Bubble sort logic</span>
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 4; i++) {
        <span style="color: blue;">for</span> (<span style="color: blue;">int</span> j = 0; j &lt; 4 - i; j++) {
            <span style="color: blue;">if</span> (arr[j] &gt; arr[j + 1]) {
                temp = arr[j];
                arr[j] = arr[j + 1];
                arr[j + 1] = temp;
            }
        }
    }

    printf(<span style="color: brown;">"Sorted array:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 5; i++)
        printf(<span style="color: brown;">"%d "</span>, arr[i]);

    <span style="color: blue;">return</span> 0;
}
</pre>

<h3>🧠 Program Explanation</h3>
<ul>
  <li>Accepts 5 integers into an array.</li>
  <li>Implements the <strong>Bubble Sort</strong> algorithm to sort the array in ascending order.</li>
  <li>Compares and swaps adjacent elements if they are out of order.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter 5 elements:
45 12 89 3 5
Sorted array:
3 5 12 45 89
</pre>


<h3>🔁 C Program: Count Duplicate Elements in an Array</h3>

<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow-x: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to count duplicate elements in an array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() {
    <span style="color: blue;">int</span> arr[10], count = 0;

    printf(<span style="color: brown;">"Enter 10 elements:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 10; i++)
        scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 10; i++) {
        <span style="color: blue;">for</span> (<span style="color: blue;">int</span> j = i + 1; j &lt; 10; j++) {
            <span style="color: blue;">if</span> (arr[i] == arr[j]) {
                count++;
                <span style="color: blue;">break</span>; <span style="color: green;">// Avoid multiple counts for same element</span>
            }
        }
    }

    printf(<span style="color: brown;">"Duplicate elements count = %d\n"</span>, count);
    <span style="color: blue;">return</span> 0;
}
</pre>

<h3>🧠 Program Explanation</h3>
<ul>
  <li>Takes 10 integers as input into an array.</li>
  <li>Uses nested loops to compare each element with the ones that follow.</li>
  <li>Increments the <code>count</code> when a duplicate is found and breaks inner loop to prevent double-counting.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter 10 elements:
2 5 7 2 9 5 1 4 7 3
Duplicate elements count = 3
</pre>


<h3>📥 C Program: Insert Element at a Given Position</h3>

<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow-x: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Insert element at a specified position in array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() {
    <span style="color: blue;">int</span> arr[100], n, pos, val;

    printf(<span style="color: brown;">"Enter number of elements: "</span>);
    scanf(<span style="color: brown;">"%d"</span>, &amp;n);

    printf(<span style="color: brown;">"Enter elements:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; n; i++)
        scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

    printf(<span style="color: brown;">"Enter position and value to insert: "</span>);
    scanf(<span style="color: brown;">"%d %d"</span>, &amp;pos, &amp;val);

    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = n; i &gt;= pos; i--)
        arr[i] = arr[i - 1];

    arr[pos - 1] = val;
    n++;

    printf(<span style="color: brown;">"Array after insertion:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; n; i++)
        printf(<span style="color: brown;">"%d "</span>, arr[i]);

    <span style="color: blue;">return</span> 0;
}
</pre>

<h3>🧠 Program Explanation</h3>
<ul>
  <li>Inputs <code>n</code> elements into the array.</li>
  <li>Reads the position and value to insert.</li>
  <li>Shifts elements rightward from the given position.</li>
  <li>Inserts the new value at the correct index.</li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of elements: 5
Enter elements:
10 20 30 40 50
Enter position and value to insert: 3 99
Array after insertion:
10 20 99 30 40 50
</pre>


<h3>🔍 C Program: Search Element in an Array</h3>

<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow-x: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Linear search in array</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() {
    <span style="color: blue;">int</span> arr[10], key, found = 0;

    printf(<span style="color: brown;">"Enter 10 elements:\n"</span>);
    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 10; i++)
        scanf(<span style="color: brown;">"%d"</span>, &amp;arr[i]);

    printf(<span style="color: brown;">"Enter value to search: "</span>);
    scanf(<span style="color: brown;">"%d"</span>, &amp;key);

    <span style="color: blue;">for</span> (<span style="color: blue;">int</span> i = 0; i &lt; 10; i++) {
        <span style="color: blue;">if</span> (arr[i] == key) {
            found = 1;
            printf(<span style="color: brown;">"Found at position %d\n"</span>, i + 1);
            <span style="color: blue;">break</span>;
        }
    }

    <span style="color: blue;">if</span> (!found)
        printf(<span style="color: brown;">"Not found.\n"</span>);

    <span style="color: blue;">return</span> 0;
}
</pre>

<h3>🧠 Program Explanation</h3>
<ul>
  <li>User inputs 10 elements into the array.</li>
  <li>Searches for a specific value using linear search.</li>
  <li>If found, prints the position (1-based index).</li>
  <li>If not found, prints <code>Not found.</code></li>
</ul>

<h3>📤 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter 10 elements:
3 7 9 2 6 1 5 8 4 0
Enter value to search: 6
Found at position 5
</pre>



