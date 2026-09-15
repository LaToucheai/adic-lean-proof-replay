# RI-INTEROP-GHOSTDRIFT-001

**Status:** Completed bounded interoperability test  
**Test class:** External-system representability and receiver independence  
**Canonical web record:** https://responsibilityinfrastructure.com/interop#ri-interop-ghostdrift-001

## Result

| Dimension | Result |
|---|---|
| Representability | PASS |
| Responsibility Completeness | PARTIAL |
| Receiver Independence | PASS |
| Overall | PARTIAL |
| RI Conformance | NOT ESTABLISHED |

## Tested source boundary

The test used the public GhostDrift / ADIC Lean replay source state at commit:

`3f64c50c25914dd82ba8adad7f4c3aa819275bf0`

The bounded test asked whether facts established by the source artefact could be represented in a Responsibility Infrastructure record and consumed by a generic RI receiver without inventing responsibility, authority or acceptance claims that the source did not establish.

Under the tested conditions, the formal-verifier result and source-supported facts were representable. The RI mapping preserved the distinction between **formal verifier acceptance** and **operational responsibility**. No operational authority, assignment, acceptance, Recognition or current Standing was inferred merely from the proof artefact.

## Claims boundary

This result is deliberately narrow. It does **not** establish:

- GhostDrift adoption of Responsibility Infrastructure;
- endorsement, partnership or participation;
- certification or regulatory approval;
- full Responsibility Infrastructure conformance;
- Recognition or Registry standing;
- production interoperability beyond the tested source boundary;
- operational responsibility from formal proof acceptance alone.

The result describes only the bounded test and frozen source state identified above. It is not a general assessment of GhostDrift, ADIC, their security, quality, legality, fitness for purpose or commercial suitability.

## Research context

This test forms part of the empirical research programme associated with:

**AI Governance Is Not Enough to Prove Responsibility: A Conceptual and Testable Architecture for Demonstrable Responsibility in AI Systems.** Canonical public research edition, version 1.0 (2026), Responsibility Infrastructure Publications. DOI: https://doi.org/10.5281/zenodo.21848724

The paper provides the research hypothesis and terminology. The result above stands on the evidence of this bounded test; the paper itself is not evidence that the tested system conforms.

## Attribution, copyright and third-party rights

GhostDrift and ADIC are named solely to identify the third-party source artefact used in the test. All third-party names, marks, source code, papers and documentation remain the property of their respective owners and remain subject to their applicable licences or rights. This report does not alter or relicense third-party material.

This report does not imply affiliation, endorsement, sponsorship, certification or permission by the third-party project.

**Report copyright:** © 2026 LA TOUCHE HOLDINGS LTD. All rights reserved. Short quotations for research, review and citation are permitted with attribution and a link to the canonical record. No broader licence to modify, republish or redistribute this report is granted unless expressly stated in writing.

**Trade mark notice:** Responsibility Infrastructure® is a registered trade mark of LA TOUCHE HOLDINGS LTD in the United Kingdom. Third-party trade marks remain the property of their respective owners.
