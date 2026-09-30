# Audit of all indexed results

Legend: **SC** = self-contained at the repository level (`Y` yes, `P`
substantial cited input, `N` open/computational artifact). “RH dep.” means RH
is assumed, not merely mentioned; none of the retained theorems assumes RH.

| # | result | classification | proof path | RH dep. | numeric | SC | narrowing / audit note |
|---:|---|---|---|---|---|---|---|
| 1 | 7.G(a) | KNOWN-IN-DIFFERENT-LANGUAGE | `proof_attempts/phase7_first_convergence_lemma.md` | none | no | P | standard compact-resolvent Galerkin theorem; keep fixed \(\lambda\) |
| 2 | 7.G(b) | KNOWN-IN-DIFFERENT-LANGUAGE | same | none; assumes simplicity | no | P | implication only; T1 remains open |
| 3 | 8.J | NEW-COROLLARY / NOVELTY-UNVERIFIED | `proof_attempts/phase8_first_gap_or_residual_lemma.md` | none | no | Y | only clauses (i)–(iii); decaying residual failed |
| 4 | 8.V/8.D/8.L2 | NEW-COROLLARY | `proof_attempts/phase8_rayleigh_defect.md` | none | no | Y | identities only; exclude failed 8.R/8.T |
| 5 | 9.K | KNOWN-IN-DIFFERENT-LANGUAGE | `proof_attempts/phase9_kernel_and_normality.md` | none | no | P | form-domain claim under locked CCM conventions |
| 6 | 9.W | KNOWN / conditional identity | same | none; assumes T1 | no | Y | tautological once 9.K and T1 hold |
| 7 | 9.P | KNOWN | same | none | no | P | CCM convergence implication recast |
| 8 | Phase-9 reduction identity | NEW-COROLLARY | `proof_attempts/phase9_direct_transform_estimate.md` | none | no | Y | identity only; oscillatory bound failed |
| 9 | L9 | NEW-COROLLARY | `proof_attempts/phase9_lemma_L9.md` | none | no | Y | rewrite, not an estimate |
| 10 | L10 abstract | KNOWN-IN-DIFFERENT-LANGUAGE | `proof_attempts/phase10_transfer_lemma_L10.md` | none | no | Y | Davis–Kahan theorem; Weil hypotheses open |
| 11 | L11.5 | NEW-COROLLARY / NOVELTY-UNVERIFIED | `proof_attempts/phase11_lemma_L11.md` | none | no | P | applies to windowed source \(k^w\), not CCM ground \(k_\lambda\) |
| 12 | L11-SPLIT | KNOWN algebraic identity | same | none | no | Y | no smallness conclusion |
| 13 | 12.D1 | NEW-COROLLARY | `proof_attempts/phase12_archimedean_transfer.md` | none | no | P | mixed Archimedean term only |
| 14 | 12.F1 | NEW-COROLLARY | `proof_attempts/phase12_prime_cross_cancellation.md` | none | no | P | \(O(1)\), not \(o(1)\) |
| 15 | 12.P1 | NEW-COROLLARY | `proof_attempts/phase12_archimedean_transfer.md` | none | no | Y | polar values only |
| 16 | 12.H2 | NEW-COROLLARY / NOVELTY-UNVERIFIED | `research/PHASE12_RESULT.md` | none | no | P | proof should be extracted from result narrative before paper use |
| 17 | 12.C1–C2 | KNOWN-IN-DIFFERENT-LANGUAGE / NEW-COROLLARY | `research/PHASE12_RESULT.md` | none | no | P | continuity estimates; same extraction issue |
| 18 | GAL.HM | NEW-COROLLARY / NOVELTY-UNVERIFIED | `proof_attempts/pre_phase13_galerkin_uv_lemma.md` | none | no | P | fixed \(\lambda\); diagonal asymptotic |
| 19 | GAL.UV | NEW-COROLLARY | same | none | motivation only | P | corollary of GAL.HM; not eigenvector convergence |
| 20 | TAIL.COERCIVITY | POSSIBLY-NEW / NOVELTY-UNVERIFIED | `proof_attempts/pre_phase13_continuum_recovery_lemma.md` | none | no | P | requires independent check of high-subspace bounds |
| 21 | WEIGHTED.SCHUR | POSSIBLY-NEW / NOVELTY-UNVERIFIED | `proof_attempts/pre_phase13_weighted_schur_lemma.md` | none | yes for thresholds | P | fixed \(\lambda=2\), fixed finite low sector; analytic/numeric split needed |
| 22 | LOWRANK.TAIL | POSSIBLY-NEW / NOVELTY-UNVERIFIED | `proof_attempts/pre_phase13_lowrank_tail_lemma.md` | none | certificate support | P | upper-bound kernel only, not true Schur complement asymptotic |
| 23 | K.FIN.OFF | NEW-COROLLARY / NOVELTY-UNVERIFIED | `proof_attempts/pre_phase13_exact_resolvent_lemma.md` | none | yes | P | \(\lambda=2\) and locked integer Fourier basis |
| 24 | POLAR.WOODBURY | KNOWN identity + NUMERICAL corollary | same | none | yes | P | distinguish exact rank-two identity from certified bounds |
| 25 | NEUMANN.HIGH | NEW-COROLLARY / NOVELTY-UNVERIFIED | same | none | yes | P | only certified \(M\) range at \(\lambda=2\) |
| 26 | MAT.ATOM | KNOWN-IN-DIFFERENT-LANGUAGE | `proof_attempts/pre_phase13_matrix_rigidity_lemma.md` | none | experiments support | P | structural matrix formula; selection claim failed |
| 27 | COM.E | KNOWN | `proof_attempts/pre_phase13_commutator_lemma.md` | none | no | Y | Euler intertwining identity |
| 28 | COM.NOGO | NO-GO / NEW-COROLLARY | same | none | no | Y | only transfer of the audited Slepian pair |
| 29 | DR.RAD | KNOWN | `proof_attempts/pre_phase13_degenerate_radical_lemma.md` | none | no | P | global \(\mathcal E\)-radical recast |
| 30 | DR.NOGO | NO-GO | same | none | no | P | transverse positivity is Weil positivity; not universal positivity no-go |
| 31 | DC.NOGO | NO-GO / NEW-COROLLARY | `proof_attempts/pre_phase13_dual_certificate_lemma.md` | none | no | Y | applies to specified observable/remainder |
| 32 | LD.INT | KNOWN abstract implication | `proof_attempts/pre_phase13_logderivative_lemma.md` | none | no | Y | implication only |
| 33 | LD.NOGO | NO-GO / NEW-COROLLARY | same | none | no | P | specified CCM determinant/log derivative only |
| 34 | IDENTIFIABILITY.NOGO | NO-GO / NEW-COROLLARY / NOVELTY-UNVERIFIED | `proof_attempts/pre_phase13_identifiability_nogo.md` | none | no | P | analytic sine countermodel is solid; operator clause needs explicit construction or removal |
| 35 | CANONICAL.NOGO | NO-GO / KNOWN-IN-DIFFERENT-LANGUAGE | `proof_attempts/pre_phase13_canonical_system_candidate.md` | none | no | P | inverse/Xi-derived realizations only; not all canonical systems |
| 36 | compression inertia \(A_8\) | NUMERICAL | `research/pre_phase13_cert_infra/inertia.md` | none | Arb | N | finite compression, not continuum; second-stack reproduction needed |
| 37 | Arb \(W_\mathbb R\) enclosures | NUMERICAL / KNOWN formula | `research/pre_phase13_cert_infra/archimedean_closed_form.md` | none | Arb | N | infrastructure, not new identity |
| 38 | \(G_2^{leak}\) table | NUMERICAL | `research/pre_phase13_cert_infra/G2_table.md` | none | Arb | N | constants only; depends on TAIL.COERCIVITY |
| 39 | \(P_{pt}\)/counting | OPEN | `proof_attempts/pre_phase13_onepoint_lemma.md` | none | no | N | no theorem; must not be cited as proved |
| 40 | SOURCE.BASIC.UNIQUENESS | KNOWN-IN-DIFFERENT-LANGUAGE | `proof_attempts/phase13_first_architectural_lemma.md` | none | no | P | uniqueness relative to all fixed normalizations, not absolute |
| 41 | SOURCE.MATRIXCOEFF.NOGO | NO-GO / KNOWN elementary | `proof_attempts/phase13_matrix_coefficient_nogo.md` | none | no | Y | bare unitary matrix coefficients only |
| 42 | EULER.FREDHOLM.BARRIER | KNOWN-IN-DIFFERENT-LANGUAGE / NO-GO | `proof_attempts/phase14_first_spectralization_lemma.md` | none | no | Y | fixed diagonal prime data only |
| 43 | DIRECT.L2.DESCENT.NOGO | KNOWN-IN-DIFFERENT-LANGUAGE / NO-GO | `proof_attempts/phase15_first_form_lemma.md` | none | no | Y | direct representative form only |
| 44 | CRITICAL.CLOSURE.NOGO | KNOWN-IN-DIFFERENT-LANGUAGE / NO-GO | `proof_attempts/phase16_first_closure_lemma.md` | none | no | P | radial Meyer corollary of Connes \(\delta=0\); assumptions should be restated |
| 45 | JET.CUTOFF.ASYMPTOTICS | NEW-COROLLARY / NOVELTY-UNVERIFIED | `proof_attempts/phase17_first_boundary_lemma.md` | none | no | Y | asymptotics yes; geometric boundary interpretation should remain separate |
| 46 | GLOBAL.CUTOFF.DICHOTOMY | NO-GO / KNOWN logical synthesis | `proof_attempts/phase18_global_cutoff_lemma.md` | none | no | P | positive-cone statement only; ordinary explicit formula unconditional |
| 47 | HALF.DENSITY.RIGIDITY | KNOWN-IN-DIFFERENT-LANGUAGE | `proof_attempts/phase19_first_new_architecture_lemma.md` | none | no | P | fixed-point class audited; not global architecture |
| 48 | ALL.PLACE.LOCALITY | KNOWN elementary | `proof_attempts/phase20_first_assembly_lemma.md` | none | no | Y | compact log-support/local finiteness only |
| 49 | TEMPERED.LOCAL.BOUNDARY | KNOWN-IN-DIFFERENT-LANGUAGE | `proof_attempts/phase21_first_cross_field_lemma.md` | none | no | P | off-zero unitary equivalence; fixed point excluded |
| 50 | FIXEDPOINT.GRAPH.NOGO | NEW-COROLLARY / elementary scoped no-go | `reports/PUBLICATION_AUDIT_I/FIXEDPOINT_NEW_PROOF.md` | none | no | Y | correct for finite bounded graph augmentations; closure of this restriction only; low novelty |
| 51 | RIGGING tradeoff package | KNOWN / KNOWN-IN-DIFFERENT-LANGUAGE plus architectural observations | `reports/PUBLICATION_AUDIT_I/RIGGING_PRECISE_STATEMENT.md` | none | no | P | not one no-go theorem: threshold, covariance, and point restriction are known; order selection and missing fingerprint are scoped observations |
| 52 | TRACE.WEIGHT.NONFORCING | NO-GO / KNOWN elementary | `proof_attempts/phase24_trace_native_theorem.md` | none | no | Y | bare trace/KMS positivity plus duality only |
| 53 | DUALITY.ONLY | KNOWN-IN-DIFFERENT-LANGUAGE / NEW-COROLLARY | `proof_attempts/phase25_polarization_theorem.md` | none | no | P | scoped to Meyer/CCM candidates, not universal nonexistence |
| 54 | FINITE.PRIME.ENTIRE.NOGO | NO-GO / KNOWN elementary | `proof_attempts/reset2_first_zero_confinement_theorem.md` | none | no | Y | exact Euler insertion plus one fixed meromorphic completion |

## Audit totals and policy

- Explicitly numerical artifacts: 36–38, plus numerical thresholds supporting
  21–25.
- Explicitly open indexed item: 39.
- Serious novelty-unverified analytic candidates: 20–22, 34, 45, 50, 51.
- No indexed theorem proves RH or assumes RH.
- Before publication, every `POSSIBLY-NEW`, `NEW-COROLLARY`, or numerical
  item needs an independent proof pass and a primary-literature novelty pass.
