# Linearity

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

Linearity GmbH is a Berlin-based design-technology company building AI-assisted design and animation software. Its flagship products are **Linearity Curve** (professional vector design, formerly Vectornator) and **Linearity Move** (animation and motion graphics), joined by an AI Design Generator that produces editable campaign assets from a text prompt.

Website: https://www.linearity.io/

## API surface

Linearity publishes **no public HTTP API, developer portal, or SDKs** as of July 2026. Probes of `/developers/`, `/api/`, `/docs/`, `api.linearity.io`, and `developer.linearity.io` found nothing; the help center documents only end-user features. Note that `www.linearity.io` answers every unknown path with HTTP 200 and an HTML shell, so status codes alone are not a reliable signal on this host — response bodies were inspected.

There is no GitHub organization for the company (`github.com/linearity` is an unrelated individual), and no first-party packages were found on npm or PyPI.

## Captured artifacts

| Artifact | File | Method |
|---|---|---|
| llms.txt | `llms/linearity-llms.txt` | searched (verbatim) |
| Changelog | `changelog/linearity-changelog.yml` | searched |
| Lifecycle | `lifecycle/linearity-lifecycle.yml` | searched |
| Well-Known | `well-known/linearity-well-known.yml` | searched (none found) |
| Domain security | `security/linearity-domain-security.yml` | probed |

Backed by: eqt-ventures, hv-capital
