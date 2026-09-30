# Sharp point-evaluation threshold

For a Bruhat function, Fourier inversion gives

\[
f(0)=\int_{\mathbb Q_p}\widehat f(\xi)\,d\xi.
\]

With `w_s(xi)=1+|xi|_p^{2s}`, Cauchy–Schwarz yields

\[
|f(0)|^2\leq \|f\|_{H^s}^2 I_s,
\qquad I_s=\int_{\mathbb Q_p}w_s(\xi)^{-1}d\xi.
\]

The unit ball contributes finitely.  For `k>=1`, the shell
`|xi|_p=p^k` has measure `(1-p^{-1})p^k`, so its contribution is comparable
to

\[
p^{k(1-2s)}.
\]

Therefore `I_s<infinity` exactly when `s>1/2`.  This proves sufficiency.

For necessity, let

\[
F_N(\xi)=w_s(\xi)^{-1}
\mathbf1_{\{1\leq|\xi|_p\leq p^N\}},
\qquad f_N=\mathcal F^{-1}F_N.
\]

The set is a finite union of compact-open shells and `F_N`, hence `f_N`, is
Bruhat–Schwartz.  Writing

\[
J_N=\int_{1\leq|\xi|_p\leq p^N}w_s(\xi)^{-1}d\xi,
\]

one has

\[
f_N(0)=J_N,\qquad \|f_N\|_{H^s}^2=J_N.
\]

If `s<=1/2`, then `J_N -> infinity` (linearly in `N` at `s=1/2`), so
`|f_N(0)|/||f_N||_{H^s}=sqrt(J_N)->infinity`.  Evaluation is unbounded.

Thus

\[
\boxed{\delta_0\in(H^s)'\iff s>1/2.}
\]

There is no dimensional or order ambiguity under the project convention:
the multiplier defining `D^alpha` is `|xi|^alpha`, and its graph norm uses
the squared weight `|xi|^{2alpha}`.  Hence the point-interaction condition is
`alpha>1/2`.  Authors who parameterize a Bessel norm by
`(1+|xi|^2)^s` obtain an equivalent scale; authors who call `D^{alpha/2}`
the energy operator may display a factor-two conversion.  The form-bounded
delta-potential threshold `alpha>1` is a separate statement and must not be
substituted for the domain-evaluation threshold.

