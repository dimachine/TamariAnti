# TamariAnti
Contains the codes and formal context files for counting of (maximal) antichains of Tamari lattices


This is a supporing file for OEIS on computation of (maximal) antichains in the Tamari lattice of bracketing structures.

## Outline

### 0. The basic code with the class for managing generation of formal concepts via NextClosure algorithm

### 1. Loading formal contexts for antichains and maximal antichains of Tamari lattice

### 2. Counting of maximal antichains for n in {0, 1, 2, 3, 4, 5, 6} 

### 3. Counting of  antichains for n in {0, 1, 2, 3, 4, 5} 

#### Comment to Sections 2 and 3.


We start with n=0 (i.e., with the set partition of zero elements), but in OEIS the respective offset is 1, i.e. there the sequences start with n=1.
Note also that the n-th order of the Tamari means that it is built over brackeing structures on n+1 elements. 

## References

* Bernhard Ganter, Rudolf Wille:
Formal Concept Analysis - Mathematical Foundations. Springer 1999, ISBN 978-3-540-62771-5, pp. I-X, 1-284.

* Tamari, Dov (1962), "The algebra of bracketings and their enumeration", Nieuw Archief voor Wiskunde, Series 3, 10: 131–146, MR 0146227.

* Huang, Samuel; Tamari, Dov (1972), "Problems of associativity: A simple proof for the lattice property of systems ordered by a semi-associative law", Journal of Combinatorial Theory, Series A, 13: 7–13, doi:10.1016/0097-3165(72)90003-9, MR 0306064.

* Knuth, Donald E. (2005), "Section 7.2.1.6: Generating All Trees", The Art of Computer Programming, vol. IV.


NB. Any usage of the codes requires the acknowledgment of this repository.
