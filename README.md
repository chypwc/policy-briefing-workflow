# ACT AI Policy Enquiry Workflow

A Microsoft Copilot Studio portfolio project that turns a staff enquiry into a cited policy summary, an options brief or both. The research agent draws evidence from policy PDFs stored in SharePoint. A verifier checks each draft against those findings. A person makes the final editorial decision.

## Agent workflow

```text
Staff enquiry
  |
  v
Classify Enquiry
  |-- Other --> Generate Enquiry Triage Report
  |
  '-- Summary only, brief only, or both
        |
        v
      Gather Policy Evidence <--- Policy PDFs in SharePoint
        |
        v
      Needs a summary? -- Yes --> Draft Policy Summary --> Verify Summary
        | No                                                 |
        +<---------------------------------------------------+
        v
      Needs a brief? ---- Yes --> Draft Options Brief ---> Verify Brief
        | No                                                 |
        +<---------------------------------------------------+
        v
      Generate Review Report
        |
        v
      Human review after the run
```

## Worked example

When should a branch refer recurring use of generative AI in workplace software for formal assurance? The workflow drafted options and flagged claims for revision. The two-page Word brief adapts that report into a recommendation for the branch lead. [Original agent report](AI-ASSURANCE-TRIAGE-REPORT.md) · [Two-page Word brief](AI-Assurance-Triage-Options-Brief.docx)

## Project records

- [Workflow walkthrough and screenshots](WORKFLOW.md)
- [Node prompts and field mappings](docs/WORKFLOW-PROMPTS.md)
- [Test enquiries and recorded outputs](docs/WORKFLOW-TEST-REPORTS.md)


