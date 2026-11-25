# Feature and provenance overview

| Feature | Attribution / status |
|---|---|
| Drum synthesis foundation | Selected inherited Drumtonic code by Federico Ciapi |
| Ten instrument channels and 24 parameters | RTAL instrument configuration and integration; underlying DSP may be inherited |
| ESP32-S3 real-time integration | RTAL development |
| 480 × 272 touch editor | RTAL development |
| MIDI CC mapping and kit selection | RTAL integration |
| 128 SD kit slots | RTAL storage workflow |
| Ten-track sequencer, A/B/C/D, 16/32/64 steps | RTAL integrated sequencer, validated baseline |
| Velocity, accent, swing, step/live recording | Validated baseline |
| MIDI clock/transport and smoothed BPM | Validated baseline |
| 128 SD pattern slots and editing workflows | Validated baseline |
| Probability, ratchets, microtiming, locks, polymeter | V0.6A development; hardware validation pending |
| Song mode and performance extensions | Planned |
| WAV-to-synthesis matching | Separate experimental RTAL prototype |

This is a functional attribution overview, not a source-code diff. Exact inherited versus modified algorithms require a comparison against the upstream commit.
