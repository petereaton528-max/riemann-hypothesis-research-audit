# Public report

## 1. Scope and disclaimer

**RIEMANN HYPOTHESIS REMAINS OPEN.** This archive records a long-form audit of
natural spectral, trace, boundary, cohomological, positivity, and
zero-confinement approaches. It is not a proof attempt offered as a solution,
and it does not establish universal impossibility results.

Status labels are used literally:

- **KNOWN** or **KNOWN IN DIFFERENT LANGUAGE**: established mathematics or a
  standard reformulation;
- **PROJECT COROLLARY**: a deduction made in the project from known or proved
  inputs;
- **NOVELTY UNVERIFIED**: not located in the audited search, without a novelty
  claim;
- **NUMERICAL** or **HEURISTIC**: evidence only;
- **OPEN**: unresolved;
- **CLOSED IN THE AUDITED NATURAL CLASS**: a proved or decisive obstruction
  under explicitly stated assumptions only.

The public authority order is stated in `AUTHORITATIVE_FILES.md`.

## 2. The Riemann trace fingerprint

The project used a locked target rather than accepting a generic “spectral
analogy.” A viable construction must account simultaneously for:

- average zero density of order `(T/2pi) log(T/2pi)`;
- the Archimedean Gamma/digamma contribution;
- finite-place support at `+/-m log p`;
- weights `(log p)p^{-m/2}`;
- local-to-global structure and the functional equation;
- multiplicity-sensitive nontrivial-zero data.

The half-density factor is not mysterious: normalized local scaling and
fixed-point formulas naturally produce it. The primitive factor `log p` and
the two-sided prime-power support arise from orbit/shell measure and
forward–reverse scaling. These facts are **KNOWN IN DIFFERENT LANGUAGE** in
Tate/Connes and representation-theoretic settings. They are structural clues,
not a line-forcing theorem.

## 3. Realization versus line forcing

The central conceptual separation is:

1. construct a source-defined object that genuinely carries zero data;
2. prove an independent theorem forcing the shifted spectral parameters to be
   real.

The first task has meaningful answers. Meyer’s nuclear Fréchet representation
and the adelic/cyclic/Lefschetz constructions provide genuine zero-bearing
structures. Connes-style cutoff traces reproduce the arithmetic fingerprint.
The second task remains unresolved. Positive global forms strong enough to
force the line return to Weil positivity, and hence to an RH-equivalent
condition. This is the project’s most important negative conclusion.

## 4. Tate/Connes/Meyer/CCM audit

### Tate and local trace structure — KNOWN

Tate’s local zeta integrals, Fourier transform, and Poisson summation explain
the local factors, Gamma sector, and functional equation. Finite-place and
Archimedean characters assemble as the known explicit-formula distribution.
The identity is unconditional; positivity of the resulting Weil form is a
different question.

### Connes cutoff/compression — PARTIAL / KNOWN REFORMULATION

Local and finite-set cutoff trace identities are structurally meaningful.
Critical and hypothetical off-line modes have different cutoff asymptotics,
but ordinary distributional convergence can accommodate resonances. A global
positive-cone convergence statement strong enough to exclude them is
RH-equivalent. The trace identity should not be confused with positivity.

### Meyer carrier — GENUINE REALIZATION, NO INDEPENDENT POLARIZATION

The nuclear representation carries generalized zero eigenspaces and Jordan
jets. Direct critical `L2` completion, however, loses the desired quotient in
the audited setting. Canonical duality survives; a faithful positive
polarization would force more than the location of zeros by constraining
Jordan structure. No source-derived positive polarization below RH was found.

### CCM finite sections — PARTIAL / NUMERICALLY ADVERSE

The project developed several Galerkin, coercivity, and tail estimates. The
unique-ray/ground-state selection mechanism remained unidentified and showed
adverse finite-section evidence. Some analytic tail lemmas remain candidates
for separate re-audit, but no CCM selection theorem is claimed.

## 5. Hilbert, boundary, and rigging obstructions

### Bounded fixed-point graph result — PROJECT COROLLARY

For `L2(Q_p)`, point evaluation at zero is discontinuous under every finite
bounded graph augmentation. Shrinking p-adic balls have value one at zero and
norm tending to zero. Restricting a bounded self-adjoint operator to
evaluation-zero Bruhat functions therefore gives a nonclosed restriction
whose closure is the original operator. This specific construction has no
nontrivial deficiency boundary.

Publication Audit I found this correct but elementary. Its status is
**PROJECT COROLLARY**, not a new specialist theorem. It does not rule out
unbounded graph norms, atomic measures, or independently supplied singular
extension data.

### Vladimirov repair — KNOWN ANALYSIS

In the project normalization, evaluation on `H^s(Q_p)` is continuous exactly
for `s>1/2`; the endpoint fails. For such orders the evaluation-zero
restriction of the Vladimirov operator is the known one-point symmetric
restriction with deficiency indices `(1,1)`.

The full original half-density action is unitary in the inhomogeneous scale
only at `s=0`; the p-adic unit subgroup is unitary at every order. More
abstractly, continuous evaluation transforms by the non-unimodular character
`|a|_p^{1/2}`, so it cannot coexist with unitarity of the full original action
on any Hilbert rigging. This observation is elementary and **KNOWN IN
DIFFERENT LANGUAGE**.

