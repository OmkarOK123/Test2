<h3>🔢 C Program: Print Natural Numbers in Reverse (n to 1) using while loop</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print natural numbers from n to 1 using while loop</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> n;

```
printf(<span style="color: brown;">"Enter a number: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

<span style="color: blue;">while</span> (n &gt;= 1) {
    printf(<span style="color: brown;">"%d "</span>, n);
    n--;
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li><strong>Step 1:</strong> Take an integer input <code>n</code> from the user.</li>
  <li><strong>Step 2:</strong> Use a <code>while</code> loop to print numbers starting from <code>n</code> down to 1.</li>
  <li><strong>Step 3:</strong> Decrement <code>n</code> in each iteration using <code>n--</code>.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter a number: 5
5 4 3 2 1</pre>

<h3>🔡 C Program: Print All Letters from a to z using while loop</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print all lowercase letters from a to z using while loop</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">char</span> ch = <span style="color: brown;">'a'</span>;

```
<span style="color: blue;">while</span> (ch &lt;= <span style="color: brown;">'z'</span>) {
    printf(<span style="color: brown;">"%c "</span>, ch);
    ch++;
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li><strong>Step 1:</strong> Initialize character <code>ch</code> to <code>'a'</code>.</li>
  <li><strong>Step 2:</strong> Use a <code>while</code> loop to print <code>ch</code> until it reaches <code>'z'</code>.</li>
  <li><strong>Step 3:</strong> Increment <code>ch</code> in each iteration using <code>ch++</code>.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
a b c d e f g h i j k l m n o p q r s t u v w x y z</pre>


<h3>🔢 C Program: Print All Even Numbers from 1 to 100</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print all even numbers from 1 to 100 using while loop</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> i = 1;

```
<span style="color: blue;">while</span> (i &lt;= 100) {
    <span style="color: blue;">if</span> (i % 2 == 0)
        printf(<span style="color: brown;">"%d "</span>, i);
    i++;
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li><strong>Step 1:</strong> Initialize variable <code>i</code> to 1.</li>
  <li><strong>Step 2:</strong> Loop until <code>i</code> is less than or equal to 100.</li>
  <li><strong>Step 3:</strong> Inside the loop, use <code>if (i % 2 == 0)</code> to check if the number is even.</li>
  <li><strong>Step 4:</strong> Print the number if it's even, then increment <code>i</code>.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
2 4 6 8 10 12 14 16 18 20 ... 100</pre>


<h3>🔢 C Program: Print Multiplication Table of a Number</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print multiplication table using while loop</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> num, i = 1;

```
printf(<span style="color: brown;">"Enter a number: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;num);

<span style="color: blue;">while</span> (i &lt;= 10) {
    printf(<span style="color: brown;">"%d x %d = %d\n"</span>, num, i, num * i);
    i++;
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li><strong>Step 1:</strong> Take a number as input from the user.</li>
  <li><strong>Step 2:</strong> Initialize loop counter <code>i = 1</code>.</li>
  <li><strong>Step 3:</strong> Use a <code>while</code> loop to print the multiplication from 1 to 10.</li>
  <li><strong>Step 4:</strong> In each iteration, print <code>num × i</code> and increment <code>i</code>.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter a number: 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
...
5 x 10 = 50</pre>


<h3>🔢 C Program: Check Prime Number</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to check if a number is prime</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> num, i, isPrime = 1;

```
printf(<span style="color: brown;">"Enter a number: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;num);

<span style="color: blue;">if</span> (num &lt;= 1) {
    isPrime = 0;
} <span style="color: blue;">else</span> {
    <span style="color: blue;">for</span> (i = 2; i &lt;= num / 2; i++) {
        <span style="color: blue;">if</span> (num % i == 0) {
            isPrime = 0;
            <span style="color: blue;">break</span>;
        }
    }
}

<span style="color: blue;">if</span> (isPrime)
    printf(<span style="color: brown;">"%d is a Prime Number\n"</span>, num);
<span style="color: blue;">else</span>
    printf(<span style="color: brown;">"%d is Not a Prime Number\n"</span>, num);

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li><code>isPrime</code> is initialized to 1 (assume number is prime).</li>
  <li>For numbers ≤ 1, mark as not prime.</li>
  <li>Loop from 2 to <code>num/2</code>. If divisible by any number, it’s not prime.</li>
  <li>Use a flag (<code>isPrime</code>) to track and print the result accordingly.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter a number: 13
13 is a Prime Number</pre>



<h3>🔢 C Program: Count Number of Digits</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to count number of digits in a number</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> num, count = 0;

```
printf(<span style="color: brown;">"Enter a number: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;num);

<span style="color: blue;">while</span> (num != 0) {
    num /= 10;
    count++;
}

printf(<span style="color: brown;">"Total digits: %d\n"</span>, count);

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>The loop divides the number by 10 repeatedly.</li>
  <li>Each division removes one digit from the number.</li>
  <li><code>count</code> is incremented on each iteration until number becomes 0.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter a number: 12345
Total digits: 5</pre>


<h3>🔢 C Program: Print Factorial of a Number</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to find factorial of a number using while loop</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> n, i = 1; <span style="color: blue;">long long</span> fact = 1;

```
printf(<span style="color: brown;">"Enter a number: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

<span style="color: blue;">while</span> (i &lt;= n) {
    fact *= i;
    i++;
}

printf(<span style="color: brown;">"Factorial = %lld\n"</span>, fact);

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>The program initializes <code>fact</code> to 1 and iterates from 1 to <code>n</code>.</li>
  <li>Each number is multiplied to <code>fact</code> to compute the factorial.</li>
  <li>Finally, the result is printed using <code>%lld</code> for long long int.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter a number: 5
Factorial = 120</pre>


<h3>🔢 C Program: Print ASCII Values of All Characters</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print ASCII values of all characters</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">char</span> ch = 0;

```
<span style="color: blue;">while</span> (ch &lt;= 127) {
    printf(<span style="color: brown;">"ASCII of %c = %d\n"</span>, ch, ch);
    ch++;
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>Initializes <code>ch</code> with value 0 (null character).</li>
  <li>Uses a <code>while</code> loop to iterate up to ASCII 127.</li>
  <li><code>printf</code> is used to display both the character and its ASCII code.</li>
</ul>

<p><strong>Sample Output (partial):</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
ASCII of   = 0
ASCII of ☺ = 1
...
ASCII of A = 65
ASCII of z = 122
ASCII of ~ = 126
ASCII of  = 127</pre>


<h3>🔢 C Program: Check Armstrong Number</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to check if a number is an Armstrong number</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;
<span style="color: blue;">#include</span> &lt;math.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> num, temp, remainder, digits = 0; <span style="color: blue;">int</span> result = 0;

```
printf(<span style="color: brown;">"Enter a number: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;num);

temp = num;
<span style="color: blue;">while</span> (temp != 0) {
    digits++;
    temp /= 10;
}

temp = num;
<span style="color: blue;">while</span> (temp != 0) {
    remainder = temp % 10;
    result += pow(remainder, digits);
    temp /= 10;
}

<span style="color: blue;">if</span> (result == num)
    printf(<span style="color: brown;">"%d is an Armstrong number\n"</span>, num);
<span style="color: blue;">else</span>
    printf(<span style="color: brown;">"%d is NOT an Armstrong number\n"</span>, num);

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>An Armstrong number is equal to the sum of its digits each raised to the power of number of digits.</li>
  <li>The program first counts digits in the number.</li>
  <li>Then calculates the sum of digits raised to that power using <code>pow()</code>.</li>
  <li>Finally compares the result with original number.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter a number: 153
153 is an Armstrong number</pre>


<h3>🔢 C Program: Print Fibonacci Series up to n Terms</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to print Fibonacci series up to n terms</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">int</span> n, i = 1; <span style="color: blue;">int</span> a = 0, b = 1, next;

```
printf(<span style="color: brown;">"Enter number of terms: "</span>);
scanf(<span style="color: brown;">"%d"</span>, &amp;n);

printf(<span style="color: brown;">"Fibonacci Series: "</span>);
<span style="color: blue;">while</span> (i &lt;= n) {
    printf(<span style="color: brown;">"%d "</span>, a);
    next = a + b;
    a = b;
    b = next;
    i++;
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>Fibonacci series is generated by adding the last two terms.</li>
  <li>Starts with <code>0</code> and <code>1</code>.</li>
  <li>In each iteration, <code>next = a + b</code> is computed and printed.</li>
  <li>Values are updated in a loop until <code>n</code> terms are printed.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter number of terms: 7
Fibonacci Series: 0 1 1 2 3 5 8</pre>


<h3>🔐 C Program: Accept Password and Check Using <code>break</code> (Sidd)</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Accept password until correct using break</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;
<span style="color: blue;">#include</span> &lt;string.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">char</span> password\[20];

```
<span style="color: blue;">while</span> (1) {
    printf(<span style="color: brown;">"Enter Password: "</span>);
    scanf(<span style="color: brown;">"%s"</span>, password);

    <span style="color: blue;">if</span> (strcmp(password, <span style="color: brown;">"admin123"</span>) == 0) {
        printf(<span style="color: brown;">"Password Correct!\n"</span>);
        <span style="color: blue;">break</span>;
    } <span style="color: blue;">else</span> {
        printf(<span style="color: brown;">"Wrong Password. Try again.\n"</span>);
    }
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>Uses an infinite <code>while</code> loop to repeatedly prompt for a password.</li>
  <li><code>strcmp()</code> is used to compare user input with the correct password <code>"admin123"</code>.</li>
  <li>If matched, success message is shown and <code>break</code> exits the loop.</li>
  <li>Otherwise, the loop continues with an error message.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter Password: hello
Wrong Password. Try again.
Enter Password: admin123
Password Correct!</pre>


<h3>🔤 C Program: Check Vowel or Consonant (Using <code>break</code>) (Sidd)</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
<span style="color: green;">// Program to check vowel or consonant using switch and break</span>
<span style="color: blue;">#include</span> &lt;stdio.h&gt;

<span style="color: blue;">int</span> main() { <span style="color: blue;">char</span> ch;

```
printf(<span style="color: brown;">"Enter an alphabet: "</span>);
scanf(<span style="color: brown;">" %c"</span>, &amp;ch);

<span style="color: blue;">switch</span> (ch) {
    <span style="color: blue;">case</span> 'a': <span style="color: blue;">case</span> 'e': <span style="color: blue;">case</span> 'i':
    <span style="color: blue;">case</span> 'o': <span style="color: blue;">case</span> 'u':
    <span style="color: blue;">case</span> 'A': <span style="color: blue;">case</span> 'E': <span style="color: blue;">case</span> 'I':
    <span style="color: blue;">case</span> 'O': <span style="color: blue;">case</span> 'U':
        printf(<span style="color: brown;">"Vowel\n"</span>);
        <span style="color: blue;">break</span>;
    <span style="color: blue;">default</span>:
        printf(<span style="color: brown;">"Consonant\n"</span>);
}

<span style="color: blue;">return</span> 0;
```

} </pre>

<p><strong>Explanation:</strong></p>
<ul>
  <li>User inputs an alphabet character.</li>
  <li><code>switch</code> checks if the character matches any of the vowel cases.</li>
  <li>If matched, it prints <code>Vowel</code> and exits using <code>break</code>.</li>
  <li><code>default</code> case handles consonants.</li>
</ul>

<p><strong>Sample Output:</strong></p>
<pre style="background-color: #f9f9f9; padding: 10px; border: 1px dashed #ccc; font-family: Consolas, monospace;">
Enter an alphabet: E
Vowel</pre>

<h2>🔁 Loop and Break Statements: C Programs</h2>

<h3>🔹 1. Print Natural Numbers in Reverse (while)</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; overflow: auto; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    int n;
    printf("Enter a number: ");
    scanf("%d", &n);

    while (n >= 1) {
        printf("%d ", n);
        n--;
    }
    return 0;
}
</pre>

<h3>🔹 2. Print Letters from a to z (while)</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    char ch = 'a';
    while (ch <= 'z') {
        printf("%c ", ch);
        ch++;
    }
    return 0;
}
</pre>

<h3>🔹 3. Print Even Numbers from 1 to 100 (for)</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    for (int i = 1; i <= 100; i++) {
        if (i % 2 == 0)
            printf("%d ", i);
    }
    return 0;
}
</pre>

<h3>🔹 4. Multiplication Table</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);

    for (int i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", num, i, num * i);
    }
    return 0;
}
</pre>

<h3>🔹 5. Check if a Number is Prime</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    int num, i, isPrime = 1;
    printf("Enter a number: ");
    scanf("%d", &num);

    for (i = 2; i <= num / 2; i++) {
        if (num % i == 0) {
            isPrime = 0;
            break;
        }
    }

    if (isPrime && num > 1)
        printf("Prime Number\n");
    else
        printf("Not a Prime Number\n");

    return 0;
}
</pre>

<h3>🔹 6. Count Digits in a Number</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    int num, count = 0;
    printf("Enter a number: ");
    scanf("%d", &num);

    while (num != 0) {
        num = num / 10;
        count++;
    }

    printf("Number of digits: %d\n", count);
    return 0;
}
</pre>

<h3>🔹 7. Factorial of a Number</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    int num, fact = 1;
    printf("Enter a number: ");
    scanf("%d", &num);

    for (int i = 1; i <= num; i++) {
        fact *= i;
    }

    printf("Factorial = %d\n", fact);
    return 0;
}
</pre>

<h3>🔹 8. ASCII Values of All Characters</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    for (int i = 0; i <= 255; i++) {
        printf("ASCII of %c = %d\n", i, i);
    }
    return 0;
}
</pre>

<h3>🔹 9. Fibonacci Series up to n Terms</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    int n, a = 0, b = 1, next;
    printf("Enter number of terms: ");
    scanf("%d", &n);

    for (int i = 1; i <= n; i++) {
        printf("%d ", a);
        next = a + b;
        a = b;
        b = next;
    }
    return 0;
}
</pre>

<h3>🔹 10. Armstrong Number Check</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    int num, original, rem, result = 0;
    printf("Enter a number: ");
    scanf("%d", &num);

    original = num;
    while (original != 0) {
        rem = original % 10;
        result += rem * rem * rem;
        original /= 10;
    }

    if (result == num)
        printf("Armstrong Number\n");
    else
        printf("Not Armstrong Number\n");

    return 0;
}
</pre>

<h3>🔹 11. Password Check Using break (Sidd)</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;
#include &lt;string.h&gt;

int main() {
    char password[20];
    while (1) {
        printf("Enter password: ");
        scanf("%s", password);

        if (strcmp(password, "admin123") == 0) {
            printf("Access granted\n");
            break;
        } else {
            printf("Wrong password! Try again.\n");
        }
    }
    return 0;
}
</pre>

<h3>🔹 12. Vowel/Consonant Using break</h3>
<pre style="background-color: #f4f4f4; padding: 12px; border: 1px solid #ccc; border-radius: 5px; font-family: Consolas, monospace; color: #333;">
#include &lt;stdio.h&gt;

int main() {
    char ch;
    printf("Enter a character: ");
    scanf(" %c", &ch);

    switch (ch) {
        case 'a': case 'e': case 'i': case 'o': case 'u':
        case 'A': case 'E': case 'I': case 'O': case 'U':
            printf("Vowel\n");
            break;
        default:
            printf("Consonant\n");
    }

    return 0;
}
</pre>






