# Precise decomposition of the rigging claim

Use self-dual Haar measure and Fourier transform on `Q_p`.  For `s>=0`, set

\[
H^s=\left\{f:\int_{\mathbb Q_p}(1+|\xi|_p^{2s})
|\widehat f(\xi)|^2d\xi<\infty\right\}.
\]

Let `D^alpha` be the positive multiplier `|xi|_p^alpha`; its maximal domain
is `H^alpha` with equivalent (indeed, under this convention, displayed)
graph norm.  Let

\[
(U_af)(x)=|a|_p^{1/2}f(ax).
\]

The old bundled name `RIGGING.TRADEOFF.NOGO` must be replaced by the
following separate propositions.

## RT1 — sharp trace theorem

Evaluation at zero extends continuously to `H^s` if and only if `s>1/2`.
It fails at the endpoint.  In `Q_p^d` the same proof gives `s>d/2`.

## RT2 — covariance and norm transformation

For `alpha>0`,

\[
D^\alpha U_a=|a|_p^\alpha U_aD^\alpha,
\qquad U_aD^\alpha U_a^{-1}=|a|_p^{-\alpha}D^\alpha,
\]

and

\[
\|U_af\|_{H^s}^2=\|f\|_2^2+|a|_p^{2s}\|D^sf\|_2^2.
\]

Thus the full dilation group is unitary in the inhomogeneous scale only at
`s=0`; the unit subgroup `|a|_p=1` is unitary for every `s`.

## RT3 — one-point restriction

For `alpha>1/2`,

\[
S_\alpha=D^\alpha\upharpoonright
\{f\in H^\alpha:f(0)=0\}
\]

is closed, densely defined, symmetric, and has deficiency indices `(1,1)`.
Its defect vectors are

\[
\widehat h_z(\xi)=(|\xi|_p^\alpha-z)^{-1},
\quad z\notin[0,\infty).
\]

This is established p-adic point-interaction theory, not a new project
theorem.

## RT4 — abstract unitary/evaluation incompatibility

Suppose a Hilbert function space carries the same half-density action,
evaluation at zero is a nonzero continuous functional, and every `U_a` is
unitary.  Since

\[
\delta_0U_a=|a|_p^{1/2}\delta_0,
\]

unitarity would preserve `||delta_0||` while the displayed equation multiplies
it by `|a|_p^{1/2}`.  A nonunit `a` gives a contradiction.  Hence no such
Hilbert rigging exists.

## Architectural observations, not theorem clauses

- The audited Tate/Fourier symmetries did not select one order from
  `(1/2,infinity)`.  This is a negative literature/source audit, not a theorem
  over all possible source symmetries.
- The particular one-point Green form has only one symplectic channel.  Direct
  calculation shows that it contains no `log p`, iterate labels
  `+/-m log p`, or Archimedean digamma term.  This is a precise comparison of
  two formulas, not a universal obstruction to coupling the point interaction
  to other arithmetic dynamics.

