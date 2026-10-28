# GoDaddy DNS control audit — public research edition

Grounded DI LLC's October 2026 research examines the GoDaddy CLI DNS set path at [commit 6aa64b60103d6c0807a3da9e4cde9380381e29a1](https://github.com/godaddy/cli/commit/6aa64b60103d6c0807a3da9e4cde9380381e29a1). This is independent research.

- [Public research book (PDF)](GoDaddy_Control_Audit_Public_Research_Edition.pdf) — original 23-page public-edition PDF; SHA-256 `79580e0490c41b2195aa2852f2a9f4ffe7437d62ee3c22e4468a38d45e506843`.
- [Machine-readable text companion](GoDaddy_Control_Audit_Public_Research_Edition.txt) — page-labeled text extracted from the PDF without OCR; reading order and tables may differ. The PDF governs visual layout.
- [Public release verification](Public_Release_Verification.json) — checks performed for this publication and their limits.
- [Checksums](SHA256SUMS.txt) — covers the three files above and this README; the checksum file excludes itself.

The book reports a visible partial update after a synthetic cleanup failure (OBS-01) and a final-state verification gap under a synthetic concurrent insertion (OBS-02). It also records favorable controls for a fresh retry, repeated invocation, and same-zone dispatch in the tested fixtures. These are historical local results; production impact or exploitation was not established. The complete underlying evidence archives, replay inputs and original release-verification record were not supplied for this publication review, and the tests were not rerun. This is not a standalone replay kit.

The PDF is preserved unchanged. Its references to owner review and not yet publishing describe its earlier preparation status; the owner subsequently requested this release. All 23 pages yielded extractable text. Checksums establish byte identity, not authorship or correctness.
