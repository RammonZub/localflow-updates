## [0.2.0] - 2026-05-08

- Rebuilt the app as a local-first macOS dictation tool.
- Added local speech model management for WhisperKit and FluidAudio/Parakeet.
- Added a compact floating HUD with push-to-talk and hands-free modes.
- Added local dictation history with search, copy, retry, and delete actions.
- Added model metrics logging for local runtime timing and memory snapshots.
- Added Model Lab mode to compare the same saved audio across up to two extra
  installed local speech models without changing the active paste model.
- Added a minimal dashboard with Home, Insights, Style, Transforms, Models,
  Metrics, and History.
- Added local ASR model notes covering Parakeet, WhisperKit, benchmarking, and
  the cleanup pipeline.
- Added a transcription pipeline audit from recent local history and improved
  deterministic cleanup for repeated words, repeated short phrases, and common
  engineering vocabulary corrections.
- Removed cloud-provider onboarding from the active app flow.
- Removed stale external app references and local dev branding.
- Removed the feature board and its local SQLite store.
- Added open-source contributor docs, CI, security policy, issue templates, and
  initial pure-logic tests.
- Moved API key persistence to Keychain with plaintext settings migration.
