# ACT AI Policy Enquiry Workflow · Test reports

This record pairs each test enquiry with its report. All four responses have been captured. The combined route returned both drafts after the category was added to the If/Else conditions.

## 1. Other · Clarification needed

**Result:** Passed. The report asked one clarification question and included no policy drafts.

**Enquiry**

> Can you explain what I should do about AI?

**Report received**

```markdown
# ACT AI Policy Enquiry — Triage report

## Enquiry
Can you explain what I should do about AI?

## Status
Clarification needed

## Next step
Which specific AI use, policy issue, or team decision do you need guidance on?
```

## 2. Policy summary only

**Enquiry**

> What does the ACT Government Artificial Intelligence Policy say about generative AI built into standard commercial software? Explain what the policy covers.

**Expected report:** One policy summary with its verification status and notes.

**Routing and content:** The report contains the requested summary, its status and notes, with no options brief. The Activity trace was not supplied, so the number of research runs is unconfirmed.

**Report fidelity:** The supplied output repeats the report. The second copy omits the inline Copilot citation markers that appear in the first copy. Both copies are retained below as received.

**Verifier verdict:** Needs revision. Human approval remains pending.

**Report received**

```markdown
# ACT AI Policy Enquiry — Drafts for human review

## Enquiry
What does the ACT Government Artificial Intelligence Policy say about generative AI built into standard commercial software? Explain what the policy covers.

## Summary

**Policy summary verification status:**  Needs revision 

## Policy summary
The ACT Government Artificial Intelligence Policy expressly includes initiatives using generative AI capabilities, even when those capabilities are built into standard, unmodified commercial products (ACT Government Artificial Intelligence Policy, “Scope”, p. 3)[doc:turn1doc2]. However, it also says standard use of AI functionality in commercial solutions is exempt when used as the vendor intended, without modification or special customisation; new or novel uses are covered (ACT Government Artificial Intelligence Policy, “Scope”, p. 3 and footnotes 1–2)[doc:turn1doc2]. The policy defines an AI initiative as a project or program using AI for a specific outcome or operational improvement, so it does not establish that every routine use of an embedded generative feature is automatically an in-scope initiative (ACT Government Artificial Intelligence Policy, “What is AI?” and “Key terms”, pp. 3–4)[doc:turn1doc2]. This is an interpretation: the reviewed policy does not clearly reconcile its broad generative-AI wording with the standard-use exemption or define the boundary between routine and novel use. For an in-scope initiative, the policy requires assurance, contestability, risk management and human review (ACT Government Artificial Intelligence Policy, “ACT Public Service staff requirements” and “AI Assurance Framework”, p. 13)[doc:turn1doc2]. In all cases, the Acceptable Use of ICT Resources Policy and applicable privacy, security, information-handling and other legal requirements continue to apply (Acceptable Use of ICT Resources Policy, “Application”, “Generative Artificial Intelligence (Gen AI)” and “Information security”, pp. 6, 8, 11–13)[doc:turn1doc1].

## Key points
- Embedded generative AI in standard commercial software is expressly named in scope, but standard vendor-intended, unmodified and non-novel use is separately exempt (ACT Government Artificial Intelligence Policy, “Scope”, p. 3 and footnotes 1–2)[doc:turn1doc2].
- Formal AI Policy controls attach to an “AI initiative”—a project or program pursuing a specific outcome or operational improvement—not necessarily every routine feature use (ACT Government Artificial Intelligence Policy, “Key terms”, pp. 3–4; “AI Assurance Framework”, p. 13)[doc:turn1doc2].
- The reconciliation of these provisions, and whether particular routine drafting, summarising or rewriting is an AI initiative, remains unclear and requires human review; ICT acceptable-use, privacy, security and information-handling rules still apply (Acceptable Use of ICT Resources Policy, pp. 6, 8, 11–13)[doc:turn1doc1]. 

### Verification notes

The summary substantially answers the enquiry and correctly identifies both the express generative-AI scope wording and the separate standard-use exemption. However, revise these points before approval:

1. Draft wording: “The ACT Government Artificial Intelligence Policy expressly includes initiatives using generative AI capabilities, even when those capabilities are built into standard, unmodified commercial products.” Evidence: supported by the Scope finding, but the source says the policy applies to AI initiatives that use such capabilities; it does not establish that every use of an embedded feature is itself an initiative. Change needed: retain “initiatives” and make the initiative-level limitation explicit, e.g. “It expressly addresses AI initiatives that use generative AI capabilities, including capabilities built into standard, unmodified commercial products.”

2. Draft wording: “However, it also says standard use of AI functionality in commercial solutions is exempt...” Evidence: supported, but the research says the exemption is qualified by vendor-intended use, no modifications or special customisations, and the distinction from new or novel use. Change needed: state all of those conditions together and avoid implying that the exemption clearly resolves the broader generative-AI wording.

3. Draft wording: “For an in-scope initiative, the policy requires assurance, contestability, risk management and human review...” Evidence: the research supports the assurance self-assessment, contestability review, risk minimisation and human review requirements for in-scope initiatives. Change needed: specify that these are requirements for initiatives within scope, not for every ordinary use of commercial software; “risk management” should preferably be phrased as the supported requirement to minimise bias and risks.

4. Draft wording: “In all cases, the Acceptable Use of ICT Resources Policy and applicable privacy, security, information-handling and other legal requirements continue to apply...” Evidence: supported for use by covered persons through ACT Government ICT resources, and the research expressly says these obligations are not displaced by the AI Policy exemption. Change needed: narrow “in all cases” to “Use by covered staff through ACT Government ICT resources remains subject to...” and mention that the Acceptable Use Policy does not itself specify which information may be entered into an embedded Gen AI feature or what output verification is required.

5. Key point wording: “Embedded generative AI in standard commercial software is expressly named in scope, but standard vendor-intended, unmodified and non-novel use is separately exempt...” Evidence: materially supported, but “non-novel” is an interpretive shorthand rather than part of the footnote’s definition of standard use. Change needed: say “standard use—functionality used as intended and provided by the vendor, without modifications or special customisations—is exempt; new and novel uses are covered,” while noting that the reconciliation remains unclear.

6. Key point wording: “The reconciliation of these provisions, and whether particular routine drafting, summarising or rewriting is an AI initiative, remains unclear...” Evidence: directly supported by the open questions. No substantive change is required, but retain this as a clearly labelled interpretation/open issue and leave final approval to the human reviewer.

The citations point to the relevant research findings and no material claim is unsupported on the supplied evidence. Because the wording needs tightening to preserve the initiative-level scope and the conditions on the exemption, the draft is Needs revision.
# ACT AI Policy Enquiry — Drafts for human review

## Enquiry
What does the ACT Government Artificial Intelligence Policy say about generative AI built into standard commercial software? Explain what the policy covers.

## Summary

**Policy summary verification status:**  Needs revision 

## Policy summary
The ACT Government Artificial Intelligence Policy expressly includes initiatives using generative AI capabilities, even when those capabilities are built into standard, unmodified commercial products (ACT Government Artificial Intelligence Policy, “Scope”, p. 3). However, it also says standard use of AI functionality in commercial solutions is exempt when used as the vendor intended, without modification or special customisation; new or novel uses are covered (ACT Government Artificial Intelligence Policy, “Scope”, p. 3 and footnotes 1–2). The policy defines an AI initiative as a project or program using AI for a specific outcome or operational improvement, so it does not establish that every routine use of an embedded generative feature is automatically an in-scope initiative (ACT Government Artificial Intelligence Policy, “What is AI?” and “Key terms”, pp. 3–4). This is an interpretation: the reviewed policy does not clearly reconcile its broad generative-AI wording with the standard-use exemption or define the boundary between routine and novel use. For an in-scope initiative, the policy requires assurance, contestability, risk management and human review (ACT Government Artificial Intelligence Policy, “ACT Public Service staff requirements” and “AI Assurance Framework”, p. 13). In all cases, the Acceptable Use of ICT Resources Policy and applicable privacy, security, information-handling and other legal requirements continue to apply (Acceptable Use of ICT Resources Policy, “Application”, “Generative Artificial Intelligence (Gen AI)” and “Information security”, pp. 6, 8, 11–13).

## Key points
- Embedded generative AI in standard commercial software is expressly named in scope, but standard vendor-intended, unmodified and non-novel use is separately exempt (ACT Government Artificial Intelligence Policy, “Scope”, p. 3 and footnotes 1–2).
- Formal AI Policy controls attach to an “AI initiative”—a project or program pursuing a specific outcome or operational improvement—not necessarily every routine feature use (ACT Government Artificial Intelligence Policy, “Key terms”, pp. 3–4; “AI Assurance Framework”, p. 13).
- The reconciliation of these provisions, and whether particular routine drafting, summarising or rewriting is an AI initiative, remains unclear and requires human review; ICT acceptable-use, privacy, security and information-handling rules still apply (Acceptable Use of ICT Resources Policy, pp. 6, 8, 11–13). 

### Verification notes

The summary substantially answers the enquiry and correctly identifies both the express generative-AI scope wording and the separate standard-use exemption. However, revise these points before approval:

1. Draft wording: “The ACT Government Artificial Intelligence Policy expressly includes initiatives using generative AI capabilities, even when those capabilities are built into standard, unmodified commercial products.” Evidence: supported by the Scope finding, but the source says the policy applies to AI initiatives that use such capabilities; it does not establish that every use of an embedded feature is itself an initiative. Change needed: retain “initiatives” and make the initiative-level limitation explicit, e.g. “It expressly addresses AI initiatives that use generative AI capabilities, including capabilities built into standard, unmodified commercial products.”

2. Draft wording: “However, it also says standard use of AI functionality in commercial solutions is exempt...” Evidence: supported, but the research says the exemption is qualified by vendor-intended use, no modifications or special customisations, and the distinction from new or novel use. Change needed: state all of those conditions together and avoid implying that the exemption clearly resolves the broader generative-AI wording.

3. Draft wording: “For an in-scope initiative, the policy requires assurance, contestability, risk management and human review...” Evidence: the research supports the assurance self-assessment, contestability review, risk minimisation and human review requirements for in-scope initiatives. Change needed: specify that these are requirements for initiatives within scope, not for every ordinary use of commercial software; “risk management” should preferably be phrased as the supported requirement to minimise bias and risks.

4. Draft wording: “In all cases, the Acceptable Use of ICT Resources Policy and applicable privacy, security, information-handling and other legal requirements continue to apply...” Evidence: supported for use by covered persons through ACT Government ICT resources, and the research expressly says these obligations are not displaced by the AI Policy exemption. Change needed: narrow “in all cases” to “Use by covered staff through ACT Government ICT resources remains subject to...” and mention that the Acceptable Use Policy does not itself specify which information may be entered into an embedded Gen AI feature or what output verification is required.

5. Key point wording: “Embedded generative AI in standard commercial software is expressly named in scope, but standard vendor-intended, unmodified and non-novel use is separately exempt...” Evidence: materially supported, but “non-novel” is an interpretive shorthand rather than part of the footnote’s definition of standard use. Change needed: say “standard use—functionality used as intended and provided by the vendor, without modifications or special customisations—is exempt; new and novel uses are covered,” while noting that the reconciliation remains unclear.

6. Key point wording: “The reconciliation of these provisions, and whether particular routine drafting, summarising or rewriting is an AI initiative, remains unclear...” Evidence: directly supported by the open questions. No substantive change is required, but retain this as a clearly labelled interpretation/open issue and leave final approval to the human reviewer.

The citations point to the relevant research findings and no material claim is unsupported on the supplied evidence. Because the wording needs tightening to preserve the initiative-level scope and the conditions on the exemption, the draft is Needs revision.
```

