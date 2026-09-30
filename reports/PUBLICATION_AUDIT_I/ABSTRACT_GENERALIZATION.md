# Abstract generalizations

## A. Bounded graph invisibility

Let `(X,mu)` be atomless, `x_0` a point, `E subset L2(X,mu)` a dense vector
space of actual functions, and suppose there are `e_n in E` with

\[
e_n(x_0)=1,\qquad \|e_n\|_2\to0.
\]

Let `q` be any norm on `E` satisfying `q(f)<=C||f||_2`.  Then evaluation at
`x_0` is not `q`-continuous.  If `E` is `q`-dense in its `L2` completion, the
kernel of evaluation is dense as well whenever `f-f(x_0)e_n` belongs to that
kernel.

Every joint graph norm of a finite family of bounded operators satisfies the
domination hypothesis.  This is the exact abstract content of
`FIXEDPOINT.GRAPH.NOGO`; the p-adic balls merely provide the `e_n`.

The hypothesis cannot be dropped.  An infinite operator family with growing
weights, an unbounded multiplier, an RKHS norm, or an atomic measure can make
evaluation continuous.

## B. Unitary fixed-point character obstruction

Let `K` be a Hilbert space of functions on a set `X`, let `x_0 in X`, and let
`U_g` be a unitary representation of a group `G` on `K`.  Suppose evaluation
`ell(f)=f(x_0)` is nonzero and continuous and

\[
\ell U_g=\chi(g)\ell.
\]

Then `|chi(g)|=1` for every `g`: taking operator norms on the dual gives
`||ell||=||ell U_g||=|chi(g)| ||ell||`.

For p-adic half-density scaling, `chi(a)=|a|_p^{1/2}`, which is not unimodular
on the full multiplicative group.  Therefore no Hilbert rigging can
simultaneously retain nonzero continuous fixed-point evaluation and make the
original full half-density action unitary.

This generalization is stronger than the inhomogeneous Sobolev calculation
but elementary.  It does not forbid covariance, bounded invertibility,
unitarity of the unit subgroup, or a renormalized representation.

## C. Fourier-multiplier threshold

For a positive radial weight `w`, evaluation is continuous in the Hilbert
space with norm `int w|fhat|^2` precisely when `w^{-1}` is integrable.  The
Vladimirov threshold follows by inserting `w=1+|xi|^{2s}`.  This is a standard
reproducing-kernel/Fourier-multiplier criterion rather than an
arithmetic-specific theorem.

