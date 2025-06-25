<h3>🔢 C Program: Print Day of Week Using Switch Case</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print day of the week using switch</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> day;

```
printf(<span style="color: brown;">"Enter day number (1-7): "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;day);

<span style="color: blue;">switch</span> (day) {
    <span style="color: blue;">case</span> 1: printf(<span style="color: brown;">"Sunday\n"</span>); <span style="color: blue;">break</span>;
    <span style="color: blue;">case</span> 2: printf(<span style="color: brown;">"Monday\n"</span>); <span style="color: blue;">break</span>;
    <span style="color: blue;">case</span> 3: printf(<span style="color: brown;">"Tuesday\n"</span>); <span style="color: blue;">break</span>;
    <span style="color: blue;">case</span> 4: printf(<span style="color: brown;">"Wednesday\n"</span>); <span style="color: blue;">break</span>;
    <span style="color: blue;">case</span> 5: printf(<span style="color: brown;">"Thursday\n"</span>); <span style="color: blue;">break</span>;
    <span style="color: blue;">case</span> 6: printf(<span style="color: brown;">"Friday\n"</span>); <span style="color: blue;">break</span>;
    <span style="color: blue;">case</span> 7: printf(<span style="color: brown;">"Saturday\n"</span>); <span style="color: blue;">break</span>;
    <span style="color: blue;">default</span>: printf(<span style="color: brown;">"Invalid day number!\n"</span>);
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li>Takes an integer input from the user between 1 and 7.</li>
  <li>Uses a <code>switch</code> statement to match the day number.</li>
  <li>Each <code>case</code> corresponds to a weekday.</li>
  <li><code>default</code> handles invalid input outside 1-7.</li>
</ul>
<h3>🧪 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter day number (1-7): 3
Tuesday
</pre>

---

<h3>🔢 C Program: Print Total Days in a Month Using Switch Case</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print total days in a month using switch</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> month;

```
printf(<span style="color: brown;">"Enter month number (1-12): "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;month);

<span style="color: blue;">switch</span> (month) {
    <span style="color: blue;">case</span> 1: <span style="color: blue;">case</span> 3: <span style="color: blue;">case</span> 5:
    <span style="color: blue;">case</span> 7: <span style="color: blue;">case</span> 8: <span style="color: blue;">case</span> 10:
    <span style="color: blue;">case</span> 12:
        printf(<span style="color: brown;">"31 days\n"</span>);
        <span style="color: blue;">break</span>;
    <span style="color: blue;">case</span> 4: <span style="color: blue;">case</span> 6:
    <span style="color: blue;">case</span> 9: <span style="color: blue;">case</span> 11:
        printf(<span style="color: brown;">"30 days\n"</span>);
        <span style="color: blue;">break</span>;
    <span style="color: blue;">case</span> 2:
        printf(<span style="color: brown;">"28 or 29 days (leap year dependent)\n"</span>);
        <span style="color: blue;">break</span>;
    <span style="color: blue;">default</span>:
        printf(<span style="color: brown;">"Invalid month number!\n"</span>);
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<h3>🧠 Program Logic &amp; Explanation</h3>
<ul>
  <li>User inputs a number between 1 and 12 representing the month.</li>
  <li>Switch cases group months with the same number of days.</li>
  <li>February is handled separately due to leap year condition.</li>
  <li><code>default</code> handles invalid month numbers.</li>
</ul>
<h3>🧪 Sample Output</h3>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter month number (1-12): 2
28 or 29 days (leap year dependent)
</pre>

---
