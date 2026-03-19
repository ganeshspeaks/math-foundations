
# 1c. Linear Algebra

## Matrices — Basic
- Addition: (A+B)ᵢⱼ = Aᵢⱼ + Bᵢⱼ
- Scalar: (cA)ᵢⱼ = c·Aᵢⱼ
- Multiplication: (AB)ᵢⱼ = Σₖ AᵢₖBₖⱼ
- Transpose: (Aᵀ)ᵢⱼ = Aⱼᵢ
- (AB)ᵀ = BᵀAᵀ
- (AB)⁻¹ = B⁻¹A⁻¹

## Types of Matrices
- Symmetric: A = Aᵀ
- Skew-Symmetric: A = −Aᵀ → diagonal entries = 0
- Hermitian: A = Ā ᵀ (conjugate transpose)
- Skew-Hermitian: A = −Ā ᵀ
- Orthogonal: AAᵀ = AᵀA = I → A⁻¹ = Aᵀ
- Unitary: AĀᵀ = I

## Determinants
- det(AB) = det(A)·det(B)
- det(Aᵀ) = det(A)
- det(A⁻¹) = 1/det(A)
- det(cA) = cⁿ·det(A) for n×n matrix
- det(A) = 0 ⟺ A is singular
- For 2×2: det[[a,b],[c,d]] = ad − bc

## Inverse
- A⁻¹ = adj(A)/det(A)
- adj(A) = transpose of cofactor matrix
- Exists only when det(A) ≠ 0

## Rank
- Rank = number of nonzero rows in row echelon form
- rank(A) + nullity(A) = n (Rank-Nullity Theorem)
- rank(AB) ≤ min(rank(A), rank(B))

## System of Linear Equations Ax = b
- Unique solution: rank(A) = rank(A|b) = n
- Infinite solutions: rank(A) = rank(A|b) < n
- No solution: rank(A) ≠ rank(A|b)

## Eigenvalues & Eigenvectors
- Definition: Av = λv, v ≠ 0
- Characteristic equation: det(A − λI) = 0
- Sum of eigenvalues = trace(A) = Σ aᵢᵢ
- Product of eigenvalues = det(A)
- Cayley-Hamilton: every matrix satisfies its own characteristic equation

## Linear Transformations
- T(u + v) = T(u) + T(v)
- T(cu) = cT(u)
- T(0) = 0
- Rank-Nullity: dim(ker T) + dim(im T) = dim(V)
- Matrix representation: [T]_B = matrix of T with respect to basis B

## Inner Product & Norms
- ⟨u, v⟩ = Σ uᵢvᵢ (standard dot product)
- ‖v‖ = √⟨v,v⟩
- Cauchy-Schwarz: |⟨u,v⟩| ≤ ‖u‖·‖v‖
- Triangle inequality: ‖u+v‖ ≤ ‖u‖ + ‖v‖
