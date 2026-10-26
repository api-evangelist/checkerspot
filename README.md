# Checkerspot

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
