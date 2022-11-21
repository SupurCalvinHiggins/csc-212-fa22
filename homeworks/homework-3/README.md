Assignment 3 due Week 6, Friday by 11:59p

# Work Expectations
Your work must unambiguously demonstrate mastery of the problem. It should be clearly and evidently your own. Instructor(s) and TAs should be unable to even question if your answers were copied. That is, your work should be beyond suspicion. It should be clear, correct and otherwise unimpeachable.

### Question 1
For parts (a) through (e), complete and correct formal justifications with summations must be provided. For example, the exact formula for $T(n)$ of

```c++
for (int i = 7; i <= 3*n*n; i++) {
  // op
  // op
}
```

should be calculated as follows. First, we translate the code into a formula for $T(n)$ in terms of summation(s): $T(n)=\sum\limits_{i=7}^{3n^2}(1 + 1)$. Multiple loops will require using multiple summations. Then, we solve for a closed form: $T(n)=\sum\limits_{i=7}^{3n^2}(1 + 1)=\sum\limits_{i=7}^{3n^2}(2)=2\sum\limits_{i=7}^{3n^2}(1)=2\sum\limits_{i=1}^{3n^2-6}(1)=2(3n^2-6)$. Do NOT include $T(n)$ on the answer line. In the prior example, acceptable answers include $2(3n^2-6)$, $6n^2-12$ or any equivalent closed form. HINT: test your final answer with different values of $n$. Be sure it works.

For parts (f) through (i), summations are NOT required. However, the code must be clearly traced OR an argument/proof must be provided.

### Question 2
Formal justification with summations must be provided.

### Question 3
None.

### Question 4
Must write $T$ for true and $F$ for false.

### Question 5
Answer must NOT include $\mathcal{O}$, $\Theta$ or $\Omega$ notation. For example, if the answer is $\Theta(n)$ write only $n$ in the answer box. For future reference, note that $\mathcal{O}$ is NOT the same thing as best case, $\Theta$ is NOT the same thing as average case and $\Omega$ is NOT the same thing as worst case.

### Question 6
Code must be clearly traced. Output must be written ACROSS the provided rows and NOT down the columns. 

### Question 7
Code must be clearly traced. Output must be written ACROSS the provided rows and NOT down the columns. 

### Question 8
None.

### Question 9
None.

### Question 10
None.
