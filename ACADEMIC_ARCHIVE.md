# Academic Archive & Independent Verification Initiative

> **Statement of Academic Purpose / Declaración de Propósito Académico**
> 
> This repository is maintained strictly for **academic research, scientific preservation, and independent mathematical verification**. 
>
> *Este repositorio se mantiene estrictamente con fines de **investigación académica, preservación científica y verificación matemática independiente**.*

---

## 1. Motivation: "Do Not Discard Anything Without Verification"

In pure mathematics, formal verification, and automated theorem proving, **unverified attempts, counterexamples, and withdrawn manuscripts contain immense scientific value**:

1. **Epistemological Transparency:** Understanding how state-of-the-art reasoning models formulate hypotheses, construct chains of lemmas, and where subtle logical or sign errors occur is essential for the future of computer-assisted mathematics.
2. **Preventing Knowledge Loss:** In fast-moving AI releases, retracted or modified papers risk disappearing behind minimal stubs or deleted repositories. Preserving the exact preprints, source code, and proof traces ensures that no work is lost before the global community can independently evaluate it.
3. **Open Verification & Peer Scrutiny:** Neither automated formal checkers (like Lean 4) nor proprietary model outputs should be accepted as oracles without human peer review and independent replication.

---

## 2. Preserved Withdrawn Manuscripts (`withdrawn_manuscripts_restored/`)

Following OpenAI's October 7, 2026 update, three manuscripts were formally retracted due to a sign error in the geometry of abelian 8-folds. Rather than discarding these materials, this repository archives the original uncompressed PDFs, LaTeX sources, and figures in [`withdrawn_manuscripts_restored/`](withdrawn_manuscripts_restored/) for research and comparative analysis:

* **Algebraicity of Weil classes on split abelian eightfolds** (September 18, 2026)
  * *Original PDF (812 KB) & complete 12 LaTeX sections.*
  * *Context:* Origin of the sign discrepancy (`+1` vs `-1`) in the reverse stabilization trace for cusp double-point counts.
* **Algebraicity of Kuga-Satake Correspondences for K3 Surfaces** (October 3, 2026)
  * *Original PDF (720 KB), figures, and full manuscript source.*
  * *Context:* Dependent paper whose cancellation lemma relied on the eightfold construction.
* **The rational Hodge conjecture for products of K3 surfaces** (October 4, 2026)
  * *Original full PDF (639 KB) & 13 LaTeX chapters (prior to being replaced upstream with a 3 KB stub).*

---

## 3. Academic Integrity & Citation Notice

* All original research, model architectures, and proofs were produced by OpenAI and their respective authors.
* This repository acts as a non-commercial archival mirror to support researchers, mathematicians, and logicians worldwide in assessing AI-generated mathematics.
* If you identify issues, proof repairs, or counterexamples in any manuscript, please contribute documentation or formal Lean 4 verifications.