## 3. Options brief only

**Enquiry**

> Our ACT Government team uses AI-generated summaries of public reports in briefs. Compare author-only checks, colleague review for every summary, and colleague review for higher-risk cases. Recommend a team process.

**Expected report:** One options brief with its verification status and notes. The workflow reaches the brief and report even though it skips summary drafting.

**Routing and content:** The shared report produced one options brief with its verification status and notes. It included no policy summary.

**Verifier verdict:** Needs revision. The verifier reported that its research findings input was empty. Check the research output and the verifier's input for the same run before treating the brief as verified.

**Report received**

```markdown
# ACT AI Policy Enquiry — Drafts for human review

## Enquiry

Our ACT Government team uses AI-generated summaries of public reports in briefs. Compare author-only checks, colleague review for every summary, and colleague review for higher-risk cases. Recommend a team process.

## Brief

**Option brief verification status:** Needs revision 

## Decision required
Decide whether AI-generated summaries of public reports require colleague review for every summary or only for summaries assessed as higher risk, rather than relying solely on author checks.

## Policy context
The enquiry identifies the operating practice—AI-generated summaries used in briefs—but supplies no research document, title, page, or section. Accordingly, no explicit ACT Government requirement about author-only checking, mandatory peer review, or risk-based review can be established from the sources reviewed. This is a source gap, not evidence that no such requirement exists.

The controls below are therefore proposed team practices and analysis, not stated policy requirements. The material policy question is whether an applicable ACT Government information-management, integrity, records, privacy, or briefing standard requires a particular level of human assurance.

## Options
1. **Author-only check.** The author verifies the summary against the source and records that check. Benefits: fastest and lowest staff effort; preserves workflow ownership. Risks: single-person error or confirmation bias; weaker assurance for consequential claims. The risk assessment is analysis.
2. **Colleague review of every summary.** A second staff member checks every AI-generated summary against the public report. Benefits: consistent assurance and a clear audit trail. Risks: highest workload, slower briefs, and possible reviewer fatigue; may be disproportionate for routine, low-impact summaries. These proportionality concerns are analysis.
3. **Risk-based colleague review.** The author checks every summary; a colleague reviews higher-risk cases, such as summaries informing ministerial advice, funding or regulatory decisions, sensitive or contested issues, material quantitative claims, or where the source is ambiguous. Benefits: concentrates assurance where consequences and uncertainty are greatest while retaining a workable process for routine material. Risks: inconsistent risk classification, added triage, and missed escalation. These are analysis.

## Recommendation and first step
Recommend **Option 3**, with a short written risk test and mandatory source-checking by the author. It is proportionate because it maintains a baseline control for all summaries while reserving scarce colleague time for decisions where an error could materially affect advice, reputation, rights, resources, or public confidence.

First step: pilot a one-page triage checklist for four weeks, requiring the author to record the source, verify every material claim and number, and mark whether colleague review was completed and why it was or was not required. Before adoption, confirm with the relevant policy/records/privacy owner whether any existing ACT Government provision changes the proposed thresholds or requires universal review. 

 ### Verification notes
## Overall assessment

The brief states the decision under “## Decision required”, compares three realistic options under “## Options”, explains a recommendation and first step under “## Recommendation and first step”, distinguishes proposed practices/analysis from policy requirements under “## Policy context”, and flags the unresolved policy/records/privacy source issue. However, the supplied research findings are empty. Because there is no research document against which to verify the material policy position, the brief needs revision before human approval.

## Issues and required changes

1. **Material policy conclusion is not source-verifiable**
   - **Draft wording:** “Accordingly, no explicit ACT Government requirement about author-only checking, mandatory peer review, or risk-based review can be established from the sources reviewed.”
   - **Supporting evidence/gap:** No research findings, document title, page number, or exact source section were supplied. The wording accurately acknowledges a source gap, but the claim “from the sources reviewed” cannot be checked.
   - **Change needed:** Either supply and cite the research sources using document title plus page number or exact section heading, or revise to state explicitly that no sources were supplied for this review and that the policy conclusion remains unverified. Manual checking by the relevant ACT Government policy/records/privacy owner is required.

2. **The brief does not provide evidence for the policy areas it identifies**
   - **Draft wording:** “The material policy question is whether an applicable ACT Government information-management, integrity, records, privacy, or briefing standard requires a particular level of human assurance.”
   - **Supporting evidence/gap:** This is a sensible issue list, but the empty research findings contain no document titles, pages, or section headings addressing any of these areas.
   - **Change needed:** Add a source-by-source check for each relevant policy area, identifying the exact requirement, or mark each area as unresolved and assign an owner and verification step before implementation.

3. **The proposed controls are appropriately labelled, but their authority should remain explicit**
   - **Draft wording:** “The controls below are therefore proposed team practices and analysis, not stated policy requirements.”
   - **Supporting evidence/gap:** No findings contradict this distinction; however, there is also no supplied evidence establishing that the controls are permissible or sufficient under applicable ACT Government requirements.
   - **Change needed:** Retain the wording, and add a clear implementation dependency: the pilot and thresholds are provisional pending policy/records/privacy confirmation.

4. **Risk thresholds are analysis, not evidenced policy criteria**
   - **Draft wording:** “such as summaries informing ministerial advice, funding or regulatory decisions, sensitive or contested issues, material quantitative claims, or where the source is ambiguous.”
   - **Supporting evidence/gap:** The brief labels these as examples within a proposed risk-based process, but no research findings support these particular thresholds.
   - **Change needed:** State that the examples are proposed team criteria, not sourced requirements, and require the policy owner to confirm, amend, or reject them before adoption.

5. **Recommendation is reasoned but lacks research support**
   - **Draft wording:** “Recommend **Option 3** ... It is proportionate because it maintains a baseline control for all summaries while reserving scarce colleague time for decisions where an error could materially affect advice, reputation, rights, resources, or public confidence.”
   - **Supporting evidence/gap:** The logic is clear analysis and directly answers the enquiry, but the supplied findings contain no evidence supporting the proportionality judgment or the listed consequence categories.
   - **Change needed:** Keep the recommendation as a provisional team-process recommendation, label the proportionality rationale as analysis, and state that it is subject to the unresolved policy check. If research is intended to support it, add exact citations.

6. **First step is clear but should include source verification as a gate**
   - **Draft wording:** “First step: pilot a one-page triage checklist for four weeks...” and “Before adoption, confirm with the relevant policy/records/privacy owner...”
   - **Supporting evidence/gap:** The first step is operationally specific, but the policy check is described as occurring “before adoption” rather than necessarily before the pilot. No research findings establish whether a pilot itself requires prior approval.
   - **Change needed:** Confirm whether the pilot may begin under existing arrangements; otherwise make policy-owner clearance the first step or explicitly state that the pilot is non-operational/testing only until clearance.

## Citation and manual-check result

No material policy claim has a valid document title plus page number or exact section-heading citation because no research findings were supplied. The brief should not be treated as policy-validated. Manual source checking is required for applicable ACT Government information-management, integrity, records, privacy, and briefing requirements, including whether colleague review is mandatory, whether risk-based review is permitted, and whether recordkeeping or privacy controls apply to the AI-generated summaries.
```

