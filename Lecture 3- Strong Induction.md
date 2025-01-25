# Strong Induction

Let P(n) be any predicate.If P(0) is true and
$\forall n (P(0)\land P(1) \land ... \land P(n))\implies P(n+1)$ is true,
then every P(n) is true.

> [!hint]
> Any proof can be done by strong induction can be done by ordinary induction.But strong induction make it easier to prove

# The Well Ordering Principle

- [n] Every nonempty set of nonnegative integers has a smallest element.

# Template for Well Ordering Proofs

- [7] Template
![[static/images/Pasted image 20250125200544.png]]

- [8] Example Proof
![[static/images/Pasted image 20250125202331.png]]

# Template for Ordinary Induction Proofs

- [7] Template
![[static/images/Pasted image 20250125202853.png]]

# Invariant

One of the most important uses of induction in computer science involves proving that a program or process preserves one or more desirable properties as it proceeds.

A property that is preserved through a series of operations or steps is known as an ==**invariant**==.

- [7] Template
![[static/images/Pasted image 20250125203822.png]]

# Structural Induction

## Recursive Data Types

	Recursive data types are specified by recursive definitions.
Recursive definitions:
- **Base case(s)** that dont depend on anything.
- Constructor case(s) that depend on previos cases.


## Structural Induction on Recursive Data Types

- Prove P for the base cases of the definition.
- Prove P for the constructor cases of the definition, assuming that is true for the component data items.



[[Lecture 6 - Graph Theory and Coloring]]
