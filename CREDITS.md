# Credits

Praman was built by a small team working with AI coding agents.

## People
- **Dhananjai Pratap** ([@duperdj](https://github.com/duperdj)) — backend / decision-lane direction, integration, deployment
- **Soham Shahapure** ([@SohamShahapure](https://github.com/SohamShahapure)) — frontend / UI, service catalog, screens

## AI agents
- **Codex** (OpenAI, `gpt-5.6-sol`) — authored and audited the **decision engine** (`lib/engine/`): the 8 issuance rules, the scoring model, and the deterministic evaluation pass, plus the working-day SLA math review.

All data in this project is **synthetic**. No real Aadhaar, Samagra, or personal
data appears anywhere in the repo; Aadhaar-like numbers are constructed to fail
the Verhoeff checksum so they can never collide with a real identifier.
