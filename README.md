# Lamudi

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

Lamudi is an online real estate classifieds marketplace focused exclusively on emerging markets, founded in 2013. It operates consumer property portals in the Philippines ([lamudi.com.ph](https://www.lamudi.com.ph/)), Indonesia ([lamudi.co.id](https://www.lamudi.co.id/)) and Mexico ([lamudi.com.mx](https://www.lamudi.com.mx/)), covering houses, condominiums/apartments, land, commercial space and offices for sale and rent. Agencies and developers publish inventory through the `pro.lamudi.com` professional portal. Lamudi operates as part of LIFULL Connect, which supplies its legal notice, privacy policy and contact surface.

Backed by: hv-capital

## API surface

Lamudi publishes **no public developer API** — no developer portal, OpenAPI/GraphQL specification, SDK, CLI, MCP server, webhook or event surface, and no OAuth. No `/.well-known/` discovery document is served on any host, and no security.txt, status page, trust center or vulnerability disclosure program was found.

Its one notable machine-readable surface is a first-party **`llms.txt` on each country site**, served as `text/markdown`, documenting the URL grammar of its search (SERP), new-development and project pages for AI agents — property-group and operation slugs, geographic path structure, and worked example URLs.

## Artifacts

| Artifact | Path | Method |
|---|---|---|
| llms.txt (Philippines) | `llms/lamudi-ph-llms.txt` | searched |
| llms.txt (Indonesia) | `llms/lamudi-id-llms.txt` | searched |
| llms.txt (Mexico) | `llms/lamudi-mx-llms.txt` | searched |
| Well-known probe record | `well-known/lamudi-well-known.yml` | searched (all negative) |
| Domain security | `security/lamudi-domain-security.yml` | probed |
