# temporal-agent-lab

Experimental playground: multi-agent orchestration on the Temporal Go SDK, with a chat UI that shows agents working in real time.

- **Orchestration:** Temporal (Go SDK) — one parent workflow per chat turn, one child workflow per sub-agent
- **UI:** Next.js chat with a live agent activity view
- **Realtime:** AnyCable pushes workflow and agent events to the browser
- **Runtime:** docker-compose

Example workflow: crypto research. Sub-agents gather news, funding and vesting, tokenomics, unlock schedule, current price, and price/volume across time windows, then a synthesizer produces a trend analysis for the coin.

Status: scaffolding, nothing runnable yet.
