# Adversarial scope of the bounded-graph result

## Theorem remains true

- **Bruhat–Schwartz or locally constant compactly supported domains:** the
  shrinking balls belong to both.
- **Any finite bounded operator family:** no algebraic assumptions are needed.
- **Any graph-like norm dominated by `C||.||_2`:** this includes uniformly
  bounded infinite families when their combined norm still has that bound.
- **Equivalent Hilbert norms and bounded renormings:** equivalence preserves
  the shrinking-ball convergence.
- **Different nontrivial additive characters:** Fourier remains unitary; the
  proof does not otherwise use the character.
- **Finite extensions `K/Q_p`:** with residue cardinality `q`,
  `||1_{pi^n O_K}||_2=q^{-n/2}`, so the same proof works.
- **Atomless weighted `L2` spaces:** point values are not defined on
  equivalence classes.  For locally integrable weights whose mass of shrinking
  balls tends to zero, the same spike proof applies.

## The conclusion needs qualification

- `N` is not closed in the graph completion; as an abstract subspace of the
  incomplete Bruhat space, “closed” must always name the induced norm.
- The theorem concerns the evaluation-zero restriction of a bounded
  self-adjoint `A`.  A nonsymmetric bounded operator has no deficiency-index
  interpretation.
- Infinitely many bounded operators can collectively define a strictly
  stronger norm.  For example, frequency-shell projections with growing
  weights reconstruct a Sobolev norm.  Finite-family boundedness cannot be
  extrapolated to that case.

## The theorem no longer applies

- Graph norms of unbounded elliptic or Vladimirov multipliers can control
  evaluation.
- A Hilbert space with an atom at zero makes the point a genuine `L2` degree
  of freedom, but it changes the measure and source representation.
- A reproducing-kernel Hilbert space can have continuous evaluation, but its
  norm is not equivalent to the atomless `L2` norm.
- Singular boundary relations may be built after supplying an independent
  graph-continuous trace.  The theorem only says the bounded source does not
  supply one.

Thus the exact boundary is topological: evaluation remains invisible under
norms no stronger than `L2`; it may become visible only after changing the
topology or measure.

