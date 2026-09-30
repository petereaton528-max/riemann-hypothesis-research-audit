# PROOF_INDEX

Archival index of retained named results. Proofs are **not**
reconstructed here. Paths are relative to the repository root.

Novelty against primary literature is **unchecked** unless a
novelty-audit file is cited. Independent re-audit means a later
project pass restated or used the lemma without rewriting the
proof. **Paper use:** almost every `PROVED-IN-PROJECT` item
requires another verification pass before publication.

Does not modify Phase 0–12 conclusions. Phase 13–16 entries appended below
and Phase 17–19 entries below record later explicitly authorized work.

---

## 1. Lemma 7.G(a)

- **Statement.** At fixed \(\lambda>1\), Galerkin eigenvalues of
  \(A_\lambda^N\) converge to those of \(A_\lambda\) as
  \(N\to\infty\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/phase7_first_convergence_lemma.md`
- **Support.** `research/phase7_proved_vs_open.md`, `research/PHASE7_MISSING_THEOREM.md`
- **Numerical deps.** none
- **Prereqs.** CCM compact resolvent (Thm 3.6), min-max
- **Re-audited.** used in pre-13J/K; proof not rewritten
- **Novelty check.** no dedicated literature search file
- **Paper use.** requires another verification pass

## 2. Lemma 7.G(b)

- **Statement.** If the ground eigenvalue of \(A_\lambda\) is
  simple, the Galerkin ground eigenvector and its Fourier
  transform converge (implication only).
- **Status.** PROVED-IN-PROJECT (implication); simplicity OPEN (T1)
- **Proof.** `proof_attempts/phase7_first_convergence_lemma.md`
- **Support.** `research/phase7_proved_vs_open.md`
- **Numerical deps.** none
- **Prereqs.** 7.G(a); simplicity hypothesis
- **Re-audited.** no
- **Novelty check.** no
- **Paper use.** requires verification; do not state without T1

## 3. Lemma 8.J

- **Statement.** (i) \(\|k_\lambda\|\to\|k\|\in(0,\infty)\).
  (ii) \(Q_{0,2}(k_\lambda)=O(\lambda)\|k_\lambda\|^2\) and
  \(Q_{\mathrm{fin}}(k_\lambda)=O(\lambda)\|k_\lambda\|^2\).
  (iii) \(Q_\infty(k_\lambda)\ge -C_\infty\|k_\lambda\|^2\).
- **Status.** PROVED-IN-PROJECT (i)–(iii); decaying \(r_\lambda\) FAILED
- **Proof.** `proof_attempts/phase8_first_gap_or_residual_lemma.md`
- **Support.** `research/phase8_k_lambda.md`, `research/PHASE8_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** CCM (7.1), (7.6); Chebyshev
- **Re-audited.** no
- **Novelty check.** no
- **Paper use.** requires another verification pass

## 4. Lemmas 8.V / 8.D / 8.L2

- **Statement.** Defect identities as tagged in the proof file
  (windowed \(k\) vs \(k_\lambda\); finite \(\mathcal{E}\) sum).
- **Status.** PROVED-IN-PROJECT; 8.R and 8.T FAILED
- **Proof.** `proof_attempts/phase8_rayleigh_defect.md`
- **Support.** `research/phase8_rayleigh_defect.md`, `research/PHASE8_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** CCM Lemma 7.2 / (7.6)
- **Re-audited.** used in Phase 11–12
- **Novelty check.** no
- **Paper use.** requires another verification pass

## 5. Lemma 9.K

- **Statement.** Truncated Mellin kernels \(e_z\) for
  \(\lvert\operatorname{Im}z\rvert<1/2\) lie in the form domain
  of \(QW_\lambda\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/phase9_kernel_and_normality.md`
- **Support.** `research/phase9_Mellin_kernel_testing.md`
- **Numerical deps.** none
- **Prereqs.** BV + \(O(1/t)\) Fourier of the window
- **Re-audited.** used by DC.NOGO
- **Novelty check.** no
- **Paper use.** requires another verification pass

## 6. Lemma 9.W

- **Statement.** Under T1,
  \(QW_\lambda(\xi_\lambda,e_z)=\mu_\lambda\widehat{\xi}_\lambda(z)\).
- **Status.** PROVED-IN-PROJECT (tautological given 9.K and T1)
- **Proof.** `proof_attempts/phase9_kernel_and_normality.md`
- **Support.** `research/PHASE9_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** 9.K, T1
- **Re-audited.** no
- **Novelty check.** no
- **Paper use.** requires T1 hypothesis; verification pass

## 7. Lemma 9.P

- **Statement.** \(K_\lambda\to F\) as an implication of CCM
  Lemma 7.3.
- **Status.** PROVED-IN-PROJECT (implication / KNOWN RESULT RECAST)
- **Proof.** `proof_attempts/phase9_kernel_and_normality.md`
- **Support.** `research/phase9_projective_normalization.md`
- **Numerical deps.** none
- **Prereqs.** CCM Lemma 7.3
- **Re-audited.** no
- **Novelty check.** recast of CCM 7.3
- **Paper use.** cite CCM; project write-up needs verification

## 8. Phase 9 reduction identity

- **Statement.** Oscillatory bound FAILED; a reduction identity
  for the transform error is proved in the same file.
- **Status.** PROVED-IN-PROJECT (identity only)
- **Proof.** `proof_attempts/phase9_direct_transform_estimate.md`
- **Support.** `research/phase9_exact_transform_error.md`
- **Numerical deps.** none
- **Prereqs.** —
- **Re-audited.** no
- **Novelty check.** no
- **Paper use.** requires another verification pass

## 9. Lemma L9

- **Statement.** Rewrite of \(\Delta_\lambda\) as tagged in the
  proof file.
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/phase9_lemma_L9.md`
- **Support.** `research/PHASE9_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** —
- **Re-audited.** no
- **Novelty check.** no
- **Paper use.** requires another verification pass

## 10. Lemma L10 (abstract cluster \(\sin\Theta\))

- **Statement.** Abstract Davis–Kahan / cluster \(\sin\Theta\)
  transfer. Weil application OPEN.
- **Status.** PROVED-IN-PROJECT (abstract); Weil application OPEN
- **Proof.** `proof_attempts/phase10_transfer_lemma_L10.md`
- **Support.** `research/PHASE10_RESULT.md`, `research/phase10_low_energy_subspace.md`
- **Numerical deps.** none
- **Prereqs.** standard subspace perturbation
- **Re-audited.** no
- **Novelty check.** likely KNOWN RESULT RECAST of Davis–Kahan;
  novelty unverified
- **Paper use.** requires novelty check + verification pass

## 11. Lemma L11.5

- **Statement.** \(QW_\lambda(k^w,k^w)=O(\lambda e^{-c\lambda^2})\to 0\)
  for \(k^w=k\cdot 1_{[\lambda^{-1},\lambda]}\), \(k=\mathcal{E}(h)\)
  CCM (7.1).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/phase11_lemma_L11.md`
- **Support.** `research/phase11_signed_windowing.md`, `research/PHASE11_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** \(QW(k)=0\); Gaussian tails; Lemmas 11.2–11.5 in
  the support file
- **Re-audited.** restated in Phase 12
- **Novelty check.** no dedicated file
- **Paper use.** requires another verification pass

## 12. L11-SPLIT

- **Statement.**
  \(QW(k_\lambda)=QW(k^w)+2\operatorname{Re}QW(k^w,e_\lambda)+QW(e_\lambda)\)
  with \(e_\lambda=\mathcal{E}(h_\lambda-h)|_{\mathrm{window}}\).
- **Status.** PROVED-IN-PROJECT (algebraic split)
- **Proof.** `proof_attempts/phase11_lemma_L11.md`
- **Support.** `research/PHASE11_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** definitions of \(k^w\), \(e_\lambda\)
- **Re-audited.** used in Phase 12
- **Novelty check.** tautological
- **Paper use.** as-is as an identity; still verify notation

## 13. Lemma 12.D1

- **Statement.** \(Q_\infty(k^w,e_\lambda)=O(\lambda^{-1/2})\to 0\).
- **Status.** NEW COROLLARY (also tagged PROVED-IN-PROJECT)
- **Proof.** `proof_attempts/phase12_archimedean_transfer.md`,
  `proof_attempts/phase12_main_lemma.md`
- **Support.** `research/PHASE12_RESULT.md`,
  `research/phase12_archimedean_form_topology.md`,
  `research/phase12_novelty_audit.md`
- **Numerical deps.** none
- **Prereqs.** CCM \(C^0\) / Lemmas 7.2–7.3; decay of \(\Xi\)
- **Re-audited.** novelty audit in `research/phase12_novelty_audit.md`
- **Novelty check.** yes, against CCM/CC, PSWF, Weil-positivity
  papers as listed in that file
- **Paper use.** closest to paper-ready among project corollaries;
  still requires an independent verification pass

## 14. Lemma 12.F1

- **Statement.** \(\lvert Q_{\mathrm{fin}}(k^w,e_\lambda)\rvert=O(1)\),
  improving Phase 11’s \(O(\lambda^{1/2})\); not \(o(1)\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/phase12_prime_cross_cancellation.md`
- **Support.** `research/phase12_prime_cross_exact.md`,
  `research/phase12_novelty_audit.md`
- **Numerical deps.** none
- **Prereqs.** CCM Lemma 7.2; 8.L2; Chebyshev
- **Re-audited.** novelty comment in `phase12_novelty_audit.md`
- **Novelty check.** partial (same file as 12.D1)
- **Paper use.** requires another verification pass

## 15. Lemma 12.P1

- **Statement.** Polar values of \(e_\lambda\) tend to \(0\)
  (vanishing-integral identity).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/phase12_archimedean_transfer.md`
  (recorded in `research/PHASE12_RESULT.md`)
- **Support.** `research/PHASE12_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** vanishing-integral of the defect
- **Re-audited.** no separate re-proof
- **Novelty check.** no
- **Paper use.** requires another verification pass

## 16. Lemma 12.H2

- **Statement.** \(C^1\) of \(h_{n,\lambda}-h_n\) on compact
  sets, rate \(O(\lambda^{-2})\), \(n=0,4\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** recorded in `research/PHASE12_RESULT.md`;
  supporting `research/phase12_pswf_asymptotic_audit.md`,
  `research/phase12_modes_0_4.md`
- **Support.** `proof_attempts/phase12_main_lemma.md` (notes L12-A
  only compact)
- **Numerical deps.** none
- **Prereqs.** PSWF / Hermite literature as cited in the audit
- **Re-audited.** no
- **Novelty check.** `research/phase12_novelty_audit.md` (PSWF
  ingredients not a new PSWF theorem)
- **Paper use.** requires another verification pass; may be
  KNOWN RESULT RECAST of PSWF expansions

## 17. Lemmas 12.C1–C2

- **Statement.** Continuity of \(Q_\infty\) in \(N_\infty\), and
  the mixed estimate for a Schwartz partner.
- **Status.** PROVED-IN-PROJECT
- **Proof.** recorded in `research/PHASE12_RESULT.md`;
  `research/phase12_archimedean_form_topology.md`
- **Support.** `proof_attempts/phase12_archimedean_transfer.md`
- **Numerical deps.** none
- **Prereqs.** definition of \(N_\infty\)
- **Re-audited.** no
- **Novelty check.** no
- **Paper use.** requires another verification pass

## 18. GAL.HM

- **Statement.** Fixed \(\lambda>1\),
  \(QW_\lambda(V_n,V_n)=\log\lvert n\rvert+O_\lambda(1)\to+\infty\).
  Same for fixed-width packets.
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/pre_phase13_galerkin_uv_lemma.md`
- **Support.** `research/pre_phase13_galerkin_uv/high_mode_asymptotics.md`,
  `research/pre_phase13_galerkin_uv/AUDIT_RESULT.md`
- **Numerical deps.** none for the lemma
- **Prereqs.** CCM (3.24), (4.2); finite prime sum at fixed \(\lambda\)
- **Re-audited.** used in 13K TAIL.COERCIVITY
- **Novelty check.** no dedicated literature file; likely recast
  of CCM multiplier asymptotics
- **Paper use.** requires novelty check + verification pass

## 19. GAL.UV

- **Statement.** UV-occupied Galerkin grounds cannot persist as
  \(N\to\infty\) at fixed \(\lambda\).
- **Status.** PROVED-IN-PROJECT (corollary of GAL.HM)
- **Proof.** `proof_attempts/pre_phase13_galerkin_uv_lemma.md`
- **Support.** `research/pre_phase13_galerkin_uv/AUDIT_RESULT.md`
- **Numerical deps.** 13J experiments motivated the lemma; proof
  does not use those numbers
- **Prereqs.** GAL.HM
- **Re-audited.** 13K corrected the 13J UV *numerics* (quadrature
  artifact); the lemma itself stands
- **Novelty check.** no
- **Paper use.** requires another verification pass

## 20. TAIL.COERCIVITY

- **Statement.** On \(H_{\mathrm{high}}(M)\),
  \(QW_\lambda(f,f)\ge G_\lambda(M)\|f\|^2\) with
  \(G_\lambda(M)\to+\infty\). Hence \(A_{HH}-E\) invertible for
  \(G_\lambda(M)>E\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/pre_phase13_continuum_recovery_lemma.md`
- **Support.** `research/pre_phase13_continuum_recovery/tail_coercivity.md`,
  `research/pre_phase13_continuum_recovery/AUDIT_RESULT.md`
- **Numerical deps.** none for existence of \(G_\lambda\); quantitative
  \(G_2(M)\) is separate (13M)
- **Prereqs.** GAL.HM ingredients; discrete Hilbert; polar rank \(\le 2\)
- **Re-audited.** constants sharpened in 13M–P; existence proof
  not rewritten
- **Novelty check.** no
- **Paper use.** requires another verification pass

## 21. WEIGHTED.SCHUR

- **Statement.** \(\lambda=2\), fixed finite low sector \(J\),
  \(G_2^L(M)>E\):
  \(\|B_M(A_{HH}-E)^{-1}B_M^*\|=O_J(1/(M\log M))\to 0\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/pre_phase13_weighted_schur_lemma.md`
- **Support.** `research/pre_phase13_weighted_schur/weighted_coupling.md`,
  `research/pre_phase13_weighted_schur/AUDIT_RESULT.md`,
  `experiments/weighted_schur/certified_tail.md`
- **Numerical deps.** Arb \(a_M\), \(d_n\), entry bounds at \(\lambda=2\)
- **Prereqs.** TAIL.COERCIVITY; \(|A_{jn}|\le C_J/\lvert n\rvert\)
- **Re-audited.** no second proof
- **Novelty check.** no
- **Paper use.** requires another verification pass; \(\lambda=2\) only

## 22. LOWRANK.TAIL

- **Statement.** For \(T_M=BY^{-1}B^*\) at \(\lambda=2\), fixed \(J\),
  \(T_M\) is explicit finite-rank at order \(1/n\) plus
  \(O_J(1/(M^2\log M))\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/pre_phase13_lowrank_tail_lemma.md`
- **Support.** `research/pre_phase13_lowrank_tail/entry_expansion.md`,
  `research/pre_phase13_lowrank_tail/schur_expansion.md`,
  `research/pre_phase13_lowrank_tail/AUDIT_RESULT.md`,
  `experiments/lowrank_tail/certified_expansion.md`
- **Numerical deps.** Arb expansion check; not a substitute for
  the analytic remainder
- **Prereqs.** CCM (4.2)–(4.4); \(q(\log 2)=q(2\log 2)=0\) off-diagonal
  at integer indices
- **Re-audited.** no
- **Novelty check.** no
- **Paper use.** requires another verification pass; \(\lambda=2\) only

## 23. K.FIN.OFF

- **Statement.** High-high finite off-diagonal at \(\lambda=2\) is
  only the atom \(k=3\);
  \(\|A^{\mathrm{fin}}_{\mathrm{off}}\|\le 2\log 3/\sqrt 3\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/pre_phase13_exact_resolvent_lemma.md`
- **Support.** `research/pre_phase13_exact_resolvent/relative_prime.md`,
  `experiments/exact_resolvent/results/a_M.json`
- **Numerical deps.** Arb numerical value of the elementary bound
- **Prereqs.** \(L=2\log 2\); integer Fourier indices
- **Re-audited.** no
- **Novelty check.** no (elementary)
- **Paper use.** requires another verification pass; \(\lambda=2\) only

## 24. POLAR.WOODBURY

- **Statement.** \(D_E+P\) with rank-\(\le 2\) polar inverted by
  Woodbury; at \(M\ge 128\),
  \(\|D_E^{-1/2}PD_E^{-1/2}\|=O(10^{-4})\).
- **Status.** PROVED-IN-PROJECT (identity + certified Grams)
- **Proof.** `proof_attempts/pre_phase13_exact_resolvent_lemma.md`
- **Support.** `research/pre_phase13_exact_resolvent/polar_woodbury.md`,
  `experiments/exact_resolvent/results/woodbury_grams.json`
- **Numerical deps.** Arb Gram sums
- **Prereqs.** CCM (4.2)
- **Re-audited.** no
- **Novelty check.** Woodbury is KNOWN; application is project-internal
- **Paper use.** requires another verification pass

## 25. NEUMANN.HIGH

- **Statement.** If \(a_M=\kappa_K(M)/d_{M+1}<1\), then
  \((A_{HH}-E)^{-1}=R_0^{1/2}(I+R_M)^{-1}R_0^{1/2}\) with
  \(\|R_M\|\le a_M\) and Neumann remainder
  \(\le a_M^{q+1}/(1-a_M)\). Certified \(a_M<1\) for \(M\ge 128\)
  at \(\lambda=2\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/pre_phase13_exact_resolvent_lemma.md`
- **Support.** `research/pre_phase13_exact_resolvent/neumann_resolvent.md`,
  `experiments/exact_resolvent/results/a_M.json`,
  `experiments/exact_resolvent/results/neumann.json`
- **Numerical deps.** Arb \(a_M\)
- **Prereqs.** K.FIN.OFF; POLAR.WOODBURY
- **Re-audited.** no
- **Novelty check.** Neumann is KNOWN; \(a_M\) table is
  COMPUTER-ASSISTED
- **Paper use.** requires another verification pass

## 26. MAT.ATOM

- **Statement.** Finite-place Galerkin matrix is the atomic
  Loewner sum at \(\log n\); not Toeplitz / multiplier / banded.
  Ground-selection theorems FAILED.
- **Status.** PROVED-IN-PROJECT (structure); selection FAILED
- **Proof.** `proof_attempts/pre_phase13_matrix_rigidity_lemma.md`
- **Support.** `research/pre_phase13_matrix_anatomy/exact_matrix.md`,
  `research/pre_phase13_matrix_anatomy/AUDIT_RESULT.md`
- **Numerical deps.** `experiments/pre_phase13_matrix_structure.md`
  (polar+prime only; Archimedean omitted there)
- **Prereqs.** CCM (2.9)–(4.3)
- **Re-audited.** no
- **Novelty check.** recast of CCM atomic Loewner
- **Paper use.** structure part may be KNOWN RESULT RECAST;
  verification pass required

## 27. COM.E

- **Statement.** Euler intertwining through \(\mathcal{E}\).
- **Status.** PROVED-IN-PROJECT
- **Proof.** `proof_attempts/pre_phase13_commutator_lemma.md`
- **Support.** `research/pre_phase13_commutator/E_intertwining.md`,
  `research/pre_phase13_commutator/AUDIT_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** \(\mathcal{E}\)
- **Re-audited.** no
- **Novelty check.** no; likely KNOWN RESULT RECAST of the
  Sonin/\(\mathcal{E}\) dictionary
- **Paper use.** requires novelty check + verification pass

## 28. COM.NOGO

- **Statement.** Slepian pair does not transfer to \(A_\lambda\).
- **Status.** NO-GO
- **Proof.** `proof_attempts/pre_phase13_commutator_lemma.md`
- **Support.** `research/pre_phase13_commutator/AUDIT_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** COM.E
- **Re-audited.** no
- **Novelty check.** n/a (negative)
- **Paper use.** as a project no-go after verification; not a
  literature theorem

## 29. DR.RAD

- **Statement.** The global \(\mathcal{E}\)-radical on
  \(\mathcal{S}_0^{\mathrm{ev}}\) and the associated splitting
  as tagged in the proof file.
- **Status.** PROVED-IN-PROJECT / KNOWN RESULT RECAST of the
  source radical
- **Proof.** `proof_attempts/pre_phase13_degenerate_radical_lemma.md`
- **Support.** `research/pre_phase13_degenerate_radical/global_radical.md`,
  `research/phase11_global_E_radical.md`
- **Numerical deps.** none
- **Prereqs.** source \(\mathcal{E}\)-radical theorem
- **Re-audited.** Phase 11 then 13D
- **Novelty check.** source THEOREM recast
- **Paper use.** cite source; project write-up needs verification

## 30. DR.NOGO

- **Statement.** Global transverse positivity modulo the
  \(\mathcal{E}\)-radical is Weil positivity.
- **Status.** NO-GO
- **Proof.** `proof_attempts/pre_phase13_degenerate_radical_lemma.md`
- **Support.** `research/pre_phase13_degenerate_radical/no_go_audit.md`,
  `research/pre_phase13_degenerate_radical/AUDIT_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** DR.RAD; Weil form
- **Re-audited.** no
- **Novelty check.** n/a
- **Paper use.** project no-go after verification

## 31. DC.NOGO

- **Statement.** Dual-certificate remainder on \(\xi_\lambda\)
  equals \(\widehat{\Psi}_\lambda(z)\); infimal Hilbert distance
  to \(\operatorname{ran}(A-\mu)\) is \(\lvert L(\xi_\lambda)\rvert\).
- **Status.** NO-GO
- **Proof.** `proof_attempts/pre_phase13_dual_certificate_lemma.md`
- **Support.** `research/pre_phase13_dual_certificate/AUDIT_RESULT.md`,
  `research/pre_phase13_dual_certificate/tautology_audit.md`
- **Numerical deps.** none
- **Prereqs.** 9.K
- **Re-audited.** no
- **Novelty check.** n/a
- **Paper use.** project no-go after verification

## 32. LD.INT

- **Statement.** Abstract implication relating a log-derivative
  / spectral-measure hypothesis to a conclusion as tagged in
  the proof file.
- **Status.** PROVED-IN-PROJECT (implication only)
- **Proof.** `proof_attempts/pre_phase13_logderivative_lemma.md`
- **Support.** `research/pre_phase13_logderivative/minimal_theorem.md`
- **Numerical deps.** none
- **Prereqs.** —
- **Re-audited.** no
- **Novelty check.** no
- **Paper use.** requires another verification pass; hypothesis
  not discharged

## 33. LD.NOGO

- **Statement.** The regularized resolvent trace / log
  derivative of \(\det_{\mathrm{reg}}(D_{\log}^{(\lambda,N)}-z)\)
  is not independent of \(\xi\).
- **Status.** NO-GO
- **Proof.** `proof_attempts/pre_phase13_logderivative_lemma.md`
- **Support.** `research/pre_phase13_logderivative/tautology_audit.md`,
  `research/pre_phase13_logderivative/AUDIT_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** CCM Theorem 5.10(ii)
- **Re-audited.** no
- **Novelty check.** n/a
- **Paper use.** project no-go after verification

## 34. IDENTIFIABILITY.NOGO

- **Statement.** T1 + Paley–Wiener type \(\le\log\lambda\) +
  evenness + real zeros + real-on-real + anchor
  \(F(z_*)=1\) do not imply \(T_{\mathrm{HOL}}\). CvS-class
  even-simple matrices do not determine a unique projective
  ground transform tending to \(\Xi/\Xi(z_*)\).
- **Status.** NO-GO
- **Proof.** `proof_attempts/pre_phase13_identifiability_nogo.md`
- **Support.** `research/pre_phase13_identifiability/analytic_countermodels.md`,
  `research/pre_phase13_identifiability/operator_countermodels.md`,
  `research/pre_phase13_identifiability/AUDIT_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** T1 as a *hypothesis* in \(C^{\mathrm{an}}\); sine model
- **Re-audited.** no
- **Novelty check.** no dedicated literature search; sine-type
  models are classical
- **Paper use.** requires novelty check + verification pass

## 35. CANONICAL.NOGO

- **Statement.** Realizations of \(\widehat{\xi}_\lambda\) as
  canonical systems / de Branges spaces are xi-derived or
  require RH-level positivity. Not an advance toward
  \(N_\lambda(R)=O_R(1)\).
- **Status.** NO-GO
- **Proof.** `proof_attempts/pre_phase13_canonical_system_candidate.md`
- **Support.** `research/pre_phase13_canonical_systems/inverse_tautology.md`,
  `research/pre_phase13_canonical_systems/AUDIT_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** —
- **Re-audited.** no
- **Novelty check.** no
- **Paper use.** project no-go after verification

## 36. Compression inertia of \(A_8\) at \(\lambda=2\)

- **Statement.** Interval LDL of the certified compression
  \(A_8\): exactly one Galerkin eigenvalue in
  \((2.75\cdot 10^{-12},1.2\cdot 10^{-9}]\). Not continuum.
- **Status.** COMPUTER-ASSISTED (also NEW COROLLARY of CCM
  matrix formulae)
- **Proof.** `research/pre_phase13_cert_infra/inertia.md`
- **Support.** `research/pre_phase13_cert_infra/AUDIT_RESULT.md`,
  `experiments/cert_infra/compute_infra.py`,
  `experiments/cert_infra/g2_sharp.py`,
  `experiments/cert_infra/results/inertia_compression.json`,
  `experiments/cert_infra/results/inertia_M8_tight.json`
- **Numerical deps.** python-flint / Arb 256-bit balls of \(A_{jk}\)
- **Prereqs.** Arb \(W_{\mathbb{R}}\) path (13M); polar (4.2);
  finite atoms \(n=2,3,4\)
- **Re-audited.** no second stack
- **Novelty check.** CCM did not publish this interval count
- **Paper use.** requires independent interval reproduction;
  label as compression not continuum

## 37. Arb enclosures of \(W_{\mathbb{R}}\) at \(\lambda=2\)

- **Statement.** CCM (4.4) via Prop. 4.2 + elementary
  \(I_{\mathrm{elem}}\) evaluated in Arb; nested 128/256/512-bit
  balls; mpmath dps 80/160 lie inside.
- **Status.** COMPUTER-ASSISTED (formulae KNOWN RESULT RECAST)
- **Proof / algorithm.** `research/pre_phase13_cert_infra/archimedean_closed_form.md`,
  `research/pre_phase13_cert_infra/archimedean_interval_algorithm.md`
- **Support.** `experiments/cert_infra/balls.py`,
  `experiments/cert_infra/interval_matrix.md`,
  `experiments/cert_infra/crosscheck.md`,
  `experiments/cert_infra/results/entries.json`,
  `experiments/cert_infra/results/crosscheck.json`
- **Numerical deps.** python-flint 0.9.0
- **Prereqs.** CCM Prop. 4.2–4.3, (4.4)
- **Re-audited.** cross-check vs mpmath; SF vs 64-bit integral
- **Novelty check.** evaluation infrastructure, not a new identity
- **Paper use.** requires independent Arb reproduction

## 38. \(G_2^{\mathrm{leak}}(M)\) table

- **Statement.** Unconditional leakage \(G_2^{\mathrm{leak}}(512)\approx 0.246>0\)
  at \(\lambda=2\), with tabulated values for listed \(M\).
- **Status.** COMPUTER-ASSISTED (constants for TAIL.COERCIVITY)
- **Proof.** existence in TAIL.COERCIVITY; numbers in
  `research/pre_phase13_cert_infra/G2_table.md`
- **Support.** `experiments/cert_infra/g2_sharp.py`,
  `experiments/cert_infra/results/g2.json`
- **Numerical deps.** Arb \(\theta'\), \(F_2\), polar tail
- **Prereqs.** TAIL.COERCIVITY
- **Re-audited.** no
- **Novelty check.** n/a
- **Paper use.** requires independent Arb reproduction

## 39. P_pt / \(N_\lambda(R)=O_R(1)\)

- **Statement.** One-point growth / compact counting bound
  intended to kill IDENTIFIABILITY.NOGO sine models.
- **Status.** OPEN (not proved); identities in the proof file
  are not a proof of \(P_{\mathrm{pt}}\)
- **Proof attempt.** `proof_attempts/pre_phase13_onepoint_lemma.md`
- **Support.** `research/pre_phase13_onepoint/AUDIT_RESULT.md`
- **Numerical deps.** none
- **Prereqs.** IDENTIFIABILITY.NOGO
- **Re-audited.** no
- **Novelty check.** n/a
- **Paper use.** **not suitable**; OPEN

## 40. SOURCE.BASIC.UNIQUENESS

- **Statement.** With the standard global additive character and self-dual
  measures fixed, the finite local support/Fourier-support conditions select
  \(\mathbf 1_{\mathbb Z_p}\); the normalized Archimedean oscillator-ground
  condition selects \(e^{-\pi x^2}\); the normalized restricted tensor
  product is the standard Tate vector \(\Phi_0\).
- **Status.** KNOWN IN DIFFERENT LANGUAGE; proof recorded in project;
  no genuinely new lemma claimed
- **Proof.** `proof_attempts/phase13_first_architectural_lemma.md`
- **Support.** `research/phase13/source_rigidity.md`,
  `research/phase13/SELECTION_FINGERPRINT.md`
- **Numerical deps.** none
- **Prereqs.** self-dual local Fourier theory; harmonic-oscillator ground
  state; restricted tensor products
- **Novelty check.** standard local facts assembled for the project;
  novelty-unverified as an assembled label
- **Paper use.** cite standard local results; independently verify the
  normalization and tensor-product statement

## 41. SOURCE.MATRIXCOEFF.NOGO

- **Statement.** A canonical vector and its unitary matrix coefficient
  determine a positive spectral measure, but zeros of the scalar
  Mellin/Fourier transform are not thereby eigenvalues, resonances, or
  spectral points.
- **Status.** NO-GO / PROVED-IN-PROJECT; elementary spectral-theorem
  corollary; no novelty claim
- **Proof.** `proof_attempts/phase13_matrix_coefficient_nogo.md`
- **Support.** `research/phase13/scaling_spectral_measure.md`,
  `research/phase13/spectralization_requirements.md`
- **Numerical deps.** none
- **Prereqs.** Stone's theorem; spectral theorem; Fourier inversion
- **Novelty check.** KNOWN IN DIFFERENT LANGUAGE
- **Paper use.** project no-go after verification; not a new literature
  theorem

## 42. EULER.FREDHOLM.BARRIER

- **Statement.** The diagonal prime operator
  \(K(s)e_p=p^{-s}e_p\) is trace class exactly for \(\Re s>1\), where
  \(\det(I-K(s))=\zeta(s)^{-1}\); the same diagonal family has no
  trace-class-valued analytic continuation through \(\Re s\le1\) preserving
  those matrix coefficients.
- **Status.** PROVED-IN-PROJECT / KNOWN IN DIFFERENT LANGUAGE; no novelty
  claim
- **Proof.** `proof_attempts/phase14_first_spectralization_lemma.md`
- **Support.** `research/phase14/PRIME_POWER_DETERMINANT.md`,
  `research/phase14/perturbation_determinant.md`
- **Numerical deps.** none
- **Prereqs.** divergence of \(\sum_p1/p\); trace-class determinants;
  analytic identity theorem
- **Novelty check.** standard convergence boundary plus elementary
  corollary
- **Paper use.** requires verification; do not present as a new theorem

## 43. DIRECT.L2.DESCENT.NOGO

- **Statement.** A positive-definite Hermitian form on \(E\) cannot descend
  unchanged by representatives to \(E/N\) for \(N\ne0\). In particular,
  the natural \(L^2(\mathbb R_+,dx)\) form does not descend directly to
  Meyer's \(\mathcal H_-^0=\mathcal H_-/Z\mathcal H_\cap\).
- **Status.** PROVED-IN-PROJECT / KNOWN IN DIFFERENT LANGUAGE; elementary
  no-go; no novelty claim
- **Proof.** `proof_attempts/phase15_first_form_lemma.md`
- **Support.** `research/phase15/L2_descent.md`,
  `research/phase15/unitary_completion.md`
- **Numerical deps.** none
- **Prereqs.** positive-definite quotient-form linear algebra; Meyer's
  injectivity of \(Z\)
- **Novelty check.** standard quotient-form argument
- **Paper use.** project no-go after verification

## 44. CRITICAL.CLOSURE.NOGO

- **Statement.**
  \[
  \overline{Z\mathcal H_\cap}^{\,L^2(\mathbb R_+,dx)}
  =L^2(\mathbb R_+,dx).
  \]
  Hence the fixed critical Hilbert quotient and orthogonal complement are
  zero, and no Meyer evaluation jet has a nonzero Riesz representative
  there.
- **Status.** KNOWN IN DIFFERENT LANGUAGE from Connes's \(\delta=0\)
  surjectivity theorem; radial Meyer formulation is
  NEW COROLLARY / NOVELTY-UNVERIFIED; no novelty claim
- **Proof.** `proof_attempts/phase16_first_closure_lemma.md`
- **Support.** `research/phase16/critical_closure.md`,
  `research/phase16/evaluation_continuity.md`,
  `research/phase16/annihilator_filter.md`,
  `research/phase16/connes_comparison.md`
- **Numerical deps.** none
- **Prereqs.** Connes \(\delta=0\) surjectivity; Meyer space dictionary;
  half-density Mellin–Plancherel transform
- **Re-audited.** Phase 16 only; no independent second proof stack
- **Novelty check.** primary-source audit recorded in Phase 16; radial
  corollary not claimed new
- **Paper use.** requires independent verification of the radial/adelic
  identification

## 45. JET.CUTOFF.ASYMPTOTICS

- **Statement.** For the \(j\)-th Mellin evaluation jet at
  \(s=\tfrac12+\alpha+i\gamma\), restricted to the logarithmic source
  window \([-T,T]\), the Riesz norm is
  \[
  \sqrt{\frac{2}{2j+1}}T^{j+1/2}\quad(\alpha=0),
  \qquad
  \frac{e^{|\alpha|T}T^j}{\sqrt{2|\alpha|}}
  (1+O_{\alpha,j}(T^{-1}))\quad(\alpha\ne0).
  \]
  No zero-independent scalar renormalization gives finite nonzero norms
  simultaneously on and off the critical line.
- **Status.** PROVED-IN-PROJECT / ELEMENTARY SOURCE-DERIVED COROLLARY;
  novelty unchecked; no novelty claim
- **Proof.** proof_attempts/phase17_first_boundary_lemma.md
- **Support.** research/phase17/rigged_space.md,
  research/phase17/jet_boundary_asymptotics.md,
  research/phase17/critical_vs_resonant.md
- **Numerical deps.** none
- **Prereqs.** source logarithmic cutoff; half-density Mellin dictionary;
  elementary Laplace endpoint asymptotics
- **Re-audited.** Phase 17 only
- **Novelty check.** none
- **Paper use.** requires independent verification and literature audit;
  it is not a line-forcing theorem

---

## 46. GLOBAL.CUTOFF.DICHOTOMY

- **Statement.** Harmonic-measure convergence of Connes's positive cutoff
  defects is compatible with off-line zeros and does not imply RH.
  Conversely, convergence to the direct-evaluation Weil form merely on
  the admissible positive cone \(g*g^*\) implies Weil positivity and hence
  RH.
- **Status.** PROVED-IN-PROJECT / LOGICAL NO-GO; assembled from known
  source theorems; no novelty claim
- **Proof.** proof_attempts/phase18_global_cutoff_lemma.md
- **Support.** research/phase18/offline_zero_effect.md,
  research/phase18/convergence_implies_RH.md,
  research/phase18/weil_interface.md,
  research/phase18/identity_vs_positivity.md
- **Numerical deps.** none
- **Prereqs.** Connes finite-cutoff positivity and harmonic-measure lemma;
  Weil positivity criterion
- **Re-audited.** Phase 18 only
- **Novelty check.** none
- **Paper use.** logical audit result; requires independent verification
  of conventions before citation

---

## 47. HALF.DENSITY.RIGIDITY

- **Statement.** For local dilation pullbacks
  \((U_{a,\beta}f)(x)=|a|^\beta f(ax)\), unitarity uniquely selects
  \(\beta=1/2\). At \(a=p^{\pm m}\), equality of forward and reverse
  flat traces selects the same exponent and both traces equal
  \(p^{-m/2}\). Multiplication by \(\log p\) gives the locked
  prime-power amplitude.
- **Status.** PROVED-IN-PROJECT / KNOWN IN DIFFERENT LANGUAGE; no RH input;
  no novelty claim
- **Proof.** `proof_attempts/phase19_first_new_architecture_lemma.md`
- **Support.** `research/phase19/LOCAL_UNITARIZATION.md`,
  `research/phase19/HALF_DENSITY_CLUE.md`,
  `research/phase19/TRACE_REVERSE_ENGINEERING.md`
- **Numerical deps.** none
- **Prereqs.** local Haar change of variables; distributional fixed-point
  trace for a transverse dilation graph
- **Re-audited.** Phase 20 primary-source comparison
- **Novelty check.** Phase 20: half-modulus unitarity and the fixed-point
  denominator are standard; Connes's symmetric local trace already combines
  them with inversion and normalized place measure
- **Paper use.** expository normalization lemma only; not a standalone new
  result, global spectralization, or RH result

---

## 48. ALL.PLACE.LOCALITY

- **Statement.** On \(\mathcal D(\mathbb R)\), the finite-prime
  half-density distributions form a locally finite sum. As finite prime sets
  increase, their net converges strongly in \(\mathcal D'(\mathbb R)_\beta\),
  indeed by eventual equality on every bounded test family. Adding the real
  principal-value term gives an all-place local distribution.
- **Status.** PROVED-IN-PROJECT / KNOWN ELEMENTARY COROLLARY; no novelty claim
- **Proof.** `proof_attempts/phase20_first_assembly_lemma.md`
- **Support.** `research/phase20/all_place_distribution.md`,
  `research/phase20/prime_tail.md`
- **Numerical deps.** none
- **Prereqs.** compact log support; continuity of the established
  Archimedean principal-value distribution
- **Re-audited.** Phase 20 only
- **Novelty check.** not new; topological formulation of local finiteness of
  the prime-power side
- **Paper use.** not a standalone publication result

---

## 49. TEMPERED.LOCAL.BOUNDARY

- **Statement.** Half-density dilation on a local additive field is unitarily
  equivalent, off the null point zero, to the tempered multiplicative regular
  representation. The additive flat trace is nevertheless supported exactly
  at zero and therefore is not transported to an ordinary character of that
  regular representation. For \(\mathbb Q_p\), the two oriented traces at
  \(p^{\pm m}\) equal \(p^{-m/2}\).
- **Status.** PROVED-IN-PROJECT / KNOWN IN DIFFERENT LANGUAGE; no RH input; no
  novelty claim
- **Proof.** `proof_attempts/phase21_first_cross_field_lemma.md`
- **Support.** `research/phase21/unitary_normalization.md`,
  `research/phase21/temperedness_first.md`,
  `research/phase21/CROSS_FIELD_NO_GO.md`
- **Numerical deps.** none
- **Prereqs.** additive/multiplicative Haar change of variables; regular
  representation temperedness; transverse fixed-point trace
- **Re-audited.** Phase 21 only
- **Novelty check.** standard half-modular normalization plus the known local
  flat trace; the boundary-point mismatch is an elementary corollary
- **Paper use.** expository obstruction lemma only

---

## 50. FIXEDPOINT.GRAPH.NOGO

- **Corrected statement (Publication Audit I).** Point evaluation at zero on
  \(\mathcal S(\mathbb Q_p)\) is not continuous for the joint graph norm of
  any finite family of bounded operators on \(L^2(\mathbb Q_p)\). Its kernel
  is dense in the graph completion. If a bounded self-adjoint \(A\) is
  restricted to that kernel, the restriction is closable and its closure is
  \(A\); hence this specific closed restriction has zero deficiency indices
  and no boundary quotient. This does not exclude restrictions defined by
  unbounded graph norms, atomic measures, or other singular-extension data.
- **Status.** PROVED-IN-PROJECT / NEW-COROLLARY; elementary and low novelty;
  no RH or zero input
- **Proof.** `proof_attempts/phase22_arithmetic_green_no_go.md`
- **Independent audit proof.**
  `reports/PUBLICATION_AUDIT_I/FIXEDPOINT_NEW_PROOF.md`
- **Support.** `research/phase22/FINITE_PLACE_DEFECT.md`,
  `research/phase22/DISTRIBUTIONAL_BOUNDARIES.md`,
  `research/phase22/NOVELTY.md`
- **Numerical deps.** none
- **Prereqs.** graph norms of bounded operators; shrinking p-adic balls;
  graph-continuity hypothesis in singular boundary-triple theory
- **Re-audited.** Publication Quality Audit I
- **Novelty check.** standard abstract mechanism; explicit p-adic
  half-density application is an elementary new corollary, not a standalone
  specialist result
- **Paper use.** scoped lemma in an expository note

---

## 51. RIGGING.TRADEOFF.NOGO

- **Corrected statement (Publication Audit I).** This label denotes a package,
  not one no-go theorem. In the project Bessel scale, evaluation is continuous
  exactly for \(s>1/2\); the full half-density dilation group is unitary in
  the inhomogeneous rigging norm only for \(s=0\) (the unit subgroup is
  unitary for every \(s\)); and for \(\alpha>1/2\) the evaluation-zero
  restriction of \(D^\alpha\) is the known closed symmetric one-point
  restriction with indices \((1,1)\). More abstractly, a nonzero continuous
  evaluation functional transforming by \(|a|_p^{1/2}\) is incompatible with
  unitarity of the full original action. Failure to locate a source-selected
  order and absence of \(\log p\), iterate times, and Gamma data from the
  one-point Green form are architectural observations, not universal theorem
  clauses.
- **Status.** analytic clauses KNOWN / KNOWN-IN-DIFFERENT-LANGUAGE; arithmetic
  comparison NEW-COROLLARY / NOVELTY-UNVERIFIED; no RH or zero input
- **Proof.** `proof_attempts/phase23_canonical_rigging_theorem.md`
- **Independent audit.** `reports/PUBLICATION_AUDIT_I/RIGGING_PRECISE_STATEMENT.md`,
  `POINT_THRESHOLD_PROOF.md`, `SCALING_AUDIT.md`, and
  `POINT_INTERACTION_LITERATURE.md`
- **Support.** `research/phase23/POINT_EVALUATION.md`,
  `research/phase23/POINT_DEFECT_RELATION.md`,
  `research/phase23/RIGGING_TRADEOFF.md`, `research/phase23/NOVELTY.md`
- **Numerical deps.** none
- **Prereqs.** p-adic Fourier shell decomposition; Vladimirov point
  interactions; half-density scaling covariance
- **Re-audited.** Publication Quality Audit I
- **Novelty check.** point-interaction content is explicitly in
  Kuzhel--Torba and Albeverio--Kuzhel--Torba; remaining synthesis is not an
  independently novel operator-theory theorem
- **Paper use.** background and scoped comparison in an expository note

---

## 52. TRACE.WEIGHT.NONFORCING

- **Statement.** A faithful positive finite/semifinite trace (even a KMS
  trace) and antiunitary shifted functional-equation symmetry
  \(JGJ^{-1}=-G\) do not imply
  \(\sigma(G)\subset i\mathbb R\). The \(2\times2\) example
  \(G=\operatorname{diag}(z,-\overline z)\) works for
  \(\operatorname{Re}z\ne0\). In addition, identical even/odd summands leave
  every supertrace character unchanged while adding arbitrary spectrum.
- **Status.** PROVED-IN-PROJECT / KNOWN ELEMENTARY COROLLARY; no RH or zero
  input; no novelty claim
- **Proof.** proof_attempts/phase24_trace_native_theorem.md
- **Support.** research/phase24/REALITY_MECHANISMS.md,
  research/phase24/NOVELTY.md, research/PHASE24_RESULT.md
- **Numerical deps.** none
- **Prereqs.** finite-dimensional operator theory; elementary supertrace
  cancellation
- **Re-audited.** Phase 24 only
- **Novelty check.** elementary matrix counterexample and standard graded
  cancellation; not publication-candidate material
- **Paper use.** project filter only; it rules out bare trace/KMS positivity
  plus duality, not source-derived self-adjointness or purity

---

## 53. DUALITY.ONLY

- **Statement.** On the existing Meyer and CCM zero-bearing carriers,
  source involutions give functional-equation/conjugation duality. Any
  invariant Hermitian form pairs \(E_\rho\) only with
  \(E_{1-\bar\rho}\), so off-line modes are neutral. The canonical CCM
  positive test form is Weil positivity/RH-equivalent; a faithful positive
  form on all Meyer jets would force RH and semisimplicity, hence simplicity
  in the Riemann one-chain specialization.
- **Status.** PROVED-IN-PROJECT / KNOWN IN DIFFERENT LANGUAGE / NEW COROLLARY;
  novelty unverified; no RH assumed
- **Proof.** `proof_attempts/phase25_polarization_theorem.md`
- **Support.** `research/phase25/PAIRING_SELECTION_RULES.md`,
  `research/phase25/JORDAN_CONSTRAINTS.md`,
  `research/phase25/WEIL_INTERFACE.md`, `research/phase25/NOVELTY.md`
- **Numerical deps.** none
- **Prereqs.** Meyer functional-equation symmetries and Jordan model; CCM
  cyclic-cokernel trace pairing; Weil positivity criterion
- **Re-audited.** Phase 25 only
- **Novelty check.** known ingredients; exact comparison of test-form and
  faithful-jet positivity is a scoped synthesis, not a universal no-go
- **Paper use.** project filter only unless expert novelty review upgrades it

---

## 54. FINITE.PRIME.ENTIRE.NOGO

- **Statement.** If
  \(F_N(s)=A(s)\prod_{j\le N}(1-p_j^{-s})^{-1}\) with one fixed nonzero
  meromorphic completion \(A\), then
  \(\operatorname{ord}_{s=0}F_N=\operatorname{ord}_{s=0}A-N\). Hence exact
  finite Euler insertion cannot give an entire approximant family for
  unbounded \(N\). Nor can an entire local factor agree with an Euler factor
  on an open half-plane.
- **Status.** PROVED-IN-PROJECT / KNOWN ELEMENTARY COROLLARY; no RH or zero
  input; no novelty claim
- **Proof.** `proof_attempts/reset2_first_zero_confinement_theorem.md`
- **Support.** `research/reset2/PRIME_RECURSION.md`,
  `research/reset2/FINITE_PRIME_COMPLETION.md`,
  `research/reset2/NOVELTY.md`
- **Numerical deps.** none
- **Prereqs.** Taylor expansion of \(p^{-s}\); identity theorem
- **Re-audited.** Reset II / Phase 26 only
- **Novelty check.** elementary order calculation packaged as an architecture
  filter
- **Paper use.** project filter only

---

## Count

Indexed mathematical results in this file: **54**.

No retained named result from
`05_RETAINED_RESULTS.md` had a missing proof/source path.
Lemma 12.P1 / 12.H2 / 12.C1–C2 are recorded in
`research/PHASE12_RESULT.md` with supporting research files
rather than a single dedicated `proof_attempts/` file each.
