# InvariansLabs

**Blockchain infrastructure fails silently. Invarians makes it observable.**

Post-EIP-4844, L1 basefee is structurally decoupled from L2 activity. Sequencer incidents, bridge posting gaps, and structural stress produce no gas signature. Every fee monitor stays silent. Invarians detects them and signs the execution context the infrastructure was in at the moment an agent acted.

---

## What Invarians produces

**SxDx regime.** The structural state of a chain at observation time, derived from two independent axes (block cadence and demand pressure).

**BSx state.** The state of a bridge at observation time, native or CCIP or CCTP, calibrated per bridge.

**Signed execution context.** A panel of L1, L2 and bridge states, timestamped and HMAC-signed. On-chain anchor planned for Q2 2026 (InvariansAnchor on Arbitrum, then Chainlink DON threshold signing in Q4).

S2D1 is the reason Invarians exists: structural degradation with no demand signature, invisible to gas monitors. Detected, signed, verifiable.

---

## Public surfaces

**Panel API V1.0.0.** Two endpoints, panel-based and direction-agnostic. The agent composes its routes from a panel of states, Invarians does not impose direction.

**Labs.** A live observatory that publishes regime frequencies and agentic activity baselines per chain since 2026-03. Currently building rheological diagnostics on the σ load and ε deformation pair (Phase B.rheo, hysteresis diagnostic in progress).

**Public methodology.** Calibration scripts, backtests and methodology document published in [agentnorthstar/calibration](https://github.com/agentnorthstar/calibration). Methodology v0.5 covers L1 calibration, L2 calibration, native bridge thresholds (P97/30d uniform) and the 5-ratio deformation composite.

---

## Repositories

| Repo | Description |
|------|-------------|
| [invarians-py](https://github.com/InvariansLabs/invarians-py) | Python SDK, `pip install invarians` |
| [agentnorthstar/calibration](https://github.com/agentnorthstar/calibration) | Public methodology, backtests and reproducible scripts |

---

## Links

[invarians.com](https://invarians.com) · [agentic.invarians.com](https://agentic.invarians.com) · [labs.invarians.com](https://labs.invarians.com) · [API reference](https://invarians.com/developers.html)
