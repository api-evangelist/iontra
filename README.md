# Iontra

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
