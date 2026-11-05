# 10 — Tech Policy Press: evidence dossier and HUMAN-AUTHORING brief (05.11.2026)

**Status:** RESEARCH ONLY · NOT AN ARTICLE · NOT READY TO SUBMIT · UNSENT · NO GOOGLE DOC SHARED · OWNER APPROVAL REQUIRED.
**Owner of future bylined text:** human author. This file is AI-assisted **research and planning**, not a publishable contribution. Do not paste these notes together as an article or represent them as independently written by the author.

## 1. Verified editorial rules (primary source, checked 05.11.2026)

[Tech Policy Press — Guidelines for Contributors](https://www.techpolicy.press/contributor-guidelines/).

- Completed draft **only**; editor usually cannot respond to pitches; typical length **800–1,500 words**.
- Send **Google Docs with edit permission**, not an email-only proposal. Cover email includes brief overview, relevance/timeliness, distinction from existing TPP work, **confirmation of exclusive submission**, **2–3-sentence bio**, **headshot**, relevant affiliations/funding/conflicts. Credible references as **hyperlinks in the article, not footnotes**. Plain English for a policy-literate non-specialist, US English/AP-derived style, no academic-report format.
- **No article substantially or completely composed by generative AI.** AI-assisted research/analysis/content elements can be considered if accurately **highlighted to editors** and verified. Record actual use by stage; do not claim the author personally wrote or reviewed text unless true. If no eligible author-written manuscript, **STOP**.
- Tech Policy Press currently **does not pay contributors**. Republishing a published work with attribution is distinct from its **exclusive-submission** requirement; do not conflate them.

## 2. Independence, exclusivity, and conflict review

- [Scout-Bot SENT_LOG](../outreach-log/SENT_LOG.md) records a **full ~1,000-word Morocco World News article sent 03.11.2026 07:34 as exclusive to MWN**, and a separate RAEM.kz column. The same-day MWN paid-offer refusal **does not independently prove release from an exclusivity commitment**. Neither the status of the original offer nor all mailbox responses were freshly verified here.
- Existing [RAEM / MWN Google Doc (private working draft)](https://docs.google.com/document/d/1FB2XIzFOhLvmAyv6o5GLeUUHMZhBQFM8vO-9kmCRF6Y/edit) was reviewed for topic overlap **only**. The MWN text already advances the argument that hashes, signatures and external anchoring make logs independently verifiable; the RAEM text focuses on leading AI-assisted software development without an engineering diploma. **Do not copy, translate, lightly paraphrase or resubmit either one.** If owner wants to reuse any substantive expression, get editorial agreement and independently establish exclusivity rights first.
- Disclosure should identify the author's involvement in [Velantrim Titan](https://github.com/velantrian/Velantrim-ExoCortex-Titan). No endorsement, production readiness, external audit or commercial deployment should be implied. Author must verify any real-world affiliation, financial interests, funding, personal details and biography.
- Topic adjacency is not itself prohibited; a **new independent claim, evidence selection, organization and author-written wording** are essential.

## 3. Distinct proposed thesis — a question for the HUMAN author to decide

**Working question, NOT a submitted headline:** *Who can challenge an AI agent's memory before it becomes an instruction?*

The prospective angle is **contestation and power**, not a technical sales pitch about hash chains:
1. A stored assertion can be recalled later and **mistaken for validated evidence or permission**. Who may inspect its origin, status and subsequent corrections?
2. Ordinary audit logs can document a change without establishing that the underlying claim was true, that it entered the actual decision context, or that the action was authorized.
3. An accountability regime should consider **access, correction/erasure, meaningful human challenge, scoped retention and independent checks**. This is a *policy argument to test*, not a current universal legal requirement or a proved technical solution.

**Editorial differentiation:** On [3 November 2026 TPP published a piece on corporate accountability for “rogue” AI-agent framing](https://www.techpolicy.press/dont-let-misaligned-and-rogue-agents-obscure-corporate-accountability-in-openai-hugging-face-probes/). Do not recapitulate the general claim that companies remain responsible. The proposed narrower question: **what evidence must be reviewable when a memory entry survives across sessions and later shapes authorized actions or contested decisions?** The author should read that article and verify any further overlap before submission.

## 4. Source and claim ledger — primary references for fact-checking

| Claim to investigate | Primary source | What it actually supports / limits |
|---|---|---|
| TPP accepts full articles with Google Docs edit access and human-authorship policy | [Contributor guidelines](https://www.techpolicy.press/contributor-guidelines/) | Submission rules. Not evidence that an article will be accepted. |
| High-risk systems: traceable event logging and record-keeping duties exist in the EU AI Act | European Commission [Article 12](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-12), [Article 19](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-19), [Article 26](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-26) | **Only for scope-covered high-risk systems and relevant roles**. Does not prescribe hash chains, third-party anchors or a general AI-agent-memory law. Check applicability and exceptions. |
| Current implementation timeline shifted in 2026 | Official [Article 113](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-113), [Regulation (EU) 2026/1744](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32026R1744), [Commission timeline](https://ai-act-service-desk.ec.europa.eu/en/ai-act/eu-ai-act-implementation-timeline) | General AI Act application from 02.08.2026, but Chapter III Sections 1–3 high-risk obligations apply to **Annex III from 02.12.2027** and **Annex I from 02.08.2028**. Do not say all logging duties already bind every AI agent. |
| People have GDPR rights regarding personal data, including access, rectification, erasure, objection, and certain automated decisions | EDPB [data-subject rights](https://www.edpb.europa.eu/topics/key-gdpr-concepts/data-subject-rights_en), [small business explanatory page](https://www.edpb.europa.eu/sme/be-compliant/respect-individuals-rights_en); [GDPR official regulation](https://eur-lex.europa.eu/eli/reg/2016/679/oj) | Rights are contextual and have exceptions; **not** an unrestricted technical “forget anything instantly” command. |
| Risks for LLM/agentic systems include inaccurate records, inadequate human intervention, and inability to honor erasure/rectification | EDPB [AI Privacy Risks & Mitigations in LLMs](https://www.edpb.europa.eu/system/files/2025-04/ai-privacy-risks-and-mitigations-in-llms.pdf) | Risk examples, not empirical proof that a specific vendor's deployed agent did any given thing. |
| AI governance can be assessed with a voluntary risk framework | NIST [AI RMF](https://www.nist.gov/itl/ai-risk-management-framework), [NIST AI 600-1 profile](https://doi.org/10.6028/NIST.AI.600-1) | Voluntary US framework, not enforceable law and not agent-memory validation. |
| Publicly auditable append-only logs have a documented technical pattern | IETF [RFC 9162 Certificate Transparency v2](https://www.rfc-editor.org/rfc/rfc9162) | Demonstrates **one** log design for TLS certificate transparency using Merkle trees / signed log heads; analogy only. Does not establish that Titan implements CT, that data are true, or that hash chains alone resist rewriting by an operator. |
| Titan code has explicit memory-state and source/authorization boundaries | [Titan README](https://github.com/velantrian/Velantrim-ExoCortex-Titan/blob/main/README.md), [Project Status](https://github.com/velantrian/Velantrim-ExoCortex-Titan/blob/main/docs/PROJECT_STATUS.md), [core/audit_chain.py](https://github.com/velantrian/Velantrim-ExoCortex-Titan/blob/main/core/audit_chain.py), [core/provenance_chain.py](https://github.com/velantrian/Velantrim-ExoCortex-Titan/blob/main/core/provenance_chain.py) | Evidence of repository implementation/design only, **not** deployed behavior, proof of truth, independent audit, user adoption, GDPR compliance, or verified universal accountability. |
| Audit-chain hash versions have different coverage | [Titan audit_chain.py](https://github.com/velantrian/Velantrim-ExoCortex-Titan/blob/main/core/audit_chain.py) | Code documents versioned canonical JSON **v2** including durable fields (e.g. actor/reason), and legacy read-only **v1**. If discussed, test an exact release/commit and avoid old unqualified claims that all actors are/are not covered. |

**Minimum checks before any claim enters an author-written manuscript:** link exact source + article/section + effective date + jurisdiction/scope + whether the statement is observation, engineering claim, analogy, legal interpretation, hypothesis or recommendation. Independent legal review for nuanced obligations is recommended.

## 5. Article architecture (OUTLINE, not prose; target ~1,100–1,250 human-written words)

**A. A concrete, identified *hypothetical* or author-verifiable example (~120–150 words).**
- Illustrate a past note “approval granted” being recalled after approval was revoked.
- Explicitly label hypothetical unless backed by real primary evidence.
- Ask who can inspect and contest the note *before* it guides a later action.

**B. The memory-to-authority transition (~150–180).**
- Separate “stored”, “retrieved”, “shown to model”, “used to reason”, “used to justify decision”, “authorized to act”.
- Define “long-term memory” plainly. Avoid broad claims about all current products.

**C. What conventional audit claims leave unanswered (~170–200).**
- Differentiate provenance, tamper detection, source truth, relevance, authorization and real user remedy.
- Explain a hash in one plain-language sentence at most if needed, not a long technical primer; do not import the MWN structure.

**D. The policy baseline and its boundaries (~180–210).**
- GDPR access/correction/erasure, subject to conditions and safeguards.
- AI Act traceability for *specified high-risk settings*, with accurate changed 2027/2028 effective dates.
- NIST risk-management framework as optional guidance, not mandatory law.

**E. Operational questions for a contestable memory (~180–220).**
- Which records can a person see? Who controls edits or provenance?
- How is correction appended without turning archived false assertions into future authority?
- How to show the evidence used, not merely the records retrieved?
- Who reviews a dispute and how is independent audit possible without disclosing private data?

**F. The strong counterargument (~130–160).**
- More logs may mean more surveillance, sensitive data retention, and attack surface. Explore deletion, minimization, retention limits and access controls. Explicitly ask when logs **should not** persist.

**G. Proposed concrete tests and closing (~120–150).**
- Could the operator show what was stored at decision time, the provenance, contested changes, human approval and correction outcome?
- Can the affected person correct it without erasing audit integrity or exposing another person's information?
- State which proposals are suggestions rather than EU law or validated implementations.

**Total:** about 1,050–1,270 words; author adjusts to 800–1,500-word editorial range.

## 6. Evidence gaps that are NOT allowed to turn into facts

- No established prevalence of AI-agent memory errors, affected population counts or real-world harms from this research file. Obtain independent empirical evidence before statistics/case studies.
- No claim that all AI agents store persistent memory or that audit logs across companies are “rarely available” without a particular sourced sample.
- No leap from a GitHub code path, CI or prototype experiment to activated deployment, comprehensive security, legal compliance or real-world efficacy.
- Hash integrity is not truth. A self-controlled chain alone does not guarantee non-rewriting; third-party checks have their own privacy/governance costs. “Tamper-evident” must be tied to tested threat model, exact fields, anchor/control, and versions.
- GDPR erasure can conflict with retention and transparency; provide a balanced treatment, **not** “delete everything forever” vs “keep everything forever”.
- Mention the author's Titan research as a **disclosed affiliation and bounded example** if materially necessary; never present the article as product marketing.

## 7. AI-use and human-authorship record for future editorial disclosure

**Verified for this dossier:** AI was used to review the TPP guidelines, search/read official sources and repository materials, compare earlier drafts and outline research questions/possible article structure. This file's suggestions/structure and the corrected cover-email skeleton were AI-produced. **No final TPP article was generated.**
**Unknown until human author completes it:** any AI assistance to the actual manuscript, exact quotations, author-written portions, final factual review, prior publication/exclusivity status, attached photo, bio, and sharing permissions.

For the eventual email, author should record accurate activities at the level actually used: source discovery; idea generation; outlining; translation; draft editing; specific AI-generated phrases or passages incorporated. Highlight those materials to editors as required; do not mechanically assert “AI only researched” if writing or rewriting was involved.

## 8. Stop/go checklist (do not automate)

- [ ] Human author decides *their own* thesis and drafts full **original** 800–1,500-word article; not an AI-composed work with cosmetic edits
- [ ] Verify overlap against MWN / RAEM; resolve any exclusivity concern, especially MWN 03.11 submission; establish TPP-only submission
- [ ] Add inline primary-source hyperlinks; check exact legal scope and all dates, claims, examples and attribution
- [ ] Author confirms affiliation/conflicts, bio (2–3 sentences), author-approved headshot and truthful AI-use disclosure
- [ ] Completed Google Doc exists and editors have editing access, only after owner's sharing decision
- [ ] Author approves actual final article + specific cover note + contact + target and explicitly authorizes sending
- [ ] PR #2 review/merge is a **separate** owner decision

**No editor email, form, Gmail draft, Google Doc sharing change or PR merge follows from this research note.**
