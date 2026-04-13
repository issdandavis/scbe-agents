# SCBE Agents

> Agent runtime + HYDRA 6-agent swarm coordinator + MCP servers for the SCBE-AETHERMOORE ecosystem.

The bounded-teammate-AI layer. Each agent is scoped, policy-checked, and auditable.
HYDRA coordinates multiple agents as a swarm where each "head" is a Sacred Tongue
specialist (KO=Scout, AV=Vision, RU=Reader, CA=Clicker, UM=Typer, DR=Judge).

## Directory layout

- `agents/` — individual agent implementations + shared runtime
- `hydra/` — HYDRA swarm coordinator and the 6-head specialist system
- `mcp/` — Model Context Protocol servers

## Relationship to other SCBE repos

- **[SCBE-AETHERMOORE](https://github.com/issdandavis/SCBE-AETHERMOORE)** — the full governance framework
- **[scbe-tongues-toolchain](https://github.com/issdandavis/scbe-tongues-toolchain)** — assembler + VM for programs HYDRA agents can execute
- **[six-tongues-geoseal](https://github.com/issdandavis/six-tongues-geoseal)** — tokenization + sealed envelopes
- **[scbe-experiments](https://github.com/issdandavis/scbe-experiments)** — reproducible evaluation scripts

## HYDRA Agent Templates

A $29 one-time package of ready-made agent roles, packet patterns, and launch
structure is available at [aethermoore.com](https://aethermoore.com/product-manual/hydra-agent-templates.html).

## License

MIT