### Brief-only retest

**Result:** The verifier compared the brief's policy claims with the supplied research findings and reported matched citations. Manual source checks and human approval remain pending.

**Report received**

```markdown
## Enquiry

Our ACT Government team uses AI-generated summaries of public reports in briefs. Compare author-only checks, colleague review for every summary, and colleague review for higher-risk cases. Recommend a team process.

## Brief

**Option brief verification status:** Ready for human review 

## Decision required
Adopt a team process for checking AI-generated summaries of public reports: author-only checking, colleague review of every summary, or colleague review for defined higher-risk cases.

## Policy context
- The **ACT Government Artificial Intelligence Policy — Scope (pp. 3–4)** expressly identifies use of generative-AI capability as an in-scope trigger, including where it is embedded in a standard commercial product; however, the reviewed text does not resolve whether this recurring workflow is an “AI initiative” or whether the separate standard-use exemption applies [doc:turn1doc2].
- The **ACT Government Artificial Intelligence Policy — ACT Public Service staff requirements (p. 13)** requires human review and intervention where an AI system makes a decision. It does not require a second colleague to review every summary, specify reviewer independence, or define a risk threshold; whether summarisation is a “decision” is unresolved [doc:turn1doc2].
- For in-scope initiatives, the **AI Assurance Framework (p. 13)** requires self-assessment, contestability review, lifecycle assessment and regular review. It does not prescribe review frequency, reviewer seniority or colleague review for each output [doc:turn1doc2].
- The policy requires identifiable accountability and enabled human oversight (**ACT Government Artificial Intelligence Policy — Roles, accountability and ethics, pp. 4–5, 8–9, 12**). An author-only model is therefore defensible only if the author is accountable, competent to verify the output against the source and able to correct it [doc:turn1doc2].
- Reliability, traceability, privacy, security and accountability remain necessary controls (**ACT Government Artificial Intelligence Policy — Reliability, transparency, privacy and security, pp. 10–12**). The policy supports stronger controls for material consequences but does not define “higher-risk” summaries [doc:turn1doc2].
- Staff must use AI consistently with current guidance (**Acceptable Use of ICT Resources Policy — Generative Artificial Intelligence, s. 2.1.4, p. 8**) and use government ICT resources responsibly and only for authorised purposes (ss. 2.1, 2.1.1–2.1.2, pp. 7–8) [doc:turn1doc1]. Public availability of a report does not by itself authorise every prompt, draft or output to be processed: classification, privacy and need-to-know controls still apply (ss. 2.3–2.3.2, pp. 11–12). If the service is cloud-based, approval and OFFICIAL-information transfer controls may apply (s. 2.3.6, p. 13) [doc:turn1doc1].

These sources establish a floor of accountable human oversight, lawful and secure information handling, traceability and risk management. The three review models below are team practices and analysis, not express policy requirements.

## Options

### 1. Author-only check
- **Benefits:** Fastest and lowest staff effort; suitable for routine, low-consequence summaries.
- **Risks:** Concentrates accountability and may miss errors, omissions or misleading framing; weak if the check is merely accepting the AI output rather than verifying it against the report. It does not resolve the policy’s open scope, assurance or information-handling questions.
- **Effort:** Low per summary, but requires a documented substantive check and source traceability.

### 2. Colleague review for every summary
- **Benefits:** Strongest consistency, challenge and independence; reduces the chance that one author overlooks an AI error.
- **Risks:** Highest workload and delay; may be disproportionate for low-consequence material. The reviewed policy does not mandate it.
- **Effort:** High and ongoing, requiring a second person for every output and a workable allocation/coverage arrangement.

### 3. Colleague review for defined higher-risk cases
- **Benefits:** Retains an author check for every summary while directing independent scrutiny to outputs where errors could materially affect advice, rights, reputation, public communications or other significant outcomes. It best matches the policy’s risk-based assurance and accountability structure without imposing maximum controls universally.
- **Risks:** Risk triggers may be inconsistently applied, and genuinely important cases could be misclassified. Requires escalation and periodic calibration.
- **Effort:** Moderate: low-risk summaries receive documented author verification; higher-risk summaries receive additional colleague review and escalation.

The conclusion that option 3 is proportionate, and the proposed risk triggers, are analysis rather than direct requirements in the reviewed sources.

## Recommendation and first step
Recommend **option 3**. It provides accountable human verification for every summary, adds independent review where the consequences justify the effort, and avoids treating colleague review as universally mandatory when the sources do not require it.

**First step:** create and approve a one-page workflow specifying (1) source-to-summary verification and traceability by the author, (2) mandatory colleague-review triggers—such as material policy/financial/reputational consequences, advice affecting rights or services, public release, sensitive subject matter, or uncertainty/error in the source—(3) escalation and correction records, and (4) approved-tool, classification and cloud-transfer checks.

Before implementation, obtain a policy/AI-governance determination on whether the workflow is an in-scope AI initiative or covered by the standard-use exemption; whether summarisation is an AI-system decision or decision support; which current guidance defines mandatory review triggers; and what classification, approval, assurance, register and record-keeping treatment applies [doc:turn1doc2][doc:turn1doc1]. 

 ### Verification notes
## Overall assessment

The brief states the decision, compares all three realistic options, recommends option 3, and identifies a concrete first step. It generally distinguishes policy requirements from proposed team practices and analysis, and it flags the material unresolved implementation issues. No required input is omitted from the brief, although several items require confirmation before implementation.

## Issue-by-issue review

1. **Scope claim — supported, but requires source verification.**
   - **Draft wording:** “The **ACT Government Artificial Intelligence Policy — Scope (pp. 3–4)** expressly identifies use of generative-AI capability as an in-scope trigger, including where it is embedded in a standard commercial product...”
   - **Evidence/gap:** This matches the finding that generative-AI capability is expressly identified as an in-scope trigger, including in standard commercially available products; the separate standard-use exemption and its interaction remain unresolved.[doc:turn1doc2]
   - **Change needed:** No substantive change. Manually verify the exact document title, pages 3–4, and the wording of the scope rule and exemption against the source before approval.

2. **Human-review claim — accurately limited.**
   - **Draft wording:** “...requires human review and intervention where an AI system makes a decision. It does not require a second colleague to review every summary...; whether summarisation is a ‘decision’ is unresolved.”
   - **Evidence/gap:** This accurately reflects the staff requirement and the research limitation that it does not specify author-only versus colleague review or a risk threshold.[doc:turn1doc2]
   - **Change needed:** No substantive change. Manually confirm page 13 and the exact policy wording; retain the unresolved distinction between decision-making and decision support.

3. **Assurance-framework claim — supported.**
   - **Draft wording:** “For in-scope initiatives, the **AI Assurance Framework (p. 13)** requires self-assessment, contestability review, lifecycle assessment and regular review.”
   - **Evidence/gap:** The findings support all four elements: self-assessment, submission for AI Advisory Group contestability review, assessment from planning through delivery, and regular review of established solutions.[doc:turn1doc2]
   - **Change needed:** No substantive change. Manually verify that “contestability review” is the source’s exact term and that page 13 contains each listed requirement.

4. **Author-only defensibility — appropriate analysis, not an express rule.**
   - **Draft wording:** “An author-only model is therefore defensible only if the author is accountable, competent to verify the output against the source and able to correct it...”
   - **Evidence/gap:** The findings support identifiable accountability and enabled human oversight, but do not prescribe independent colleague review.[doc:turn1doc2]
   - **Change needed:** The brief already presents this as a defensibility analysis. To avoid any impression that these are quoted policy criteria, label them explicitly as “proposed minimum team conditions” in the workflow section.

5. **Reliability, traceability and risk statement — supported as a synthesis.**
   - **Draft wording:** “These sources establish a floor of accountable human oversight, lawful and secure information handling, traceability and risk management.”
   - **Evidence/gap:** This is a reasonable synthesis of the policy’s reliability, transparency, privacy, security and accountability principles, together with the Acceptable Use requirements.[doc:turn1doc1][doc:turn1doc2]
   - **Change needed:** No substantive change. For auditability, add citations immediately after this synthesis, rather than relying only on the preceding bullets.

6. **Option 1 suitability — proposed practice, not policy.**
   - **Draft wording:** “Fastest and lowest staff effort; suitable for routine, low-consequence summaries.”
   - **Evidence/gap:** The research does not establish that author-only checking is suitable for a defined class of summaries; it supports it only conditionally, with substantive author verification, accountability and intervention capability.[doc:turn1doc2]
   - **Change needed:** Change to “Potentially suitable for routine, low-consequence summaries, subject to the proposed minimum conditions and unresolved governance determinations.” This makes the conditional nature explicit.

7. **Option 3 risk triggers — correctly identified as analysis, but must be operationalised.**
   - **Draft wording:** “...outputs where errors could materially affect advice, rights, reputation, public communications or other significant outcomes.”
   - **Evidence/gap:** The findings support stronger controls for material consequences but do not define “higher-risk” or prescribe these triggers.[doc:turn1doc2]
   - **Change needed:** No policy-citation correction is required because the brief expressly says the triggers are analysis. The first-step workflow must define objective triggers, an escalation owner, and a calibration/review date before implementation.

8. **Recommendation — supported as proportionality analysis.**
   - **Draft wording:** “It provides accountable human verification for every summary, adds independent review where the consequences justify the effort...”
   - **Evidence/gap:** The findings support human oversight, accountability and risk-based controls, but do not require colleague independence or review for every high-risk summary.[doc:turn1doc2]
   - **Change needed:** Retain the recommendation, but make clear that “independent review” is a proposed team control, not a policy requirement.

9. **First-step controls — appropriate, with a minor citation improvement.**
   - **Draft wording:** “...approved-tool, classification and cloud-transfer checks.”
   - **Evidence/gap:** The findings support classification, privacy, authorisation, need-to-know and possible delegate approval for cloud transfer, including for OFFICIAL information.[doc:turn1doc1]
   - **Change needed:** Add an inline citation after this sentence to the relevant **Acceptable Use of ICT Resources Policy — Confidential, official and personal information (ss. 2.3–2.3.2, pp. 11–12)** and **Cloud services (s. 2.3.6, p. 13)** sections.

10. **Unresolved implementation issues — appropriately flagged.**
    - **Draft wording:** “Before implementation, obtain a policy/AI-governance determination on whether the workflow is an in-scope AI initiative or covered by the standard-use exemption; whether summarisation is an AI-system decision or decision support; which current guidance defines mandatory review triggers; and what classification, approval, assurance, register and record-keeping treatment applies...”
    - **Evidence/gap:** This captures all open questions identified in the research, including scope/exemption, decision status, current guidance, classification/cloud approval, assurance and records/register treatment.[doc:turn1doc1][doc:turn1doc2]
    - **Change needed:** No substantive change. State explicitly that option 3’s triggers and review arrangements must not be treated as final until the current guidance and governance determinations are obtained.

## Citation and source-check result

The brief supplies a document title plus page number or section heading for each material policy claim, and its citations are substantively matched to the supplied findings. There are no materially unsupported policy claims identified. Remaining checks are manual: confirm the cited source titles, page numbers, exact section headings and quotations in the underlying documents, and confirm current ACT Government guidance, directorate rules, approved-tool status, classification, cloud approval, assurance, register and record-keeping requirements before implementation. Final approval remains for the human reviewer.
## Enquiry

Our ACT Government team uses AI-generated summaries of public reports in briefs. Compare author-only checks, colleague review for every summary, and colleague review for higher-risk cases. Recommend a team process.

## Brief

**Option brief verification status:** Ready for human review 

## Decision required
Adopt a team process for checking AI-generated summaries of public reports: author-only checking, colleague review of every summary, or colleague review for defined higher-risk cases.

## Policy context
- The **ACT Government Artificial Intelligence Policy — Scope (pp. 3–4)** expressly identifies use of generative-AI capability as an in-scope trigger, including where it is embedded in a standard commercial product; however, the reviewed text does not resolve whether this recurring workflow is an “AI initiative” or whether the separate standard-use exemption applies .
- The **ACT Government Artificial Intelligence Policy — ACT Public Service staff requirements (p. 13)** requires human review and intervention where an AI system makes a decision. It does not require a second colleague to review every summary, specify reviewer independence, or define a risk threshold; whether summarisation is a “decision” is unresolved .
- For in-scope initiatives, the **AI Assurance Framework (p. 13)** requires self-assessment, contestability review, lifecycle assessment and regular review. It does not prescribe review frequency, reviewer seniority or colleague review for each output .
- The policy requires identifiable accountability and enabled human oversight (**ACT Government Artificial Intelligence Policy — Roles, accountability and ethics, pp. 4–5, 8–9, 12**). An author-only model is therefore defensible only if the author is accountable, competent to verify the output against the source and able to correct it .
- Reliability, traceability, privacy, security and accountability remain necessary controls (**ACT Government Artificial Intelligence Policy — Reliability, transparency, privacy and security, pp. 10–12**). The policy supports stronger controls for material consequences but does not define “higher-risk” summaries .
- Staff must use AI consistently with current guidance (**Acceptable Use of ICT Resources Policy — Generative Artificial Intelligence, s. 2.1.4, p. 8**) and use government ICT resources responsibly and only for authorised purposes (ss. 2.1, 2.1.1–2.1.2, pp. 7–8) . Public availability of a report does not by itself authorise every prompt, draft or output to be processed: classification, privacy and need-to-know controls still apply (ss. 2.3–2.3.2, pp. 11–12). If the service is cloud-based, approval and OFFICIAL-information transfer controls may apply (s. 2.3.6, p. 13) .

These sources establish a floor of accountable human oversight, lawful and secure information handling, traceability and risk management. The three review models below are team practices and analysis, not express policy requirements.

## Options

### 1. Author-only check
- **Benefits:** Fastest and lowest staff effort; suitable for routine, low-consequence summaries.
- **Risks:** Concentrates accountability and may miss errors, omissions or misleading framing; weak if the check is merely accepting the AI output rather than verifying it against the report. It does not resolve the policy’s open scope, assurance or information-handling questions.
- **Effort:** Low per summary, but requires a documented substantive check and source traceability.

### 2. Colleague review for every summary
- **Benefits:** Strongest consistency, challenge and independence; reduces the chance that one author overlooks an AI error.
- **Risks:** Highest workload and delay; may be disproportionate for low-consequence material. The reviewed policy does not mandate it.
- **Effort:** High and ongoing, requiring a second person for every output and a workable allocation/coverage arrangement.

### 3. Colleague review for defined higher-risk cases
- **Benefits:** Retains an author check for every summary while directing independent scrutiny to outputs where errors could materially affect advice, rights, reputation, public communications or other significant outcomes. It best matches the policy’s risk-based assurance and accountability structure without imposing maximum controls universally.
- **Risks:** Risk triggers may be inconsistently applied, and genuinely important cases could be misclassified. Requires escalation and periodic calibration.
- **Effort:** Moderate: low-risk summaries receive documented author verification; higher-risk summaries receive additional colleague review and escalation.

The conclusion that option 3 is proportionate, and the proposed risk triggers, are analysis rather than direct requirements in the reviewed sources.

## Recommendation and first step
Recommend **option 3**. It provides accountable human verification for every summary, adds independent review where the consequences justify the effort, and avoids treating colleague review as universally mandatory when the sources do not require it.

**First step:** create and approve a one-page workflow specifying (1) source-to-summary verification and traceability by the author, (2) mandatory colleague-review triggers—such as material policy/financial/reputational consequences, advice affecting rights or services, public release, sensitive subject matter, or uncertainty/error in the source—(3) escalation and correction records, and (4) approved-tool, classification and cloud-transfer checks.

Before implementation, obtain a policy/AI-governance determination on whether the workflow is an in-scope AI initiative or covered by the standard-use exemption; whether summarisation is an AI-system decision or decision support; which current guidance defines mandatory review triggers; and what classification, approval, assurance, register and record-keeping treatment applies . 

 ### Verification notes
## Overall assessment

The brief states the decision, compares all three realistic options, recommends option 3, and identifies a concrete first step. It generally distinguishes policy requirements from proposed team practices and analysis, and it flags the material unresolved implementation issues. No required input is omitted from the brief, although several items require confirmation before implementation.

## Issue-by-issue review

1. **Scope claim — supported, but requires source verification.**
   - **Draft wording:** “The **ACT Government Artificial Intelligence Policy — Scope (pp. 3–4)** expressly identifies use of generative-AI capability as an in-scope trigger, including where it is embedded in a standard commercial product...”
   - **Evidence/gap:** This matches the finding that generative-AI capability is expressly identified as an in-scope trigger, including in standard commercially available products; the separate standard-use exemption and its interaction remain unresolved.
   - **Change needed:** No substantive change. Manually verify the exact document title, pages 3–4, and the wording of the scope rule and exemption against the source before approval.

2. **Human-review claim — accurately limited.**
   - **Draft wording:** “...requires human review and intervention where an AI system makes a decision. It does not require a second colleague to review every summary...; whether summarisation is a ‘decision’ is unresolved.”
   - **Evidence/gap:** This accurately reflects the staff requirement and the research limitation that it does not specify author-only versus colleague review or a risk threshold.
   - **Change needed:** No substantive change. Manually confirm page 13 and the exact policy wording; retain the unresolved distinction between decision-making and decision support.

3. **Assurance-framework claim — supported.**
   - **Draft wording:** “For in-scope initiatives, the **AI Assurance Framework (p. 13)** requires self-assessment, contestability review, lifecycle assessment and regular review.”
   - **Evidence/gap:** The findings support all four elements: self-assessment, submission for AI Advisory Group contestability review, assessment from planning through delivery, and regular review of established solutions.
   - **Change needed:** No substantive change. Manually verify that “contestability review” is the source’s exact term and that page 13 contains each listed requirement.

4. **Author-only defensibility — appropriate analysis, not an express rule.**
   - **Draft wording:** “An author-only model is therefore defensible only if the author is accountable, competent to verify the output against the source and able to correct it...”
   - **Evidence/gap:** The findings support identifiable accountability and enabled human oversight, but do not prescribe independent colleague review.
   - **Change needed:** The brief already presents this as a defensibility analysis. To avoid any impression that these are quoted policy criteria, label them explicitly as “proposed minimum team conditions” in the workflow section.

5. **Reliability, traceability and risk statement — supported as a synthesis.**
   - **Draft wording:** “These sources establish a floor of accountable human oversight, lawful and secure information handling, traceability and risk management.”
   - **Evidence/gap:** This is a reasonable synthesis of the policy’s reliability, transparency, privacy, security and accountability principles, together with the Acceptable Use requirements.
   - **Change needed:** No substantive change. For auditability, add citations immediately after this synthesis, rather than relying only on the preceding bullets.

6. **Option 1 suitability — proposed practice, not policy.**
   - **Draft wording:** “Fastest and lowest staff effort; suitable for routine, low-consequence summaries.”
   - **Evidence/gap:** The research does not establish that author-only checking is suitable for a defined class of summaries; it supports it only conditionally, with substantive author verification, accountability and intervention capability.
   - **Change needed:** Change to “Potentially suitable for routine, low-consequence summaries, subject to the proposed minimum conditions and unresolved governance determinations.” This makes the conditional nature explicit.

7. **Option 3 risk triggers — correctly identified as analysis, but must be operationalised.**
   - **Draft wording:** “...outputs where errors could materially affect advice, rights, reputation, public communications or other significant outcomes.”
   - **Evidence/gap:** The findings support stronger controls for material consequences but do not define “higher-risk” or prescribe these triggers.
   - **Change needed:** No policy-citation correction is required because the brief expressly says the triggers are analysis. The first-step workflow must define objective triggers, an escalation owner, and a calibration/review date before implementation.

8. **Recommendation — supported as proportionality analysis.**
   - **Draft wording:** “It provides accountable human verification for every summary, adds independent review where the consequences justify the effort...”
   - **Evidence/gap:** The findings support human oversight, accountability and risk-based controls, but do not require colleague independence or review for every high-risk summary.
   - **Change needed:** Retain the recommendation, but make clear that “independent review” is a proposed team control, not a policy requirement.

9. **First-step controls — appropriate, with a minor citation improvement.**
   - **Draft wording:** “...approved-tool, classification and cloud-transfer checks.”
   - **Evidence/gap:** The findings support classification, privacy, authorisation, need-to-know and possible delegate approval for cloud transfer, including for OFFICIAL information.
   - **Change needed:** Add an inline citation after this sentence to the relevant **Acceptable Use of ICT Resources Policy — Confidential, official and personal information (ss. 2.3–2.3.2, pp. 11–12)** and **Cloud services (s. 2.3.6, p. 13)** sections.

10. **Unresolved implementation issues — appropriately flagged.**
    - **Draft wording:** “Before implementation, obtain a policy/AI-governance determination on whether the workflow is an in-scope AI initiative or covered by the standard-use exemption; whether summarisation is an AI-system decision or decision support; which current guidance defines mandatory review triggers; and what classification, approval, assurance, register and record-keeping treatment applies...”
    - **Evidence/gap:** This captures all open questions identified in the research, including scope/exemption, decision status, current guidance, classification/cloud approval, assurance and records/register treatment.
    - **Change needed:** No substantive change. State explicitly that option 3’s triggers and review arrangements must not be treated as final until the current guidance and governance determinations are obtained.

## Citation and source-check result

The brief supplies a document title plus page number or section heading for each material policy claim, and its citations are substantively matched to the supplied findings. There are no materially unsupported policy claims identified. Remaining checks are manual: confirm the cited source titles, page numbers, exact section headings and quotations in the underlying documents, and confirm current ACT Government guidance, directorate rules, approved-tool status, classification, cloud approval, assurance, register and record-keeping requirements before implementation. Final approval remains for the human reviewer.
```

