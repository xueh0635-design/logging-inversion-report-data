# Logging inversion report visualization data

Public, immutable visualization shards for the advisor report website. These are simulated reference targets and saved model outputs, not field measurements.

- `noise-db/`: 900 profiles, four saved noise levels, two prediction systems.
- `c0-database/`: 500 previously used evaluation profiles.
- `manifest.json`: SHA-256 and byte count for every shard.

No model weights, research source code, original MAT files, credentials or complete experiment archives are included. The website fetches one profile at a time and checks SHA-256 before rendering. This repository provides existing experiment visualizations, not new evaluation or scientific acceptance.

- `uq-db/`: all 500 previously used evaluation profiles with the five frozen calibrated systems, original 200x80 geometry, and three diagnostic point masks. Values are lossless float64. No new inference, training or independent evaluation.
