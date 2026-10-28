# Microsoft control audit and harness hardening — public research edition

Grounded DI LLC's October 2026 companion examines local DI² v0.3.1 hardening and a separately labeled mirror of selected Microsoft Agent Governance Toolkit code at [commit bb9fd0df2aed2969a403b6d083c34185cad0eb04](https://github.com/microsoft/agent-governance-toolkit/commit/bb9fd0df2aed2969a403b6d083c34185cad0eb04). This is independent research.

- [Public research book (PDF)](Microsoft_Control_Audit_Harness_Hardening_Public_Edition.pdf) — six-page public edition; SHA-256 `268d13a2497d48682aa96595afcdf58d00cf0a0a934f4d0b881074bfc12b3486`.
- [Machine-readable text companion](Microsoft_Control_Audit_Harness_Hardening_Public_Edition.txt) — page-labeled extraction without OCR; the PDF governs layout.
- [Release verification](Public_Release_Verification.json) and [checksums](SHA256SUMS.txt) — current package checks; the checksum list excludes itself.

The book reports 216 upstream passes and 11 skips, and a separate local mirror registry with 25 Microsoft passes and 13 failed safety assertions across five groups. It preserves passing controls, audit corrections, and limitations. The book also describes earlier screenshot-based demonstrations; those counts are separate. The later [fresh-rerun exhibit](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry/tree/main/benchmarks/2026-10-21-microsoft-di2-v031-fresh-rerun) reports a distinct 64-pass, 16-failure sidecar population; do not combine the populations.

The [source-attribution correction](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry/blob/main/benchmarks/2026-10-21-microsoft-di2-v031-fresh-rerun/Source_Attribution_Correction.md) explains a repository-name error in the later exhibit and the remaining execution-receipt boundary. The [earlier demos text](https://github.com/Grounded-DI/START_HERE_DI_EXHIBIT_BOOKS/blob/main/Grounded_DI_Two_Deterministic_Control_Demos_Book_2026-10-21.md) is maintained separately.

Results are historical local observations, not live-service or Microsoft-wide findings. The research evidence and replay inputs are not included in this directory; tests were not rerun for this release. All six pages yielded extractable text. Checksums establish byte identity, not correctness or authorship.
