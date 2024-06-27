# Counting - Permutations and Combinations

Permutations and combinations are fundamental concepts in combinatorics, a branch of mathematics dealing with counting, arrangement, and combination of objects. Here’s a detailed explanation of both concepts:

### Permutations

**Definition**: A permutation is an arrangement of all or part of a set of objects, with regard to the order of the arrangement.

**Formula**: The number of permutations of $n$ objects taken $r$ at a time is given by:
$$P(n, r) = \frac{n!}{(n - r)!}$$

**Explanation**:
- **n! (n factorial)**: The product of all positive integers up to $n$.
- **(n - r)!**: The product of all positive integers up to $n - r$.
- The formula counts the number of ways to choose $r$ objects from $n$ and arrange them in order.

**Example**: How many ways can you arrange 3 books out of a set of 5?
$$P(5, 3) = \frac{5!}{(5 - 3)!} = \frac{5!}{2!} = \frac{5 \times 4 \times 3 \times 2 \times 1}{2 \times 1} = 60$$

### Combinations

**Definition**: A combination is a selection of all or part of a set of objects, without regard to the order of the selection.

**Formula**: The number of combinations of $n$ objects taken $r$ at a time is given by:
$$C(n, r) = \frac{n!}{r!(n - r)!}$$

**Explanation**:
- **n!**: The product of all positive integers up to $n$.
- **r!**: The product of all positive integers up to $r$.
- **(n - r)!**: The product of all positive integers up to $n - r$.
- The formula counts the number of ways to choose $r$ objects from $n$ without considering the order.

**Example**: How many ways can you choose 3 books out of a set of 5?
$$C(5, 3) = \frac{5!}{3!(5 - 3)!} = \frac{5!}{3!2!} = \frac{5 \times 4 \times 3 \times 2 \times 1}{3 \times 2 \times 1 \times 2 \times 1} = 10$$

### Key Differences

1. **Order**:
   - Permutations consider the order of objects (e.g., ABC is different from BAC).
   - Combinations do not consider the order (e.g., ABC is the same as BAC).

2. **Formulas**:
   - Permutations: $ P(n, r) = \frac{n!}{(n - r)!} $
   - Combinations: $ C(n, r) = \frac{n!}{r!(n - r)!} $

3. **Applications**:
   - Permutations are used when the order matters, such as in arranging books on a shelf or seating arrangements.
   - Combinations are used when the order does not matter, such as in selecting a committee or choosing lottery numbers.

### Visual Examples

1. **Permutations**:
   - Objects: A, B, C
   - Permutations of 2 out of 3: AB, BA, AC, CA, BC, CB (6 ways)

2. **Combinations**:
   - Objects: A, B, C
   - Combinations of 2 out of 3: AB, AC, BC (3 ways)

### Mnemonic for Remembering

- **Permutations**: Think **P** for **Position** matters.
- **Combinations**: Think **C** for **Choice** only, position doesn't matter.

### Practice Problems

1. **Permutations**: How many ways can 4 students be seated in a row from a group of 10?
   - $ P(10, 4) = \frac{10!}{(10 - 4)!} = \frac{10!}{6!} = 5040 $

2. **Combinations**: How many ways can a committee of 4 be chosen from 10 students?
   - $ C(10, 4) = \frac{10!}{4!6!} = 210 $

By understanding the definitions, formulas, and differences between permutations and combinations, you can apply these concepts to a wide range of problems in mathematics and real-life scenarios.