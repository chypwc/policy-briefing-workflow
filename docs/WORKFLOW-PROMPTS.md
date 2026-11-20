# ACT AI Policy Enquiry Workflow prompts

Use these prompts with the [shared workflow](../WORKFLOW.md). Each numbered section covers one node. In Copilot Studio, insert the named dynamic field wherever a block shows ⟦…⟧. Use the structured field from the named node. The two report section variables already contain the draft, verification status and notes.

## 1. Classify Enquiry

Set **Input to classify** to **Start → Enquiry**. Use the following descriptions with the existing category names. Both If/Else gates depend on those names.

| Category | Description |
|---|---|
| Policy summary only | The requester asks what a law, policy or assessment says about a specific ACT Government use of AI or ICT. An explanation of the evidence answers the enquiry. |
| Options brief only | The requester identifies an ACT Government AI or ICT decision and wants advice on what to do. This includes deciding whether to keep or change a documented approach. Explaining the baseline as part of that comparison belongs here. |
| Policy summary and options brief | The requester wants two deliverables on a specific ACT Government AI or ICT issue: a standalone explanation of what the sources establish and a separate recommendation on what to do. |

**Other** is the existing default for unclear or unrelated enquiries. It leads to **Generate Enquiry Triage Report**.

## 2. Gather Policy Evidence

**Knowledge:** ACT Government Artificial Intelligence Policy, Acceptable Use of ICT Resources Policy, Mobile Device Detection Cameras privacy impact assessment extract, Information Privacy Act 2014 and ACT Road Safety Framework 2026–2031.

**Structured output:** `researchFindings`

```text
Research the enquiry using the attached sources that directly address it. Put one shared handoff in researchFindings.

## Source findings

For each material finding, give the document title, page or exact provision, section or recommendation, a short supporting passage and what it establishes. Identify the assessment year or version where needed to locate the passage.

Distinguish legal duties, policy requirements, strategic objectives, recommendations and documented practice. Record the response to a recommendation separately from any evidence that it was implemented. Preserve relevant conditions, scope and exceptions. Label interpretations.

## Open questions

Include only gaps that could change the answer or decision. If the sources describe an intended approach but leave current practice unclear, identify the specific document or fact needed to confirm it. Leave options and recommendations to the drafting stage.

Enquiry:
⟦Start → Enquiry⟧
```

## 3. Draft Policy Summary

**Structured output:** `policySummary`

```text
Use the enquiry and research findings to explain the policy question in plain English for an ACT Government staff member. Put the complete draft in policySummary.

## Policy summary

Start with the direct answer. In one paragraph of up to 200 words, explain the relevant obligations, guidance or documented practice. Preserve qualifications and distinguish what the sources establish from interpretation. Flag any uncertainty that materially affects the answer.

## Key points

Recap the paragraph in up to three one-sentence bullets. These bullets sit outside the paragraph limit. In both sections, cite the document title and page, provision or exact section for each material claim. Leave proposed actions to the brief.

Enquiry:
⟦Start → Enquiry⟧

Research findings:
⟦Gather Policy Evidence → researchFindings⟧
```

## 4. Verify Summary

**Structured outputs:** `policySummaryStatus` and `policySummaryReview`

```text
Review the supplied policy summary against the enquiry and research findings. Check the direct answer, citations, qualifications and agreement between the paragraph and bullets. Apply the 200-word limit to the paragraph alone. Check that each claim about what an agency does has evidence of practice and that each claimed obligation has an applicable provision.

In policySummaryReview, identify each material issue once. Quote the shortest relevant wording from the summary, identify the evidence or gap and give the correction. Flag unresolved source checks. If the draft is sound, give one short review note.

Set policySummaryStatus to Needs revision if a required input is missing or a material correction is needed. Otherwise use Ready for human review. Approval rests with the human reviewer.

Enquiry:
⟦Start → Enquiry⟧

Research findings:
⟦Gather Policy Evidence → researchFindings⟧

Policy summary:
⟦Draft Policy Summary → policySummary⟧
```

## 5. Draft Options Brief

