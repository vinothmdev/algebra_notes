## Mathematical Sequences: High School Level

### 1. Introduction to Sequences
- **Definition**: A sequence is an ordered list of numbers.
- **Terms**: Each number in a sequence is called a term.
- **Notation**: Typically written as $a_1, a_2, a_3, \ldots$ or $\{a_n\}$.

### 2. Types of Sequences
- **Arithmetic Sequences**: The difference between consecutive terms is constant.
  - **General Form**: $a_n = a_1 + (n-1)d$
  - **Example**: 2, 5, 8, 11, 14, ... (common difference $d = 3$)

- **Geometric Sequences**: The ratio between consecutive terms is constant.
  - **General Form**: $a_n = a_1 \cdot r^{n-1}$
  - **Example**: 3, 6, 12, 24, 48, ... (common ratio $r = 2$)

### 3. Finding Terms in Sequences
- **Arithmetic Sequence**:
  - **Nth Term**: $a_n = a_1 + (n-1)d$
  - **Example**: Find the 10th term of the sequence 4, 7, 10, 13, ...
    - Solution: $a_{10} = 4 + (10-1) \cdot 3 = 4 + 27 = 31$

- **Geometric Sequence**:
  - **Nth Term**: $a_n = a_1 \cdot r^{n-1}$
  - **Example**: Find the 8th term of the sequence 5, 15, 45, 135, ...
    - Solution: $a_8 = 5 \cdot 3^{7} = 5 \cdot 2187 = 10935$

### 4. Summing Sequences
- **Arithmetic Series**: The sum of the first $n$ terms.
  - **Formula**: $S_n = \frac{n}{2} (a_1 + a_n)$
  - **Example**: Sum the first 10 terms of the sequence 2, 5, 8, 11, ...
    - Solution: $a_{10} = 2 + (10-1) \cdot 3 = 2 + 27 = 29$
    - $S_{10} = \frac{10}{2} (2 + 29) = 5 \cdot 31 = 155$

- **Geometric Series**: The sum of the first $n$ terms.
  - **Formula**: $S_n = a_1 \frac{1 - r^n}{1 - r}$ (for $r \neq 1$)
  - **Example**: Sum the first 5 terms of the sequence 3, 9, 27, 81, ...
    - Solution: $S_5 = 3 \frac{1 - 3^5}{1 - 3} = 3 \frac{1 - 243}{-2} = 3 \cdot \frac{-242}{-2} = 3 \cdot 121 = 363$

### 5. Special Sequences
- **Fibonacci Sequence**: Each term is the sum of the two preceding ones.
  - **General Form**: $F_n = F_{n-1} + F_{n-2}$ with $F_1 = 1$ and $F_2 = 1$
  - **Example**: 1, 1, 2, 3, 5, 8, 13, ...

- **Harmonic Sequence**: The reciprocal of the natural numbers.
  - **General Form**: $a_n = \frac{1}{n}$
  - **Example**: 1, $\frac{1}{2}$, $\frac{1}{3}$, $\frac{1}{4}$, ...

### 6. Practice Problems
1. Find the 15th term of the arithmetic sequence 7, 11, 15, 19, ...
2. Find the 6th term of the geometric sequence 2, 6, 18, 54, ...
3. Sum the first 8 terms of the arithmetic sequence 3, 8, 13, 18, ...
4. Sum the first 4 terms of the geometric sequence 1, 5, 25, 125, ...
5. Find the 10th term of the Fibonacci sequence.

### 7. Additional Concepts
- **Recursive Sequences**: Defined using previous terms.
  - **Example**: $a_n = a_{n-1} + 2$ with $a_1 = 1$

- **Convergence and Divergence**: Some sequences approach a specific value (converge), others do not (diverge).

### 8. Real-Life Applications
- **Finance**: Interest calculations (geometric sequences).
- **Physics**: Wave patterns and sound frequencies.
- **Biology**: Population growth models.
