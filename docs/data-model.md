# Data model (draft)

- **Source:** publisher/owner, canonical URL or identifier, retrieval timestamp, access method, rights/authorization notes.
- **Artifact:** original bytes or controlled reference, media type, size, cryptographic digest, storage locator.
- **Observation:** direct tool observation, tool/version/configuration, timestamp.
- **Assertion:** analyst interpretation, confidence, supporting observations.
- **Transformation:** parser/converter, version, parameters, input/output digests, errors.
- **Decision:** accept, quarantine, reject, or defer, with reason and reviewer.

A digest supports byte-integrity checks only; it does not prove source identity, authenticity, accuracy, or completeness. Preserve uncertainty and negative results.