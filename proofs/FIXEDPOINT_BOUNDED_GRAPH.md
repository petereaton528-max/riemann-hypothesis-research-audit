# Finite bounded-graph invisibility of p-adic point evaluation

**STATUS:** Rigorously audited project corollary; correct in the stated scope  
**SOURCE:** Publication Audit I, independent reproof  
**NOVELTY:** Elementary project corollary; low standalone novelty  
**DEPENDENCIES:** Haar measure on `Q_p`; bounded operators on `L2`  
**RH DEPENDENCE:** None

Let

\[
H=L^2(\mathbb Q_p,dx),\qquad \mathcal D=\mathcal S(\mathbb Q_p),
\]

with `vol(Z_p)=1`. Let `A_1,...,A_r` be a finite family of bounded
operators on `H`, and define on `D`

\[
\|f\|_{\rm gr}^2=\|f\|_2^2+\sum_{j=1}^r\|A_jf\|_2^2.
\]

For `phi_n=1_{p^n Z_p}`,

\[
\phi_n(0)=1,
\qquad \|\phi_n\|_2^2=p^{-n},
\]

and boundedness gives

\[
\|\phi_n\|_{\rm gr}^2
\leq\left(1+\sum_j\|A_j\|^2\right)p^{-n}\to0.
\]

Therefore evaluation `tau(f)=f(0)` is not graph continuous.

Set `N={f in D:f(0)=0}`. For any `psi in D`,

\[
\psi-\psi(0)\phi_n\in N
\]

and this sequence converges to `psi` in graph norm. Because the finite bounded
graph norm is equivalent to the `L2` norm, `N` is dense in the graph
completion.

If `A=A*` is bounded and `S=A|_N`, then `S` is densely defined and symmetric
but not closed. For any `f in H`, choose `f_n in N` with `f_n -> f`. Then
`Af_n -> Af`, so

\[
\overline S=A,
\qquad S^*=A,
\qquad \ker(S^*\mp i)=0.
\]

Thus this particular evaluation-zero restriction creates no nontrivial closed
deficiency boundary. The result does not cover unbounded graph norms, atomic
measures, or independently chosen singular-extension data.

