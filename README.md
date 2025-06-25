
  <h1>Recursion Programs in C</h1>

  <div class="section">
    <h2>🔸 1. Print Natural Numbers from 1 to n</h2>
    <pre><code>#include &lt;stdio.h&gt;

void printNatural(int n) {
    if (n == 0)
        return;
    printNatural(n - 1);  // recursive call
    printf("%d ", n);     // printing in increasing order
}

int main() {
    int n;
    printf("Enter value of n: ");
    scanf("%d", &n);
    printNatural(n);
    return 0;
}</code></pre>
  </div>

  <div class="section">
    <h2>🔸 2. Sum of Natural Numbers in Range (1 to n)</h2>
    <pre><code>#include &lt;stdio.h&gt;

int sumNatural(int n) {
    if (n == 0)
        return 0;
    else
        return n + sumNatural(n - 1);
}

int main() {
    int n;
    printf("Enter number: ");
    scanf("%d", &n);
    printf("Sum = %d\n", sumNatural(n));
    return 0;
}</code></pre>
  </div>

  <div class="section">
    <h2>🔸 3. Print All Even Numbers in Given Range</h2>
    <pre><code>#include &lt;stdio.h&gt;

void printEven(int start, int end) {
    if (start > end)
        return;
    if (start % 2 == 0)
        printf("%d ", start);
    printEven(start + 1, end);
}

int main() {
    int a, b;
    printf("Enter range: ");
    scanf("%d %d", &a, &b);
    printEven(a, b);
    return 0;
}</code></pre>
  </div>

  <div class="section">
    <h2>🔸 4. Sum of Even and Odd Numbers in a Range</h2>
    <pre><code>#include &lt;stdio.h&gt;

int sumEven(int start, int end) {
    if (start > end)
        return 0;
    if (start % 2 == 0)
        return start + sumEven(start + 1, end);
    else
        return sumEven(start + 1, end);
}

int sumOdd(int start, int end) {
    if (start > end)
        return 0;
    if (start % 2 != 0)
        return start + sumOdd(start + 1, end);
    else
        return sumOdd(start + 1, end);
}

int main() {
    int start, end;
    printf("Enter start and end: ");
    scanf("%d %d", &start, &end);
    printf("Sum of even numbers = %d\n", sumEven(start, end));
    printf("Sum of odd numbers = %d\n", sumOdd(start, end));
    return 0;
}</code></pre>
  </div>

  <div class="section">
    <h2>🔸 5. Factorial Using Recursion</h2>
    <pre><code>#include &lt;stdio.h&gt;

long long factorial(int n) {
    if (n == 0 || n == 1)
        return 1;
    else
        return n * factorial(n - 1);
}

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    printf("Factorial of %d is %lld\n", num, factorial(num));
    return 0;
}</code></pre>
  </div>

  <div class="section">
    <h2>🔸 6. Fibonacci Series Using Recursion</h2>
    <pre><code>#include &lt;stdio.h&gt;

int fibonacci(int n) {
    if (n == 0)
        return 0;
    else if (n == 1)
        return 1;
    else
        return fibonacci(n - 1) + fibonacci(n - 2);
}

int main() {
    int terms;
    printf("Enter number of terms: ");
    scanf("%d", &terms);
    for (int i = 0; i &lt; terms; i++) {
        printf("%d ", fibonacci(i));
    }
    return 0;
}</code></pre>
  </div>

</body>
</html>
