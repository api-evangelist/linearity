# Linearity

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
