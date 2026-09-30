# Precise bounded-graph theorem

Fix the standard additive character of `Q_p`, self-dual Haar measure `dx`
with `vol(Z_p)=1`, and

\[
H=L^2(\mathbb Q_p,dx),\qquad \mathcal D=\mathcal S(\mathbb Q_p).
\]

Elements of `H` are equivalence classes, so point evaluation is not an
operation on `H`.  On the Bruhat–Schwartz subspace it is the well-defined
linear functional

\[
\tau(f)=f(0).
\]

For `a in Q_p^times`, the source-normalized dilation and Fourier transform are

\[
(U_af)(x)=|a|_p^{1/2}f(ax),\qquad \mathcal Ff(\xi)
=\int f(x)\chi(\xi x)\,dx.
\]

Both are unitary on `H`.  Let `A_1,...,A_r` be any **finite** family of
bounded operators on `H`; this includes finite collections of such dilations,
Fourier transforms, adjoints, and bounded algebraic combinations.  On
`D` define

\[
\|f\|_{\rm gr}^2=\|f\|_2^2+\sum_{j=1}^r\|A_jf\|_2^2.
\]

## Theorem FG

1. `tau` is not continuous in this norm.
2. `N={f in D: f(0)=0}` is not closed in `D` for the induced graph topology,
   and its closure in the graph completion is all of `H`.
3. If `A` is a bounded self-adjoint operator on `H` and
   `S=A|_N`, then `S` is densely defined and symmetric but not closed, and
   its operator closure is `A`.  Consequently
   `S*=A`, its deficiency indices are `(0,0)`, and the boundary quotient of
   the closed restriction is zero.

The convergence in (1) is convergence in the displayed joint graph norm.
The theorem does not say that no unbounded operator or singular perturbation
can detect zero.  It says that imposing `f(0)=0` on this finite bounded graph
source does not create a nontrivial closed symmetric restriction.

The arithmetically named version is only an application of Theorem FG: the
half-density and Fourier source operators happen to be members of the bounded
family.  No arithmetic property is needed for the proof.

