# Consequence for deficiency theory

Let `A=A*` be bounded on `H` and let `N` be the evaluation-zero Bruhat
subspace.  The operator `S=A|_N` is densely defined and symmetric, but it is
not closed.  The independent proof gives

\[
\overline S=A,
\qquad S^*=A,
\qquad n_+(S)=n_-(S)=0.
\]

The standard singular-restriction construction starts instead with a trace
`tau:dom(A)->G` continuous in the graph norm and a proper graph-closed dense
kernel.  This is explicit in Posilicano's
[Krein-like construction](https://arxiv.org/abs/math/0005082) and
[boundary-triple formulation](https://arxiv.org/abs/math/0309077).  Here the
kernel is graph dense, not graph closed, so the closure erases the proposed
boundary condition.

The rigorous consequences are therefore:

1. this restriction does not define a nontrivial closed symmetric operator;
2. passing to its closure yields the original self-adjoint bounded operator;
3. its closed boundary quotient and deficiency spaces are trivial;
4. an ordinary boundary triple for the closure is correspondingly trivial;
5. a rank-one perturbation cannot be obtained from this restriction by the
   standard graph-continuous trace construction.

What does **not** follow:

- no singular self-adjoint extension can ever be constructed on `Q_p`;
- `delta_0` cannot live in a rigged dual;
- no unbounded source operator can make evaluation continuous;
- no change of measure, added atomic channel, or generalized relation can
  encode a point interaction.

Indeed Vladimirov operators above the sharp regularity threshold do exactly
what the bounded theorem leaves open.  The surviving statement is therefore
“this specific bounded-source restriction yields no deficiency boundary,”
not a universal nonexistence theorem.

