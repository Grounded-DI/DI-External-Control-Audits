# Google ADK confirmation control audit — public research edition

Grounded DI LLC examined tool confirmation and callback ordering in Google ADK Python at [commit 4c66a009106cbb855a79f4dc7383712057212e1e](https://github.com/google/adk-python/commit/4c66a009106cbb855a79f4dc7383712057212e1e). This is independent research based on local synthetic tests.

- [Public research book (PDF)](Google_ADK_Public_Research.pdf)
- [Machine-readable text companion](Google_ADK_Public_Research.txt)
- [Public release verification](Public_Release_Verification.json)
- [Checksums](SHA256SUMS.txt)

The tests exercised an in-memory runner, mock model, synthetic tool, and deliberately configured application callbacks. An unchanged approval and rejection behaved as expected. When a callback changed tool arguments on resume, the synthetic action reflected changed arguments; in a conditional-confirmation case, it was recorded after rejection when the changed arguments no longer met the condition. These observations require the tested callback configuration; no external compromise, real-world transaction, production deployment, or managed-gateway failure was demonstrated. The PDF is the visual source; text extraction may differ in reading order. The underlying internal evidence is not included, so this public package is not a standalone replay kit.
