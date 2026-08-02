# Checkerspot

Checkerspot is an Alameda, California biotechnology company, founded in 2016 and
incorporated as a Public Benefit Corporation, that designs and produces functional fats
and oils through precision fermentation of microalgae. Its biology-driven molecule
licensing platform pairs algal strain development, an advanced analytical platform,
bioinformatics, high-throughput screening, fermentation scale-up and downstream oil
refining, built around the proprietary microbe *Prototheca moriformis* — which the company
reports reaches over 80% oil content by dry cell weight against a 44% average across 150+
comparable organisms.

Molecule portfolio: **High sn-2 Palmitate Algal Oil** (a bio-equivalent of the fat in
maternal milk, for infant formula), **Omega-7 Algal Oil** (palmitoleic acid), **High Oleic
Palm Oil** (a designer tropical fat alternative), and **Algolein tG C18/80** (cosmetics).
Earlier work commercialized algae-derived urethane composites through the WNDR Alpine
outdoor brand. Partners include AAK, Huvepharma and La Fabrique Végétale. Checkerspot
closed a USD 55M Series C led by ArrowMark Partners with participation from Cox
Enterprises.

- https://www.checkerspot.com/
- https://forgeglobal.com/checkerspot_stock/

## API surface

**Checkerspot publishes no public API.** Contract discovery (2026-08-02) probed
`checkerspot.com`, `www.checkerspot.com` and every plausible API host for
OpenAPI/Swagger, GraphQL, MCP and A2A surfaces:

- `api.checkerspot.com`, `docs.checkerspot.com`, `developer.checkerspot.com`,
  `developers.checkerspot.com`, `app.checkerspot.com`, `status.checkerspot.com`,
  `trust.checkerspot.com`, `security.checkerspot.com` — all NXDOMAIN.
- `/openapi.json`, `/swagger.json`, `/api-docs`, `/graphql`, `/llms.txt` and every
  `/.well-known/*` path (including `agent-card.json` and the legacy `agent.json`) — all
  404 on both the apex and www hosts.
- No first-party packages on npm, PyPI, RubyGems, crates.io, Packagist or NuGet; no
  `checkerspot` GitHub organization (404).

The company sells business-to-business ingredients into infant nutrition, food and
personal care, so this is an expected and honest result — not a gap.

## What the site does publish

A stock WordPress marketing site (Rank Math SEO). The only machine-readable surfaces are
the sitemap index (`/sitemap_index.xml`, 200) and the RSS feed (`/feed/`, 200, wired as
`BlogRSS`). `robots.txt` (200) is the stock WordPress file — it only disallows
`/wp-admin/` and sets `Crawl-delay: 10`, naming no AI or answer-engine crawlers either
way. No `llms.txt` is published, so one was generated from the catalog.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `well-known/checkerspot-well-known.yml` | WellKnown | probed |
| `security/checkerspot-domain-security.yml` | DomainSecurity | probed |
| `packages/checkerspot-packages.yml` | Packages | searched (result: none) |
| `conformance/checkerspot-conformance.yml` | Conformance | searched |
| `llms/checkerspot-llms.txt` | LLMsTxt | generated |

No security.txt, no vulnerability-disclosure program, no trust center and no published
information-security certifications were found — so no `Security`, `Compliance` or
`TrustCenter` pointer is asserted. No `SDKs` pointer either. The applicable regulatory
regime is the FDA food-ingredient / GRAS pathway (recorded in `conformance/` as
in-progress, not achieved), which is a food-safety regime and does not earn a
`Compliance` pointer.
