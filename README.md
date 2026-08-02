# Iontra

Iontra Inc. is a Denver, Colorado battery technology company developing proprietary
Charge-Control technology for rechargeable lithium batteries. Its electrodynamic sensing
and signal-processing approach suppresses lithium plating, dendrite growth and SEI-layer
expansion during charging, claiming up to 4x cycle life, 2x faster charging, improved
cold-weather charging and better safety without changing cell chemistry. Founded in 2013
and publicly launched in 2022, Iontra has raised $120.3M including a $45M Series C led by
Volta Energy Technologies, and is bringing an integrated RISC-V charge-control and
fuel-gauge microcontroller to production.

- Website: https://iontra.com/
- Secondary market: https://forgeglobal.com/iontra_stock/

## API surface — none

Iontra publishes **no public API**. Contract discovery on 2026-08-01 found no OpenAPI,
Swagger, GraphQL, AsyncAPI, MCP server, A2A agent card, `llms.txt`, `security.txt`,
`.well-known` catalog, public SDK package, status page or developer portal, on any host.

Iontra is an embedded/silicon company. What it calls an SDK is **firmware** — a charging
algorithm "recipe" built for a specific MCU and battery chemistry, delivered to OEM
customers under commercial engagement and distributed through a login-gated Document
Portal. Adoption is a services engagement (battery characterization, then product
integration), not self-service API onboarding. That absence is a real finding, not a gap
to be filled: no artifact in this repo asserts an API surface Iontra does not have.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `security/iontra-domain-security.yml` | DomainSecurity | probed |
| `well-known/iontra-well-known.yml` | (probe record, no pointer) | probed |
| `llms/iontra-llms.txt` | LLMsTxt | generated |
