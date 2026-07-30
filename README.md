# Lamudi

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