**Structured output:** `optionsBrief`

```text
Write an options brief of up to 400 words, including citations, for the ACT Government lead responsible for the decision. Use the enquiry and research findings. Put one complete brief in optionsBrief.

## Decision and recommendation

State the decision, your recommended action and the main reason. If a material gap could change the recommendation, say what the lead should confirm first.

## Problem and policy context

Explain the objective and the documented approach. Distinguish obligations, accepted recommendations and confirmed practice. Cite the document title and page, provision or section for each material factual claim. Identify any assumption about the current approach.

## Options and trade-offs

Follow the comparison requested in the enquiry. For a keep-or-change decision, compare retaining the documented approach with one practical alternative unless the requester asks for more. Otherwise develop two or three viable options. Compare them against the same objective and relevant criteria, such as clarity for affected people, privacy and staff effort. Label expected impacts as analysis. Explain the trade-off that drives the choice.

## First step and evaluation

Name who should act first, what needs checking and one way to judge whether the approach works. Identify a result that would prompt reconsideration.

Enquiry:
⟦Start → Enquiry⟧

Research findings:
⟦Gather Policy Evidence → researchFindings⟧
```

## 6. Verify Brief

**Structured outputs:** `optionsBriefStatus` and `optionsBriefReview`

```text
Review the supplied options brief against the enquiry and research findings. Check that it answers the decision, compares the requested options on common criteria, explains the recommendation and gives a first step and measure of success. Check the 400-word limit including citations.

Check material factual claims against the cited findings. Flag any assumption presented as current practice, accepted recommendation presented as implementation, or proposed change presented as a legal duty. Check that material unknowns and expected impacts are labelled accurately.

In optionsBriefReview, list each material issue once with a short quotation from the brief, the evidence or gap and the correction. Flag anything requiring manual source checking. If the brief is sound, give one short review note. Leave the full draft in its original field.

Set optionsBriefStatus to Needs revision if a required input is missing or a material correction is needed. Otherwise use Ready for human review. Approval rests with the human reviewer.

Enquiry:
⟦Start → Enquiry⟧

Research findings:
⟦Gather Policy Evidence → researchFindings⟧

Options brief:
⟦Draft Options Brief → optionsBrief⟧
```

## 7. Generate Review Report

**Structured output:** `reviewReport`. Use this field when copying the finished report.

```text
Put one Markdown report in reviewReport. Title it “ACT AI Policy Enquiry — Drafts for human review”. Under “## Enquiry”, copy the original enquiry once.

For Policy summary only, include the supplied summary section. For Options brief only, include the supplied brief section. For Policy summary and options brief, include both, summary first. Copy each requested section once, preserving its headings, wording, citations, status, notes and lists. Separate sections with a blank line. If a requested section is empty, give its heading and write “Not available”. End after the last requested section.

Enquiry:
⟦Start → Enquiry⟧

Selected category:
⟦Classify Enquiry → Category⟧

Summary section:
⟦Variable → summarySection⟧

Brief section:
⟦Variable → briefSection⟧
```

## 8. Generate Enquiry Triage Report

**Route:** Other. Use the existing report output for this node.

```text
Write a short Markdown report titled “ACT AI Policy Enquiry — Triage report”. Use only the supplied enquiry.

Under “## Enquiry”, copy the enquiry. Under “## Status”, use “Clarification needed” if the request could concern ACT Government use of AI or ICT but the issue or decision is unclear. Use “Outside workflow scope” for an unrelated request.

Under “## Next step”, ask one focused question for an unclear request. For an unrelated request, briefly explain the scope and suggest a relevant way to reframe it if one follows from the enquiry.

Enquiry:
⟦Start → Enquiry⟧
```

## First routing check

> Should Access Canberra change how it explains the role of AI and human reviewers to people who receive a mobile phone camera fine? Compare the approach documented in the sources with one practical alternative. Recommend whether to make the change, considering clarity for drivers, privacy and staff effort. Flag anything about the current notice that needs checking before a decision.

Expected category: **Options brief only**. The request for the documented approach supplies the baseline for one decision brief.
