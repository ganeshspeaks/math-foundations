
# 1a. Set Theory

## Basic Operations
- Union: A ∪ B = {x : x ∈ A or x ∈ B}
- Intersection: A ∩ B = {x : x ∈ A and x ∈ B}
- Difference: A − B = {x : x ∈ A and x ∉ B}
- Complement: A' = U − A
- Symmetric Difference: A △ B = (A − B) ∪ (B − A)

## De Morgan's Laws
- (A ∪ B)' = A' ∩ B'
- (A ∩ B)' = A' ∪ B'

## Cardinality Formulas
- |A ∪ B| = |A| + |B| − |A ∩ B|
- |A ∪ B ∪ C| = |A| + |B| + |C| − |A ∩ B| − |B ∩ C| − |A ∩ C| + |A ∩ B ∩ C|
- |A × B| = |A| · |B|
- Power set: |P(A)| = 2^n where n = |A|

## Relations
- Total relations possible on set of n elements: 2^(n²)
- Equivalence relation partitions set into disjoint subsets
- Congruence modulo n: a ≡ b (mod n) ⟺ n divides (a − b)

## Functions
- Injective (one-one): f(a) = f(b) ⟹ a = b
- Surjective (onto): range = codomain
- Bijective: both injective and surjective
- Number of functions from A → B: |B|^|A|
- Number of injections from A → B: |B|P|A| (permutation)
- Number of bijections from A → A: n!

