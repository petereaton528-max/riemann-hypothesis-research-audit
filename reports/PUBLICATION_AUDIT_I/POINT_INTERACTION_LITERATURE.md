# Point-interaction literature audit

## Primary result

Kuzhel–Torba's
[2006 paper](https://arxiv.org/abs/math-ph/0612061) and the expanded
Albeverio–Kuzhel–Torba
[2008 JMAA paper](https://arxiv.org/abs/math-ph/0703077) already study finite
rank point perturbations of the Vladimirov operator.  Under the multiplier
normalization

\[
D^\alpha=\mathcal F^{-1}|\xi|_p^\alpha\mathcal F,
\]

they establish:

- `dom(D^alpha)` consists of continuous functions exactly for
  `alpha>1/2` (Proposition 2.1 in the JMAA version);
- `(D^alpha-z)h=delta_x` has a unique `L2` solution off the spectrum exactly
  in that range (Theorem 2.1);
- the symmetric restriction to functions vanishing at `n` points is the
  minimal operator for the point-interaction problem;
- its adjoint domain is `dom(D^alpha)` plus the span of the `n` Green
  vectors, giving one defect channel per point;
- the delta perturbation is form-bounded only in the stronger range
  `alpha>1`.

For one point this gives deficiency indices `(1,1)`.  If
`h=(D^alpha+I)^{-1}delta_0`, then

\[
\operatorname{dom}S_\alpha^*
=\operatorname{dom}D^\alpha\dotplus\mathbb Ch,
\qquad S_\alpha^*(u+ch)=D^\alpha u-ch.
\]

With inner product linear in the first variable, boundary maps can be chosen
as `Gamma_0(u+ch)=c` and `Gamma_1(u+ch)=u(0)`, and the Green form is

\[
u(0)\overline d-c\overline{v(0)}.
\]

Self-adjoint extensions are the one-real-parameter Lagrangian boundary
conditions.  The detailed regularization of a *specified additive delta
potential* is more delicate for `1/2<alpha<=1`; that does not change the
minimal restriction or its defect count.

## General extension theory

Posilicano's
[Krein-like formula](https://arxiv.org/abs/math/0005082) and
[boundary-triple paper](https://arxiv.org/abs/math/0309077) formulate the
general mechanism: a graph-continuous trace on `dom(A)` with a proper
graph-closed dense kernel produces a closed symmetric restriction and its
extensions.  This confirms both halves of the project comparison: bounded
source operators fail the trace hypothesis, while `D^alpha`, `alpha>1/2`,
satisfies it.

## Arithmetic/Tate overlap

Huang–Stoica–Yau–Zhong
[derive Vladimirov Green functions from local Tate functional equations](https://arxiv.org/abs/2001.01721),
but the quasi-character/order is input.  This supports only the observation
that the Tate family does not visibly single out the project order; it is not
a theorem that no arithmetic principle could ever select one.

## Audit conclusion

The threshold, defect vectors, deficiency indices, Green form, and extension
parameters are **KNOWN**.  The project proof is a valid rederivation, not a
new point-interaction theorem.

