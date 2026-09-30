# PF3/PF4: continuous kernel versus discrete coefficients

## 1. Continuous translation-kernel hierarchy

The object is Riemann's positive even Fourier kernel
\[
\Xi(z)=\int_{\mathbb R}\Phi(u)e^{izu}\,du.
\]
For (r\ge1), (Phi\in PF_r) means
\[
\det[\Phi(x_i-y_j)]_{i,j=1}^{m}\ge0
\]
for every (m\le r) and ordered real (x_i,y_j). This is total
nonnegativity of the continuous Toeplitz kernel.

Known:

- PF1 is positivity of \(\Phi\).
- PF2 is proved (equivalently, the relevant log-concavity).
- Global PF3 and PF4 were not located in the published literature.
- A 2026 preprint reports a certified negative 5-by-5 minor, hence not PF5.
- PF-infinity is impossible independently by Schoenberg's reciprocal
  bilateral-Laplace characterization together with Xi's known zeros.

Finite PF order gives finite variation-diminishing control. It does not imply
that all zeros of the Fourier transform are real. PF-infinity would be a
sufficient but overstrong condition here, not an RH equivalent.

## 2. Discrete Taylor/Jensen coefficient hierarchy

Normalize
\[
\Xi(z)=\sum_{k\ge0}(-1)^k a_k z^{2k},\qquad a_k>0,
\]
and set (G(w)=\sum_{k\ge0}a_kw^k), so
(\Xi(z)=G(-z^2)). Extend (a_k=0) for (k<0).

The sequence is PF_r when every minor of order at most (r) of the
one-sided Toeplitz matrix
\[
T(a)=[a_{j-i}]_{i,j\ge0}
\]
is nonnegative. Consecutive minors studied in recent work have the form
\[
D_{r,k}=\det[a_{k+j-i}]_{i,j=0}^{r-1};
\]
positivity of these alone is weaker than full PF_r.

Jensen polynomials are another, related hierarchy:
\[
J^{d,n}(X)=\sum_{j=0}^{d}\binom dj a_{n+j}X^j.
\]
All degrees and shifts hyperbolic are equivalent, under the standard entire
function hypotheses, to (G\) being Laguerre–Pólya and hence to RH. Fixed
degree/eventual-shift hyperbolicity is strictly below RH. Jensen
hyperbolicity, full PF_r, and positivity of only consecutive minors are not
interchangeable finite-level statements.

Known:

- order-2/Turan inequalities and substantial bounded-degree Jensen results;
- eventual fixed-degree hyperbolicity;
- fixed-order asymptotic multiple positivity;
- a 2026 preprint claiming (D_{r,k}>0) for
  (k\ge10^{18}r^3), not all PF_r minors and not the critical region.

## 3. Logical comparison

The continuous hierarchy samples translates of \(\Phi\). The discrete
hierarchy samples Taylor moments
\(a_k=\int u^{2k}\Phi(u)du/(2k)!\) after normalization. Moment integration
does not automatically transfer PF_r in either direction. A composition
theorem would require an explicitly totally positive moment kernel and exact
normalizations; none was proved here.

Therefore:

- continuous PF3/PF4 does **not** currently imply discrete coefficient PF3/PF4;
- discrete PF3/PF4 does **not** currently imply continuous PF3/PF4;
- neither fixed finite order implies RH;
- discrete PF-infinity/all Jensen hyperbolicity is RH-equivalent;
- continuous PF-infinity is overstrong and false for \(\Phi\).

## 4. Project terminology correction

The Phase-26 research files generally kept the objects separate, but the
phrases “PF3/PF4” and “finite-order positivity” in the final recommendation
were ambiguous. Future use must say either **continuous-kernel PF_r** or
**discrete-coefficient PF_r/Jensen hyperbolicity**. The recommended narrow
coefficient problem concerns the latter; the PF5 counterminor concerns the
former.