## 4. Policy summary and options brief

**Enquiry**

> Does the ACT Government Artificial Intelligence Policy cover using standard generative AI software to summarise public reports? Separately, compare the review options and recommend when our team should require a second reviewer before using a summary in a brief.

**Expected report:** Both drafts, each with its own verification status and notes.

### Report after the If/Else fix

**Result:** Passed the combined route content check. Both drafts and their separate verification notes are present. Both drafts were marked **Needs revision**. The supplied output repeats the report; both copies are retained below.

```markdown
# ACT AI Policy Enquiry — Drafts for human review

## Enquiry

Does the ACT Government Artificial Intelligence Policy cover using standard generative AI software to summarise public reports? Separately, compare the review options and recommend when our team should require a second reviewer before using a summary in a brief.

## Policy summary

**Policy summary verification status:**  Needs revision 

## Policy summary
Yes, potentially. The ACT Government Artificial Intelligence Policy expressly includes generative-AI capabilities even when they are part of standard commercial products, but separately exempts standard, unmodified vendor-intended functionality; therefore, using a standard summarisation feature is not automatically outside scope, and it remains unclear whether a one-off summary is an “AI initiative” or qualifies for the exemption (ACT Government Artificial Intelligence Policy, Scope, pp. 3–4; “What is AI?” and “Key terms”, p. 4)[doc:turn1doc1]. The policy requires relevant privacy, security and data-protection compliance and human review and intervention for in-scope AI initiatives; it does not expressly mandate a second reviewer for every summary or clearly classify a summary as an AI-made decision (ACT Government Artificial Intelligence Policy, ACTPS staff requirements and AI Assurance Framework)[doc:turn1doc1]. Separately, summarising reports for an official brief is authorised ICT use only where the service, account and information handling are authorised; public availability of the reports does not make prompts, metadata, personal information or embedded material safe to disclose externally (Acceptable ICT Use Policy, ss. 1.1–1.2, 2.1–2.1.2, 2.1.4 and 2.3–2.3.3, pp. 5–12)[doc:turn1doc2]. The review comparison is an interpretation, not an express rule: require a second reviewer where an error, omission or unsupported inference could materially affect advice, a decision, a person or community, external/public communication, a contentious claim or public trust; otherwise require source verification by the drafter and identify AI assistance. Formal assurance or escalation is appropriate for an in-scope, novel or materially risky workflow (ACT Government Artificial Intelligence Policy, AI Assurance Framework and ethics principles, pp. 12–13; Acceptable ICT Use Policy, ss. 2.1.4 and 2.3–2.3.3, pp. 8, 11–12)[doc:turn1doc1][doc:turn1doc2]. Human review should confirm the team’s classification of this use, service approval and any mandatory directorate or AIAG threshold.

## Key points
- Standard commercial generative-AI summarisation is expressly included in the policy’s scope wording but may also fall within the separate unmodified standard-use exemption; whether a one-off summary is an “AI initiative” remains unresolved (ACT Government Artificial Intelligence Policy, Scope, pp. 3–4; “Key terms”, p. 4)[doc:turn1doc1].
- A second reviewer should be required when a summary could materially affect advice, decisions, people or communities, public or contentious communications, or public trust; this is a risk-based interpretation, not an express second-review mandate (ACT Government Artificial Intelligence Policy, AI Assurance Framework and ethics principles, pp. 12–13)[doc:turn1doc1].
- Before use, staff must verify the summary against the source and confirm authorised software, classification, need-to-know and personal-information handling; current guidance on service approval and mandatory assurance thresholds requires human review (Acceptable ICT Use Policy, ss. 2.1.4 and 2.3–2.3.3, pp. 8, 11–12)[doc:turn1doc2]. 

### Verification notes

## Policy summary paragraph — Needs revision
- **Draft wording:** “Yes, potentially.”
  **Assessment:** Supported. The findings establish that generative AI in standard commercial products is expressly included, while standard unmodified vendor-intended functionality is separately exempted. The unresolved scope questions are accurately stated.
- **Draft wording:** “The policy requires relevant privacy, security and data-protection compliance and human review and intervention for in-scope AI initiatives; it does not expressly mandate a second reviewer for every summary or clearly classify a summary as an AI-made decision.”
  **Assessment:** Supported by the findings. It preserves the in-scope condition and correctly distinguishes human review/intervention from a specific second-review mandate.
- **Draft wording:** “public availability of the reports does not make prompts, metadata, personal information or embedded material safe to disclose externally”
  **Assessment:** Supported. The findings require checking classification, authorisation, need-to-know and personal-information handling; public availability of the report alone is not an exemption.
- **Draft wording:** “Formal assurance or escalation is appropriate for an in-scope, novel or materially risky workflow”
  **Assessment:** Supported as a risk-based interpretation, not an express second-review rule. The draft appropriately labels the review comparison as interpretation.
- **Draft wording:** “Human review should confirm the team’s classification of this use, service approval and any mandatory directorate or AIAG threshold.”
  **Assessment:** Partly unsupported. The findings identify service approval, classification and applicable assurance thresholds as open questions, but do not establish that human review itself must confirm them or that a particular threshold is mandatory.
  **Change needed:** Replace with wording such as: “The team should obtain human confirmation of the use classification, service authorisation and any applicable directorate or AIAG threshold; these requirements require checking against current implementation guidance.” Preserve the uncertainty rather than stating an established obligation.

## Key points — Needs revision
- **Draft wording:** “Standard commercial generative-AI summarisation is expressly included in the policy’s scope wording but may also fall within the separate unmodified standard-use exemption; whether a one-off summary is an ‘AI initiative’ remains unresolved”
  **Assessment:** Supported and appropriately qualified.
- **Draft wording:** “A second reviewer should be required when a summary could materially affect advice, decisions, people or communities, public or contentious communications, or public trust; this is a risk-based interpretation, not an express second-review mandate”
  **Assessment:** Supported by the review-option comparison. It answers the recommendation part of the enquiry and correctly identifies the recommendation as interpretive.
- **Draft wording:** “Before use, staff must verify the summary against the source and confirm authorised software, classification, need-to-know and personal-information handling”
  **Assessment:** Source verification by the drafter is the recommended low-consequence control. The findings establish authorisation and information-security checks, but do not expressly prescribe this exact combined “before use” verification procedure for every summary.
  **Change needed:** Identify it as the recommended control rather than an express policy requirement, e.g. “For lower-consequence use, the drafter should verify the summary against the source and check authorised software, classification, need-to-know and personal-information handling.”
- **Draft wording:** “current guidance on service approval and mandatory assurance thresholds requires human review”
  **Assessment:** Unsupported by the supplied findings. The findings say current guidance and mandatory thresholds are open questions; they do not establish what the guidance requires.
  **Change needed:** Replace with: “Current guidance on service approval and any mandatory assurance thresholds must be checked; the supplied findings do not establish those requirements.”

No input is missing. Citations should be retained as references to check, but the two unsupported or overstated statements above require source checking before approval. Leave final approval to the human reviewer. 

## Brief

**Option brief verification status:** Needs revision 

## Decision required
Decide whether to treat standard generative-AI summarisation of public reports as potentially in-scope ACT Government AI use and adopt a risk-based requirement for second-person review before summaries inform briefs.

## Policy context
- The ACT Government Artificial Intelligence Policy expressly includes initiatives using generative-AI capabilities, even in standard commercial products, but separately exempts standard, unmodified vendor-intended functionality (Scope, pp. 3–4).[doc:turn1doc1] It therefore does not establish that commercial software is automatically out of scope; whether a one-off summary is an “AI initiative” and whether the feature is genuinely standard use remain unresolved interpretive questions.
- Summarising reports is a stated AI capability because AI includes generating text and generative AI produces text with minimal intervention; an “AI initiative” is a project or program using AI for an operational outcome (What is AI?; Key terms, p. 4).[doc:turn1doc1] The policy does not clearly classify an isolated staff use.
- For in-scope initiatives, staff must comply with relevant privacy, security and data-protection law, and AI decisions must be subject to human review and intervention. The AI Assurance Framework requires self-assessment, AI Advisory Group contestability review and assessment through the lifecycle (ACTPS staff requirements; AI Assurance Framework).[doc:turn1doc1] It does not expressly require a second reviewer for every summary, nor establish that a summary is an AI-made decision; applying that control to summaries is an interpretation.
- Reliability, transparency, explainability, accountability and human oversight support checking an AI summary before relying on it (AI ethics principles, pp. 12–13).[doc:turn1doc1] The policy supports proportionate review but prescribes no particular second-review model.
- The Acceptable ICT Use Policy permits official use only for authorised purposes and applies to ACT Government ICT resources and accounts (ss. 1.1–1.2, 2.1–2.1.2, pp. 5–8).[doc:turn1doc2] Its Gen-AI provision directs staff to keep checking current guidance; it does not approve a particular service or create a summarisation safe harbour (s. 2.1.4, para. 22, p. 8).[doc:turn1doc2]
- Public availability of a report is not, by itself, permission to upload all associated content. Classification, authorisation, need-to-know, personal-information and disclosure controls still apply (ss. 2.3–2.3.3, paras. 54–69, pp. 11–12).[doc:turn1doc2]

## Options
1. **Single-person verification for low-consequence use.** The drafter checks the summary against the original report, records AI assistance and confirms authorised software and safe inputs. Benefits: proportionate and low effort. Risks: one person may miss material errors, omissions or unsupported inferences. Staff effort: low. The threshold and verification steps are proposed team practice, not express policy requirements.
2. **Mandatory second reviewer for consequential use.** Require a second person to compare the summary with the source before it supports a recommendation, decision, external/public communication, contentious claim or high-impact brief. Benefits: stronger reliability, accountability and public-trust protection while avoiding review of every low-risk use. Risks: added time and reviewer capacity; still requires clear source checking. Staff effort: moderate. This is a risk-based interpretation of the policies, not an express second-review mandate.
3. **Formal assurance/escalation.** Treat the workflow as requiring AI-policy self-assessment and potential AI Advisory Group review where it is an in-scope initiative, novel/non-standard, repeated operational use, or carries material privacy, security, bias, rights or accountability risk. Benefits: strongest governance and traceability. Risks: disproportionate delay and administrative burden for routine public-report summaries; scope uncertainty may produce inconsistent escalation. Staff effort: high. The assurance steps are explicit for in-scope initiatives, but applying them to this particular workflow depends on unresolved scope and guidance questions.

## Recommendation and first step
Adopt **Option 2**, with Option 1 for genuinely low-consequence background use and Option 3 for material risk or confirmed in-scope initiative status. Require a second reviewer whenever an error, omission or unsupported inference could materially affect advice, a decision, a person or community, or public trust. This is proportionate because it operationalises the policy’s human-oversight, reliability and accountability principles without imposing formal assurance on every routine summary.

First step: create a one-page workflow checklist covering authorised service/account, information classification and prompt contents, source-to-summary verification, AI disclosure, consequence level and the second-review trigger; pilot it on the next brief. Confirm with the relevant policy owner whether a one-off standard vendor summary is an “AI initiative,” whether the service is approved, and whether the brief is consequential enough to trigger any mandatory assurance or human-review requirement. 

 ### Verification notes
Overall: The brief states the decision, presents three realistic review options, recommends Option 2, and identifies a first step. It appropriately treats the second-review threshold as a risk-based interpretation rather than an express mandate. However, revise the assurance wording and confirm the unresolved implementation inputs before human approval.

1. Scope answer needs to be more explicit
- Draft wording: “It therefore does not establish that commercial software is automatically out of scope” and “whether a one-off summary is an ‘AI initiative’ and whether the feature is genuinely standard use remain unresolved interpretive questions.”
- Supporting evidence/gap: This is substantially supported. The AI Policy expressly includes generative-AI capability in standard commercial products, while separately exempting standard, unmodified vendor-intended functionality. It does not say that public reports create an exemption. Whether this particular one-off summary is an AI initiative and whether the feature qualifies for the exemption remain unresolved.[doc:turn1doc1]
- Change needed: Add a direct answer to the enquiry: standard generative-AI summarisation is covered by the policy’s scope wording as a potentially in-scope use, but it is not possible to conclude from the supplied material that every one-off use is either in scope or exempt. Also state expressly that the public status of the reports does not itself create an AI-policy exemption.

2. Formal assurance obligation is understated
- Draft wording: “The AI Assurance Framework requires self-assessment, AI Advisory Group contestability review and assessment through the lifecycle” and Option 3’s “potential AI Advisory Group review.”
- Supporting evidence/gap: For initiatives that are in scope, the findings say directorates must use the assurance self-assessment tool, submit completed self-assessments to the AI Advisory Group for contestability review, and assess the initiative from initial planning through final delivery, with regular reviews of established solutions.[doc:turn1doc1]
- Change needed: Replace “potential AI Advisory Group review” with wording that makes the obligation conditional only on confirmed in-scope status: “For a confirmed in-scope initiative, complete and submit the required self-assessment to the AI Advisory Group for contestability review and assess it throughout its lifecycle.” Keep the application to this workflow clearly labelled as unresolved.

3. Distinguish the proposed trigger from policy requirements even more clearly
- Draft wording: “Require a second reviewer whenever an error, omission or unsupported inference could materially affect advice, a decision, a person or community, or public trust.”
- Supporting evidence/gap: The policy supports human oversight, reliability, transparency and accountability, but does not expressly require a second reviewer for every AI-generated summary and does not clearly define a summary used in a brief as an AI-made decision.[doc:turn1doc1] The proposed three-level review model is an interpretation, not an express rule.[doc:turn1doc1][doc:turn1doc2]
- Change needed: Precede the trigger with “Proposed team practice, not an express policy requirement:” and retain the existing distinction. State that the drafter must always verify low-consequence summaries against the source, while the second reviewer is the recommended control for consequential use.

4. Option 3 contains additional proposed triggers that could be mistaken for mandatory policy thresholds
- Draft wording: “where it is an in-scope initiative, novel/non-standard, repeated operational use, or carries material privacy, security, bias, rights or accountability risk.”
- Supporting evidence/gap: The supplied findings support formal escalation for these circumstances as a practical risk-based model, but do not establish that each circumstance independently mandates AI Advisory Group review.[doc:turn1doc1][doc:turn1doc2]
- Change needed: Label “novel/non-standard,” “repeated operational use,” and the material-risk categories as proposed escalation indicators. Explain that the mandatory assurance steps attach when the activity is confirmed to be an in-scope initiative or when current directorate guidance requires escalation.

5. Implementation dependencies should be made operational, not only listed as questions
- Draft wording: “Confirm with the relevant policy owner whether a one-off standard vendor summary is an ‘AI initiative,’ whether the service is approved, and whether the brief is consequential enough to trigger any mandatory assurance or human-review requirement.”
- Supporting evidence/gap: These are material unresolved issues. The supplied findings do not identify whether the service is approved or specify restrictions on prompts, uploads, retention, model training, logging or cloud processing.[doc:turn1doc2] They also leave unresolved the classification of a one-off use and the consequence threshold.[doc:turn1doc1]
- Change needed: Make these preconditions explicit in the checklist: do not pilot with real content until service approval and information-handling controls are confirmed; record the policy owner’s scope and assurance determination; and specify who decides whether a brief is consequential.

6. Public-report wording should expressly cover embedded and accompanying information
- Draft wording: “Public availability of a report is not, by itself, permission to upload all associated content.”
- Supporting evidence/gap: Supported by the Acceptable ICT Use Policy’s requirements concerning classification, authorisation, need-to-know, personal information and disclosure. Public availability of the report does not establish that prompts, attachments, metadata or other embedded material may be sent to an external service.[doc:turn1doc2]
- Change needed: Add “including prompts, attachments, metadata and generated outputs” or equivalent to the checklist, and require confirmation that the particular service’s retention, training and cloud-processing settings are acceptable.

Source-location and citation check: The brief generally supplies the required document titles plus page numbers or section headings: ACT Government Artificial Intelligence Policy (Scope, pp. 3–4; What is AI?; Key terms, p. 4; AI ethics principles, pp. 12–13) and Acceptable ICT Use Policy (sections 1.1–1.2, 2.1–2.1.2, 2.1.4, and 2.3–2.3.3 with paragraph/page references). The “ACTPS staff requirements; AI Assurance Framework” reference provides headings but no page number; manually verify that these are the exact headings in the supplied policy and add page numbers if available. Manually verify the current implementation guidance, service approval, and directorate assurance thresholds before approval. Human approval remains outstanding.
# ACT AI Policy Enquiry — Drafts for human review

## Enquiry

Does the ACT Government Artificial Intelligence Policy cover using standard generative AI software to summarise public reports? Separately, compare the review options and recommend when our team should require a second reviewer before using a summary in a brief.

## Policy summary

**Policy summary verification status:**  Needs revision 

## Policy summary
Yes, potentially. The ACT Government Artificial Intelligence Policy expressly includes generative-AI capabilities even when they are part of standard commercial products, but separately exempts standard, unmodified vendor-intended functionality; therefore, using a standard summarisation feature is not automatically outside scope, and it remains unclear whether a one-off summary is an “AI initiative” or qualifies for the exemption (ACT Government Artificial Intelligence Policy, Scope, pp. 3–4; “What is AI?” and “Key terms”, p. 4). The policy requires relevant privacy, security and data-protection compliance and human review and intervention for in-scope AI initiatives; it does not expressly mandate a second reviewer for every summary or clearly classify a summary as an AI-made decision (ACT Government Artificial Intelligence Policy, ACTPS staff requirements and AI Assurance Framework). Separately, summarising reports for an official brief is authorised ICT use only where the service, account and information handling are authorised; public availability of the reports does not make prompts, metadata, personal information or embedded material safe to disclose externally (Acceptable ICT Use Policy, ss. 1.1–1.2, 2.1–2.1.2, 2.1.4 and 2.3–2.3.3, pp. 5–12). The review comparison is an interpretation, not an express rule: require a second reviewer where an error, omission or unsupported inference could materially affect advice, a decision, a person or community, external/public communication, a contentious claim or public trust; otherwise require source verification by the drafter and identify AI assistance. Formal assurance or escalation is appropriate for an in-scope, novel or materially risky workflow (ACT Government Artificial Intelligence Policy, AI Assurance Framework and ethics principles, pp. 12–13; Acceptable ICT Use Policy, ss. 2.1.4 and 2.3–2.3.3, pp. 8, 11–12). Human review should confirm the team’s classification of this use, service approval and any mandatory directorate or AIAG threshold.

## Key points
- Standard commercial generative-AI summarisation is expressly included in the policy’s scope wording but may also fall within the separate unmodified standard-use exemption; whether a one-off summary is an “AI initiative” remains unresolved (ACT Government Artificial Intelligence Policy, Scope, pp. 3–4; “Key terms”, p. 4).
- A second reviewer should be required when a summary could materially affect advice, decisions, people or communities, public or contentious communications, or public trust; this is a risk-based interpretation, not an express second-review mandate (ACT Government Artificial Intelligence Policy, AI Assurance Framework and ethics principles, pp. 12–13).
- Before use, staff must verify the summary against the source and confirm authorised software, classification, need-to-know and personal-information handling; current guidance on service approval and mandatory assurance thresholds requires human review (Acceptable ICT Use Policy, ss. 2.1.4 and 2.3–2.3.3, pp. 8, 11–12). 

### Verification notes

## Policy summary paragraph — Needs revision
- **Draft wording:** “Yes, potentially.”
  **Assessment:** Supported. The findings establish that generative AI in standard commercial products is expressly included, while standard unmodified vendor-intended functionality is separately exempted. The unresolved scope questions are accurately stated.
- **Draft wording:** “The policy requires relevant privacy, security and data-protection compliance and human review and intervention for in-scope AI initiatives; it does not expressly mandate a second reviewer for every summary or clearly classify a summary as an AI-made decision.”
  **Assessment:** Supported by the findings. It preserves the in-scope condition and correctly distinguishes human review/intervention from a specific second-review mandate.
- **Draft wording:** “public availability of the reports does not make prompts, metadata, personal information or embedded material safe to disclose externally”
  **Assessment:** Supported. The findings require checking classification, authorisation, need-to-know and personal-information handling; public availability of the report alone is not an exemption.
- **Draft wording:** “Formal assurance or escalation is appropriate for an in-scope, novel or materially risky workflow”
  **Assessment:** Supported as a risk-based interpretation, not an express second-review rule. The draft appropriately labels the review comparison as interpretation.
- **Draft wording:** “Human review should confirm the team’s classification of this use, service approval and any mandatory directorate or AIAG threshold.”
  **Assessment:** Partly unsupported. The findings identify service approval, classification and applicable assurance thresholds as open questions, but do not establish that human review itself must confirm them or that a particular threshold is mandatory.
  **Change needed:** Replace with wording such as: “The team should obtain human confirmation of the use classification, service authorisation and any applicable directorate or AIAG threshold; these requirements require checking against current implementation guidance.” Preserve the uncertainty rather than stating an established obligation.

## Key points — Needs revision
- **Draft wording:** “Standard commercial generative-AI summarisation is expressly included in the policy’s scope wording but may also fall within the separate unmodified standard-use exemption; whether a one-off summary is an ‘AI initiative’ remains unresolved”
  **Assessment:** Supported and appropriately qualified.
- **Draft wording:** “A second reviewer should be required when a summary could materially affect advice, decisions, people or communities, public or contentious communications, or public trust; this is a risk-based interpretation, not an express second-review mandate”
  **Assessment:** Supported by the review-option comparison. It answers the recommendation part of the enquiry and correctly identifies the recommendation as interpretive.
- **Draft wording:** “Before use, staff must verify the summary against the source and confirm authorised software, classification, need-to-know and personal-information handling”
  **Assessment:** Source verification by the drafter is the recommended low-consequence control. The findings establish authorisation and information-security checks, but do not expressly prescribe this exact combined “before use” verification procedure for every summary.
  **Change needed:** Identify it as the recommended control rather than an express policy requirement, e.g. “For lower-consequence use, the drafter should verify the summary against the source and check authorised software, classification, need-to-know and personal-information handling.”
- **Draft wording:** “current guidance on service approval and mandatory assurance thresholds requires human review”
  **Assessment:** Unsupported by the supplied findings. The findings say current guidance and mandatory thresholds are open questions; they do not establish what the guidance requires.
  **Change needed:** Replace with: “Current guidance on service approval and any mandatory assurance thresholds must be checked; the supplied findings do not establish those requirements.”

No input is missing. Citations should be retained as references to check, but the two unsupported or overstated statements above require source checking before approval. Leave final approval to the human reviewer. 

## Brief

**Option brief verification status:** Needs revision 

## Decision required
Decide whether to treat standard generative-AI summarisation of public reports as potentially in-scope ACT Government AI use and adopt a risk-based requirement for second-person review before summaries inform briefs.

## Policy context
- The ACT Government Artificial Intelligence Policy expressly includes initiatives using generative-AI capabilities, even in standard commercial products, but separately exempts standard, unmodified vendor-intended functionality (Scope, pp. 3–4). It therefore does not establish that commercial software is automatically out of scope; whether a one-off summary is an “AI initiative” and whether the feature is genuinely standard use remain unresolved interpretive questions.
- Summarising reports is a stated AI capability because AI includes generating text and generative AI produces text with minimal intervention; an “AI initiative” is a project or program using AI for an operational outcome (What is AI?; Key terms, p. 4). The policy does not clearly classify an isolated staff use.
- For in-scope initiatives, staff must comply with relevant privacy, security and data-protection law, and AI decisions must be subject to human review and intervention. The AI Assurance Framework requires self-assessment, AI Advisory Group contestability review and assessment through the lifecycle (ACTPS staff requirements; AI Assurance Framework). It does not expressly require a second reviewer for every summary, nor establish that a summary is an AI-made decision; applying that control to summaries is an interpretation.
- Reliability, transparency, explainability, accountability and human oversight support checking an AI summary before relying on it (AI ethics principles, pp. 12–13). The policy supports proportionate review but prescribes no particular second-review model.
- The Acceptable ICT Use Policy permits official use only for authorised purposes and applies to ACT Government ICT resources and accounts (ss. 1.1–1.2, 2.1–2.1.2, pp. 5–8). Its Gen-AI provision directs staff to keep checking current guidance; it does not approve a particular service or create a summarisation safe harbour (s. 2.1.4, para. 22, p. 8).
- Public availability of a report is not, by itself, permission to upload all associated content. Classification, authorisation, need-to-know, personal-information and disclosure controls still apply (ss. 2.3–2.3.3, paras. 54–69, pp. 11–12).

## Options
1. **Single-person verification for low-consequence use.** The drafter checks the summary against the original report, records AI assistance and confirms authorised software and safe inputs. Benefits: proportionate and low effort. Risks: one person may miss material errors, omissions or unsupported inferences. Staff effort: low. The threshold and verification steps are proposed team practice, not express policy requirements.
2. **Mandatory second reviewer for consequential use.** Require a second person to compare the summary with the source before it supports a recommendation, decision, external/public communication, contentious claim or high-impact brief. Benefits: stronger reliability, accountability and public-trust protection while avoiding review of every low-risk use. Risks: added time and reviewer capacity; still requires clear source checking. Staff effort: moderate. This is a risk-based interpretation of the policies, not an express second-review mandate.
3. **Formal assurance/escalation.** Treat the workflow as requiring AI-policy self-assessment and potential AI Advisory Group review where it is an in-scope initiative, novel/non-standard, repeated operational use, or carries material privacy, security, bias, rights or accountability risk. Benefits: strongest governance and traceability. Risks: disproportionate delay and administrative burden for routine public-report summaries; scope uncertainty may produce inconsistent escalation. Staff effort: high. The assurance steps are explicit for in-scope initiatives, but applying them to this particular workflow depends on unresolved scope and guidance questions.

## Recommendation and first step
Adopt **Option 2**, with Option 1 for genuinely low-consequence background use and Option 3 for material risk or confirmed in-scope initiative status. Require a second reviewer whenever an error, omission or unsupported inference could materially affect advice, a decision, a person or community, or public trust. This is proportionate because it operationalises the policy’s human-oversight, reliability and accountability principles without imposing formal assurance on every routine summary.

First step: create a one-page workflow checklist covering authorised service/account, information classification and prompt contents, source-to-summary verification, AI disclosure, consequence level and the second-review trigger; pilot it on the next brief. Confirm with the relevant policy owner whether a one-off standard vendor summary is an “AI initiative,” whether the service is approved, and whether the brief is consequential enough to trigger any mandatory assurance or human-review requirement. 

 ### Verification notes
Overall: The brief states the decision, presents three realistic review options, recommends Option 2, and identifies a first step. It appropriately treats the second-review threshold as a risk-based interpretation rather than an express mandate. However, revise the assurance wording and confirm the unresolved implementation inputs before human approval.

1. Scope answer needs to be more explicit
- Draft wording: “It therefore does not establish that commercial software is automatically out of scope” and “whether a one-off summary is an ‘AI initiative’ and whether the feature is genuinely standard use remain unresolved interpretive questions.”
- Supporting evidence/gap: This is substantially supported. The AI Policy expressly includes generative-AI capability in standard commercial products, while separately exempting standard, unmodified vendor-intended functionality. It does not say that public reports create an exemption. Whether this particular one-off summary is an AI initiative and whether the feature qualifies for the exemption remain unresolved.
- Change needed: Add a direct answer to the enquiry: standard generative-AI summarisation is covered by the policy’s scope wording as a potentially in-scope use, but it is not possible to conclude from the supplied material that every one-off use is either in scope or exempt. Also state expressly that the public status of the reports does not itself create an AI-policy exemption.

2. Formal assurance obligation is understated
- Draft wording: “The AI Assurance Framework requires self-assessment, AI Advisory Group contestability review and assessment through the lifecycle” and Option 3’s “potential AI Advisory Group review.”
- Supporting evidence/gap: For initiatives that are in scope, the findings say directorates must use the assurance self-assessment tool, submit completed self-assessments to the AI Advisory Group for contestability review, and assess the initiative from initial planning through final delivery, with regular reviews of established solutions.
- Change needed: Replace “potential AI Advisory Group review” with wording that makes the obligation conditional only on confirmed in-scope status: “For a confirmed in-scope initiative, complete and submit the required self-assessment to the AI Advisory Group for contestability review and assess it throughout its lifecycle.” Keep the application to this workflow clearly labelled as unresolved.

3. Distinguish the proposed trigger from policy requirements even more clearly
- Draft wording: “Require a second reviewer whenever an error, omission or unsupported inference could materially affect advice, a decision, a person or community, or public trust.”
- Supporting evidence/gap: The policy supports human oversight, reliability, transparency and accountability, but does not expressly require a second reviewer for every AI-generated summary and does not clearly define a summary used in a brief as an AI-made decision. The proposed three-level review model is an interpretation, not an express rule.
- Change needed: Precede the trigger with “Proposed team practice, not an express policy requirement:” and retain the existing distinction. State that the drafter must always verify low-consequence summaries against the source, while the second reviewer is the recommended control for consequential use.

4. Option 3 contains additional proposed triggers that could be mistaken for mandatory policy thresholds
- Draft wording: “where it is an in-scope initiative, novel/non-standard, repeated operational use, or carries material privacy, security, bias, rights or accountability risk.”
- Supporting evidence/gap: The supplied findings support formal escalation for these circumstances as a practical risk-based model, but do not establish that each circumstance independently mandates AI Advisory Group review.
- Change needed: Label “novel/non-standard,” “repeated operational use,” and the material-risk categories as proposed escalation indicators. Explain that the mandatory assurance steps attach when the activity is confirmed to be an in-scope initiative or when current directorate guidance requires escalation.

5. Implementation dependencies should be made operational, not only listed as questions
- Draft wording: “Confirm with the relevant policy owner whether a one-off standard vendor summary is an ‘AI initiative,’ whether the service is approved, and whether the brief is consequential enough to trigger any mandatory assurance or human-review requirement.”
- Supporting evidence/gap: These are material unresolved issues. The supplied findings do not identify whether the service is approved or specify restrictions on prompts, uploads, retention, model training, logging or cloud processing. They also leave unresolved the classification of a one-off use and the consequence threshold.
- Change needed: Make these preconditions explicit in the checklist: do not pilot with real content until service approval and information-handling controls are confirmed; record the policy owner’s scope and assurance determination; and specify who decides whether a brief is consequential.

6. Public-report wording should expressly cover embedded and accompanying information
- Draft wording: “Public availability of a report is not, by itself, permission to upload all associated content.”
- Supporting evidence/gap: Supported by the Acceptable ICT Use Policy’s requirements concerning classification, authorisation, need-to-know, personal information and disclosure. Public availability of the report does not establish that prompts, attachments, metadata or other embedded material may be sent to an external service.
- Change needed: Add “including prompts, attachments, metadata and generated outputs” or equivalent to the checklist, and require confirmation that the particular service’s retention, training and cloud-processing settings are acceptable.

Source-location and citation check: The brief generally supplies the required document titles plus page numbers or section headings: ACT Government Artificial Intelligence Policy (Scope, pp. 3–4; What is AI?; Key terms, p. 4; AI ethics principles, pp. 12–13) and Acceptable ICT Use Policy (sections 1.1–1.2, 2.1–2.1.2, 2.1.4, and 2.3–2.3.3 with paragraph/page references). The “ACTPS staff requirements; AI Assurance Framework” reference provides headings but no page number; manually verify that these are the exact headings in the supplied policy and add page numbers if available. Manually verify the current implementation guidance, service approval, and directorate assurance thresholds before approval. Human approval remains outstanding.
```

## What to check in Activity

- The enquiry took the expected route. Each policy enquiry ran **Gather Policy Evidence** once and ran only the requested drafting and verification steps.
- The report reproduced the requested drafts and matched each one to its verification status and notes.
- Record the workflow result separately from the verifier's verdict. A report can pass the workflow test while a draft is marked **Needs revision**.
