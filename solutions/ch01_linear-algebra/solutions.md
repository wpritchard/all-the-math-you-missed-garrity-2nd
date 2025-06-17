# Linear Algebra: Vectors, Matrices, and Linear Transformations

Linear algebra studies vectors, vector spaces, and linear mappings between these spaces.

## Vectors

A vector in \( \mathbb{R}^n \) is an ordered tuple of real numbers:

\[
\mathbf{v} = \begin{bmatrix} v_1 \\ v_2 \\ \vdots \\ v_n \end{bmatrix}
\]

Operations include:

- **Addition**: \( \mathbf{u} + \mathbf{v} \)
- **Scalar multiplication**: \( c\mathbf{v} \)
- **Dot product**: \( \mathbf{u} \cdot \mathbf{v} = \sum_{i=1}^n u_i v_i \)
- **Norm (length)**: \( \|\mathbf{v}\| = \sqrt{v_1^2 + \cdots + v_n^2} \)

## Matrices

A matrix is a rectangular array of numbers. An \( m \times n \) matrix \( A \) represents a linear transformation from \( \mathbb{R}^n \to \mathbb{R}^m \).

\[
A = \begin{bmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{bmatrix}
\]

## Matrix-Vector Multiplication

If \( A \in \mathbb{R}^{m \times n} \) and \( \mathbf{x} \in \mathbb{R}^n \), then:

\[
A\mathbf{x} = \begin{bmatrix}
\text{row}_1 \cdot \mathbf{x} \\
\text{row}_2 \cdot \mathbf{x} \\
\vdots \\
\text{row}_m \cdot \mathbf{x}
\end{bmatrix}
\]

This gives a new vector in \( \mathbb{R}^m \).

## Linear Systems

A linear system \( A\mathbf{x} = \mathbf{b} \) can be solved using:

- Gaussian elimination
- Matrix inverses (if \( A \) is square and invertible)
- LU or QR decomposition

## Eigenvalues and Eigenvectors

If \( A \in \mathbb{R}^{n \times n} \), a non-zero vector \( \mathbf{v} \) is an **eigenvector** if:

\[
A\mathbf{v} = \lambda \mathbf{v}
\]

Here, \( \lambda \) is the **eigenvalue**.


