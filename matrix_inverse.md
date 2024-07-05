Teaching about matrix inverses involves explaining the concept, conditions for the existence of an inverse, and providing examples to illustrate the process of finding the inverse of a matrix. Here’s a structured approach to teach this topic:

### 1. Introduction to Matrix Inverse

#### Definition
The inverse of a matrix $A$ is another matrix $A^{-1}$ such that when $A$ is multiplied by $A^{-1}$, the result is the identity matrix $I$:
$$A \cdot A^{-1} = A^{-1} \cdot A = I$$

#### Conditions for Invertibility
A matrix $A$ has an inverse if and only if:
- $A$ is a square matrix (same number of rows and columns).
- The determinant of $A$ is not zero ($\det(A) \neq 0$).

### 2. Finding the Inverse of a 2x2 Matrix

For a 2x2 matrix:
$$A = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$$
The inverse $A^{-1}$ is given by:
$$A^{-1} = \frac{1}{ad - bc} \begin{pmatrix} d & -b \\ -c & a \end{pmatrix}$$
provided that $ad - bc \neq 0$.

#### Example 1
Find the inverse of the matrix:
$$A = \begin{pmatrix} 2 & 3 \\ 1 & 4 \end{pmatrix}$$

**Solution:**
1. Calculate the determinant:
$$\det(A) = (2 \cdot 4) - (3 \cdot 1) = 8 - 3 = 5$$

2. Use the formula for the inverse:
$$A^{-1} = \frac{1}{5} \begin{pmatrix} 4 & -3 \\ -1 & 2 \end{pmatrix} = \begin{pmatrix} \frac{4}{5} & -\frac{3}{5} \\ -\frac{1}{5} & \frac{2}{5} \end{pmatrix}$$

### 3. Finding the Inverse of a 3x3 Matrix

For a 3x3 matrix, finding the inverse is more complex and usually involves:
1. **Calculating the determinant** of the 3x3 matrix.
2. **Finding the matrix of minors**.
3. **Forming the matrix of cofactors**.
4. **Transposing** the matrix of cofactors to get the adjugate matrix.
5. **Dividing** the adjugate matrix by the determinant.

#### Example 2
Find the inverse of the matrix:
$$A = \begin{pmatrix} 1 & 2 & 3 \\ 0 & 1 & 4 \\ 5 & 6 & 0 \end{pmatrix}$$

**Solution:**
1. **Calculate the determinant**:
$$\det(A) = 1 \cdot (1 \cdot 0 - 4 \cdot 6) - 2 \cdot (0 \cdot 0 - 4 \cdot 5) + 3 \cdot (0 \cdot 6 - 1 \cdot 5)$$
$$\det(A) = 1 \cdot (0 - 24) - 2 \cdot (0 - 20) + 3 \cdot (0 - 5)$$
$$\det(A) = -24 + 40 - 15 = 1$$

2. **Find the matrix of minors**:
$$\text{Minors} = \begin{pmatrix}
\begin{vmatrix} 1 & 4 \\ 6 & 0 \end{vmatrix} & \begin{vmatrix} 0 & 4 \\ 5 & 0 \end{vmatrix} & \begin{vmatrix} 0 & 1 \\ 5 & 6 \end{vmatrix} \\
\begin{vmatrix} 2 & 3 \\ 6 & 0 \end{vmatrix} & \begin{vmatrix} 1 & 3 \\ 5 & 0 \end{vmatrix} & \begin{vmatrix} 1 & 2 \\ 5 & 6 \end{vmatrix} \\
\begin{vmatrix} 2 & 3 \\ 1 & 4 \end{vmatrix} & \begin{vmatrix} 1 & 3 \\ 0 & 4 \end{vmatrix} & \begin{vmatrix} 1 & 2 \\ 0 & 1 \end{vmatrix}
\end{pmatrix}$$
$$\text{Minors} = \begin{pmatrix} -24 & -20 & -5 \\ 0 & -15 & -4 \\ 5 & -3 & 1 \end{pmatrix}$$

3. **Form the matrix of cofactors** by applying a checkerboard pattern of signs to the minors matrix:
$$\text{Cofactors} = \begin{pmatrix} -24 & 20 & -5 \\ 0 & -15 & 4 \\ 5 & 3 & 1 \end{pmatrix}$$

4. **Transpose the matrix of cofactors** to get the adjugate matrix:
$$\text{Adjugate} = \begin{pmatrix} -24 & 0 & 5 \\ 20 & -15 & 3 \\ -5 & 4 & 1 \end{pmatrix}$$

5. **Divide the adjugate matrix by the determinant**:
$$A^{-1} = \frac{1}{1} \begin{pmatrix} -24 & 0 & 5 \\ 20 & -15 & 3 \\ -5 & 4 & 1 \end{pmatrix}$$
$$A^{-1} = \begin{pmatrix} -24 & 0 & 5 \\ 20 & -15 & 3 \\ -5 & 4 & 1 \end{pmatrix}$$

### 4. Verifying the Inverse

To verify that a matrix $B$ is the inverse of $A$, multiply $A$ and $B$ and check if the result is the identity matrix:
$$A \cdot B = I$$

For the 2x2 example:
$$A = \begin{pmatrix} 2 & 3 \\ 1 & 4 \end{pmatrix}$$
$$A^{-1} = \begin{pmatrix} \frac{4}{5} & -\frac{3}{5} \\ -\frac{1}{5} & \frac{2}{5} \end{pmatrix}$$

$$A \cdot A^{-1} = \begin{pmatrix} 2 & 3 \\ 1 & 4 \end{pmatrix} \cdot \begin{pmatrix} \frac{4}{5} & -\frac{3}{5} \\ -\frac{1}{5} & \frac{2}{5} \end{pmatrix} = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix} = I$$

By following these steps and examples, you can effectively teach about the inverse of a matrix.
