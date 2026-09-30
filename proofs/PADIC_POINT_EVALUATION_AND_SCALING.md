# p-adic point evaluation and half-density scaling

**STATUS:** Correct rederivation of known analytic facts  
**SOURCE:** Publication Audit I; Kuzhel–Torba and Albeverio–Kuzhel–Torba  
**NOVELTY:** Known / known in different language  
**DEPENDENCIES:** p-adic Fourier transform; Vladimirov multiplier  
**RH DEPENDENCE:** None

For `s>=0`, define

\[
\|f\|_{H^s}^2=\int_{\mathbb Q_p}
(1+|\xi|_p^{2s})|\widehat f(\xi)|^2d\xi.
\]

Fourier inversion and Cauchy–Schwarz show that evaluation at zero is bounded
exactly when

\[
I_s=\int_{\mathbb Q_p}(1+|\xi|_p^{2s})^{-1}d\xi<\infty.
\]

The shell `|xi|_p=p^k` has measure `(1-p^{-1})p^k`; its large-`k`
contribution is comparable to `p^{k(1-2s)}`. Hence

\[
I_s<\infty\iff s>\tfrac12.
\]

At `s=1/2` the shell sum diverges linearly. Necessity can be seen by using
truncated weighted Riesz representers on finitely many shells.

For half-density dilation

\[
(U_af)(x)=|a|_p^{1/2}f(ax),
\]

one has

\[
\widehat{U_af}(\xi)=|a|_p^{-1/2}\widehat f(\xi/a),
\]

and therefore

\[
D^sU_a=|a|_p^sU_aD^s,
\quad U_aD^sU_a^{-1}=|a|_p^{-s}D^s,
\]

\[
\|U_af\|_{H^s}^2=\|f\|_2^2+|a|_p^{2s}\|D^sf\|_2^2.
\]

The full multiplicative group is unitary in this inhomogeneous norm only at
`s=0`; the subgroup `|a|_p=1` is unitary for every `s`.

For `alpha>1/2`, the restriction of `D^alpha` to functions in its domain
vanishing at zero is the established closed symmetric point restriction with
deficiency indices `(1,1)`. This last statement is cited, not claimed as new;
see `REFERENCES.md` entries 9–10.

