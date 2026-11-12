# Internal mathematical review — YM-000033

- Reviewer session: TrishenGunaratnam-astra-checker-alpha-20261112; GPT-6 Astra, high reasoning.
- Responsible human acceptance: not supplied by this report.
- Frozen commit: 06c8d49c02d17f286ed85ab1f7206da993ce9615.
- Unit fingerprint: 485da368423b8c3ef687dfb40eafcc2616ddd5d04b220e4fa98513d1bc5ad6dc.
- Source revision: 3456e5e75cf8d4cd558955a5c7638fba2d68f464.
- Task: https://github.com/hairer/humanise-yang-mills/issues/33 ; parent checkpoint PR #35 is merged. No contribution PR yet.
- Outcome: internal mathematical pass, conditional on the precisely displayed draft prerequisites. Ready for Parent's final review; not formal acceptance or complete existence.

## Findings and evidence

The complete owned section was reviewed, not merely the changed paragraphs. Anchors below refer to manuscript/existence/trace-prosper-sensor.tex at the frozen commit.

1. Lines 4–51 now specify the actual raw Ward basis and its normalization. The initial undefined-coordinate finding is resolved. The new three tests satisfy antisymmetry and cyclic Bianchi. For the potential A_b(z)=z^a F_ab/2+z^a z^c K_cab/3, its curl is F_ab+z^c K_cab: the quadratic contribution is (2K_cab+K_acb-K_bca)/3=K_cab by Bianchi. It is radial because contraction against z^b vanishes by antisymmetry. All color values are multiples of one unit vector. Independently recomputing the three zeroth-component rows gives (0,2,0), (1,2,0), (1,2,1), determinant -2. Together with the explicitly cited raw-dimension upper bound three this proves the basis assertion. The change from basis coefficients to w is invertible, and X corresponds to (1,-1/4,1); rho(X)=0 follows. An exact rational arithmetic check of all 64 Bianchi/potential components for each test agrees; see ../jet-check.txt. This computation checks the displayed finite algebra, not the full source theorem.
2. Lines 53–96 distinguish initial levels, postlevels, the 1/5 weight and the separate crown b_n r_i^5. The source-specific chart formulas retain the core projection and their actual scale powers. The chart right inverses and convergence are identified as incoming results, rather than consequences of the rank statement. This is within the issue's permitted boundary.
3. Lines 120–136 prove sensor-map convergence. Since a_i tends to positive infinity, weighted marked-field decay implies unweighted decay. The decomposition y=Uf(y)+A(y)x is valid because fU=id and ker f=R x with x nonzero. Then T_i tends to identity in operator norm, its inverses tend to identity, and s_i T_i=f+A tensor s_i(v_i) tends to f. Multiplication by T_i^{-1} gives the desired convergence without assuming it.
4. Lines 136–144 apply the existing receiver lemma with the correct parameter order. I read the entire cited lemma and its proof in trace-weighted-estimates.tex: mu_i=rho u_i is bounded; the weighted defect evaluated on T_i is A(y) times the difference of precisely the two weighted marked expressions. Convergence on a finite basis upgrades to operator norm; inversion removes T_i. All its hypotheses are supplied here. The resulting estimate is uniform over y on an epsilon-dependent tail; the unweighted norm bound has one eventual tail. No uniformity over epsilon is falsely claimed.
5. The referenced free-rank text was inspected for the raw-dimension, quotient/kernel, equation-of-motion nonzero and two-dimensional target interfaces. Its detailed probe argument supplies the local rank interface. It remains an unaccepted draft dependency, and this review does not certify all transitive prerequisites of that chapter.
6. Independently read Winklmeier, Functional Analysis, Theorem 2.10, printed p.29, https://math.uniandes.edu.co/~mwinklme/teaching/FuncAna/FA-lecture_notes.pdf . The Banach-space norm-less-than-one corollary applies to id-T_i, since E is finite-dimensional and hence complete. The cited receiver proof also states the inverse-error bound. The external theorem is not being used to supply the special weighted receiver. Shared background/Bots searches found no accepted replacement result; no novelty inference was made.

## Retained dependencies and limits

The selected chart/lift construction, quantitative marked-field/local-price producer, marked Ward producer and their common-history realization remain explicit draft dependencies. The argument proves the sensor conclusion from them; it does not independently construct the full selected run. The medium is a later supplier and is not imposed as a restriction on the arbitrary marked sequence of the proposition. No circular reliance on the downstream Scribe assembly was found.

No blocking mathematical finding remains at this fingerprint. An optional clarity edit would say explicitly that each named nonzero curvature pair in the three tests equals the chosen unit color vector; that is the evident intended normalization used in the displayed evaluation matrix. Such an edit would still require a new fingerprint check.

See reviewer-validation.md for independent checks and ../FINAL-MANIFEST.json for exact owned/support hashes. All status/review metadata remains draft/null. A responsible independent human must perform acceptance under the repository procedure. No extra-hour correction allowance was used.