The one-point Green form does not itself contain `log p`, prime-power iterate
times, or the Archimedean term. That is a scoped formula comparison, not a
universal no-go theorem.

## 6. Imported cross-field mechanisms

Boundary triples, passive/KYP systems, Herglotz and Schur realizations,
reflection positivity, tempered representations, modular/KMS theory,
semifinite spectral theory, cyclic cohomology, and trace-native categories
were audited.

- Ordinary boundary triples built from dilation see endpoint flux, not the
  arithmetic prime/Gamma distribution.
- Passivity or Herglotz positivity strong enough to force the line was not
  derived independently of Weil positivity.
- Natural reflection-positive candidates failed or reproduced an RH-level
  positivity demand.
- Local half-density dilation is genuinely unitary/tempered away from the
  fixed point, but the arithmetic flat trace lives at the measure-zero point
  discarded by ordinary Hilbert equivalence.
- Groupoid, cyclic, and distributional traces naturally retain fixed-point
  data; they did not add an independent reality theorem to the already known
  global carriers.

These are **CLOSED IN THE AUDITED NATURAL CLASSES**, not universal
impossibility claims.

## 7. Non-spectral zero-confinement programme

A second programme reversed the search order: start from mature mechanisms
that force real zeros, then ask whether arithmetic source data generate them.
The audit covered canonical approximants, prime recursion, interlacing,
total positivity, Pólya-frequency classes, moment/Hankel inequalities, Jensen
polynomials, Lee–Yang theory, Hermite–Biehler theory, and heat-flow or
renormalization ideas.

Natural finite Euler products do not provide locally uniform entire
approximants to completed Xi, and exact local Euler insertion is incompatible
with a fixed entire completion in the audited class. No source-derived
prime-by-prime real-root preserver or canonical interlacing family was found.
Lee–Yang and Hermite–Biehler mechanisms either lacked an arithmetic source
model or reduced to an RH-level condition.

Finite-order positivity remains a narrow mathematical topic, but terminology
must be separated:

- continuous-kernel PF order concerns minors of translates of the Xi kernel;
- discrete coefficient PF order concerns Toeplitz minors of Taylor
  coefficients;
- Jensen-polynomial hyperbolicity is related but not identical.

No implication between the continuous and discrete finite-order hierarchies
was established. See `PF_HIERARCHY_DISAMBIGUATION.md`.

## 8. Corrected publication audit

The initial consolidation treated `FIXEDPOINT.GRAPH.NOGO` and
`RIGGING.TRADEOFF.NOGO` as possible cores of an obstruction paper.
Publication Audit I changed that assessment:

- the fixed-point result is correct in finite-bounded scope but elementary;
- the rigging label must be decomposed into known analytic theorems and
  architectural observations;
- the point-interaction theory was already explicit in the primary
  literature;
- the current obstruction-paper package is **VIABLE ONLY AS AN EXPOSITORY
  NOTE**, not an original research article.

This correction governs all public interpretation of Phase 22–23.

## 9. Closed routes and exact scope

The master route table provides full detail. Particularly important closures
are:

1. ordinary compact elliptic and direct Selberg analogies: wrong density or
   arithmetic amplitudes;
2. CCM unique-ray alignment: no identified selector and adverse evidence;
3. direct/faithful positive Meyer Hilbert completion: collapse or RH-level
   positivity in the audited completion classes;
4. bounded Green and standard Vladimirov repair: exact topology/unitarity and
   arithmetic-data limitations stated above;
5. exact finite-prime entire recursion and canonical interlacing: no natural
   entire completion/preserver under the audited axioms.

Reopening any route requires a genuinely new theorem, source object, or
mechanism that changes the stated obstruction—not a relabeling of the same
condition.

## 10. Open narrow problems

The public list is `reports/OPEN_PROBLEMS.md`. The strongest clear questions
are the CCM–Meyer comparison, continuous Xi-kernel PF3/PF4, the first truly
unresolved discrete coefficient PF order, independent verification of recent
PF claims, and a line-by-line audit of retained coercivity estimates. None is
presented as a likely RH proof route.

## 11. Research debt

The highest-risk items are:

- recent preprint claims not independently reproduced;
- analytic/computer-assisted Schur chains without a second implementation;
- tail-coercivity domain and uniformity details;
- terminology drift between continuous PF, discrete PF, and Jensen
  hierarchies;
- incomplete novelty coverage for older project corollaries;
- historical local/finite-set/global scope drift.

Publication Audit I resolved the main Phase-22/23 extension-theory debt but
left historical files untouched. The correction record must be read instead.

## 12. Conclusions

The project improved the precision of several intuitions without proving RH.
It clarified that zero realization is not line forcing; that arithmetic flat
traces and Hilbert spectral mass are different kinds of data; that stronger
riggings trade source-normalized unitarity for point regularity; and that
natural arithmetic approximation does not automatically preserve zero
geometry.

Broad RH exploration remains paused. The defensible future work is
consolidation, independent verification, and narrow mathematics whose value
does not depend on an RH claim.

