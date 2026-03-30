# InvariansLabs

**Blockchain infrastructure fails silently. Invarians makes it observable.**

Post-EIP-4844, L1 basefee is structurally decoupled from L2 activity. Sequencer incidents, bridge posting gaps, and structural stress produce no gas signature. Every fee monitor stays silent. Invarians detects them — and certifies what the infrastructure looked like when your agent acted.

---

## What Invarians produces

**SxDx regime** — the structural state of the chain at observation time, derived from two independent axes: τ (block cadence) and π (demand pressure).

**Proof of Execution Context (PoEC)** — a signed attestation of L1 regime × L2 regime × Bridge state, timestamped and verifiable.

S2D1 is the reason Invarians exists: structural degradation with no demand signature, invisible to gas monitors. Detected. Signed. Certifiable.

---

## Repositories

| Repo | Description |
|------|-------------|
| [invarians-py](https://github.com/InvariansLabs/invarians-py) | Python SDK — `pip install invarians` |

---

## Links

[invarians.com](https://invarians.com) · [agentic.invarians.com](https://agentic.invarians.com) · [API reference](https://invarians.com/developers.html)
