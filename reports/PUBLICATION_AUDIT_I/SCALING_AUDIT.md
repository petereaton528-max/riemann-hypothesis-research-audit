# Scaling covariance audit

Let `U_a f(x)=|a|_p^{1/2}f(ax)`.  Substitution `y=ax` gives

\[
\widehat{U_af}(\xi)=|a|_p^{-1/2}\widehat f(\xi/a).
\]

Consequently

\[
\widehat{D^\alpha U_af}(\xi)
=|\xi|_p^\alpha|a|_p^{-1/2}\widehat f(\xi/a),
\]

whereas

\[
\widehat{U_aD^\alpha f}(\xi)
=|a|_p^{-1/2}|\xi/a|_p^\alpha\widehat f(\xi/a).
\]

Since `|xi/a|=|xi|/|a|`,

\[
D^\alpha U_a=|a|_p^\alpha U_aD^\alpha,
\qquad U_aD^\alpha U_a^{-1}=|a|_p^{-\alpha}D^\alpha.
\]

Plancherel proves `||U_af||_2=||f||_2`.  For the project Sobolev norm,

\[
\|U_af\|_{H^s}^2
=\|f\|_2^2+|a|_p^{2s}\|D^sf\|_2^2.
\]

It follows that the full `Q_p^times` action is unitary precisely at `s=0`.
For `|a|_p=1`, it is unitary at every order, an omitted qualification in some
historical summaries.

For the homogeneous energy seminorm, `|a|_p^{-s}U_a` is isometric.  This is
not the original half-density representation: its `L2` norm is rescaled and

\[
\delta_0(|a|_p^{-s}U_af)=|a|_p^{1/2-s}f(0).
\]

Thus homogeneous renormalization does not preserve both the original
half-density normalization and rigging unitarity.

The conflict is norm-independent in the following sense.  If evaluation is a
nonzero bounded functional on any Hilbert rigging and the original `U_a` are
unitary there, then dual norms give

\[
\|\delta_0\|=\|\delta_0U_a\|
=|a|_p^{1/2}\|\delta_0\|,
\]

impossible for a nonunit `a`.  This elementary dual-eigenfunctional argument
is the strongest valid generalization of the unitarity tradeoff.

