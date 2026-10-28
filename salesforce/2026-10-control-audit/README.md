# Salesforce Agent Fabric control audit — public research edition

Grounded DI LLC's October 2026 independent research reviews selected Salesforce and MuleSoft public documentation and source, with historical local verification. The book identifies documentation gaps, configuration conditions, a narrow Terraform helper observation, and a Grounded DI verifier self-audit.

- [Public research book (PDF)](Salesforce_Agent_Fabric_Public_Research.pdf) — 18-page edition; SHA-256 `0e9cd208b187824e47aacd0616bcf781d5d93661afac1278c96baa7142c3674b`.
- [Machine-readable text companion](Salesforce_Agent_Fabric_Public_Research.txt) — page-labeled extraction; the PDF preserves the visual layout and source links.
- [Release verification](Public_Release_Verification.json) — checks performed for this edition and limitations.
- [Checksums](SHA256SUMS.txt) — covers this README and the three files above; excludes itself.

The book reports 12 Python source checks and nine isolated Go helper tests in the earlier publication review, and preserves the original Go runner's blocked status. Those populations have different targets and must not be pooled as product-control tests. No hosted Salesforce service, real billing event, or Terraform plan/apply was tested. The underlying evidence archives and replay inputs are not included, and historical tests were not rerun for this release.

The supplied PDF and corrected historical receipt remain unchanged. This edition updates the publication-status text, removes an unverified embedded Content Credentials attachment, and sets document metadata; see the verification record. All 18 pages yielded text. Checksums establish byte identity, not correctness or authorship.
