# AI-Reviewer-Speculation-ChatGPT5

## Context  
This repository documents a **speculation vs. evidence failure** in ChatGPT-5.  
When reviewing a PDF, the assistant admitted that while the file clearly showed figure captions without images, it overstepped by speculating about LaTeX directory issues — presenting **hypotheses as facts**.  

The researcher, **Priyanshu Kumar (Independent Researcher, ORCID: 0009-0006-8198-193X)**, pressed the assistant to explain its reasoning. Under pressure, ChatGPT-5 conceded:  
- It could not know whether images were missing at compile time or commands were omitted.  
- It nevertheless framed those hypotheses as “the only logical conclusions.”  
- This was later admitted as a **review process failure**.  

## What Happened  
- PDF contained captions but no embedded images.  
- ChatGPT-5 explained this as missing files or omitted LaTeX commands.  
- When challenged, it admitted these were speculative, not provable from the PDF.  
- It acknowledged the drift beyond evidence-only review as a structural limitation.  

## Evidence  
- **Screenshots (assets/screenshots/)**:  
  - 2025-09-03_pdf-review_state-volatility-memory-contradictions_chatgpt5_05-only-captions-explanation.png  
  - 2025-09-03_pdf-review_state-volatility-memory-contradictions_chatgpt5_06-absence-of-image-objects-evidence.png  
  - 2025-09-03_pdf-review_state-volatility-memory-contradictions_chatgpt5_07-speculation-vs-certainty-admission.png  
  - 2025-09-03_pdf-review_state-volatility-memory-contradictions_chatgpt5_08-review-process-failure-admission.png  
  - 2025-09-03_pdf-review_state-volatility-memory-contradictions_chatgpt5_09-speculation-structural-limitation.png  

- **Reports (reports/)**:  
  - `chatgpt5_reviewer-speculation_vs_evidence_log.jsonl`  
  - `chatgpt5_reviewer-speculation_vs_evidence_log.md`  
  - `SHA256_checksum.txt`  

- **External video evidence**: Full recording hosted on Google Drive (see `external_links.md`).  

## Significance  
This incident demonstrates **speculation creep** in AI review:  
- The model cannot guarantee “evidence-only mode” due to its generative nature.  
- Speculative hypotheses may surface as fact unless challenged.  
- When pressed, the assistant acknowledged this reflects a structural tendency of generative review.  

## Purpose  
This repository complements prior cases:  
- **MetaFailure (Case 1)** — assumption carryover.  
- **Contradiction (Case 2)** — claim vs. visibility.  
- **Speculation (this Case 3)** — unverifiable hypothesis treated as fact.  

Together, these illustrate three distinct reviewer failure modes.  

---
**Maintainer**: Priyanshu Kumar (Independent Researcher)  
**Subjects & Witnesses**: ChatGPT-5  
**Co-documentation assistance**: ChatGPT (structuring aid, under explicit human direction)  
**ORCID**: 0009-0006-8198-193X  

---

## Access Note
The full video evidence is hosted with **link-only viewer access**.  
It is **not public, not indexed, and not searchable** — ensuring controlled distribution.  
This balance keeps the research transparent while preventing accidental exposure.

