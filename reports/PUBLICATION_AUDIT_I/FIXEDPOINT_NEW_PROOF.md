# Independent proof of the bounded-graph theorem

Let

\[
\phi_n=\mathbf 1_{p^n\mathbb Z_p}\in\mathcal D.
\]

Then `phi_n(0)=1` and, under the locked Haar normalization,

\[
\|\phi_n\|_2^2=\operatorname{vol}(p^n\mathbb Z_p)=p^{-n}.
\]

For a finite bounded family `A_1,...,A_r`,

\[
\|\phi_n\|_{\rm gr}^2
\leq\left(1+\sum_{j=1}^r\|A_j\|^2\right)p^{-n}\to0.
\]

If evaluation were continuous, `1=|tau(phi_n)|` would tend to zero.  This
proves discontinuity.  Notice that no commutation, Fourier covariance, or
self-adjointness of the `A_j` is used.

To determine the closure of its kernel, take any `psi in D`.  Since `D` is
locally constant, `psi(0)` is defined, and

\[
\psi_n=\psi-\psi(0)\phi_n\in N,
\qquad \|\psi_n-\psi\|_{\rm gr}	o0.
\]

Thus `D` is contained in the graph closure of `N`.  The joint graph norm is
equivalent to the `L2` norm:

\[
\|f\|_2\leq\|f\|_{\rm gr}
\leq C\|f\|_2,
\quad C^2=1+\sum_j\|A_j\|^2.
\]

As `D` is dense in `H`, the graph completion and the closure of `N` are both
`H`.

Now let `A=A*` be bounded and set `S=A|_N`.  Its graph norm is likewise
equivalent to `L2`.  For every `f in H`, choose `f_n in N` with `f_n -> f` in
`L2`.  Boundedness gives `Af_n -> Af`; hence `(f,Af)` belongs to the graph
closure of `S`.  Conversely, closedness of `A` makes every graph limit lie in
`graph(A)`.  Therefore

\[
\overline S=A.
\]

Adjoints are unchanged by closure, so `S*=(overline S)*=A`.  Since a
self-adjoint operator has no nonreal defect vectors,

\[
\ker(S^*\mp i)=0.
\]

This proves all clauses.  The argument actually applies to any norm `q` on a
dense function subspace satisfying `q(f)<=C||f||_2` and containing a sequence
with fixed value at zero and vanishing `L2` norm.

