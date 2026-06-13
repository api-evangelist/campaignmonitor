# Campaign Monitor (campaignmonitor)

Campaign Monitor is an email marketing platform with a REST API for managing campaigns, subscriber lists, transactional emails, segments, and accessing campaign performance analytics. The API (v3.3) is hosted at `https://api.createsend.com/api/v3.3/` and supports both API key and OAuth 2.0 authentication. Official SDK wrappers are available for PHP, Ruby, .NET, Python, Java, Perl, and Objective-C via the [campaignmonitor GitHub organization](https://github.com/campaignmonitor).

APIs.json: https://raw.githubusercontent.com/api-evangelist/campaignmonitor/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=campaignmonitor-api-evangelist&utm_content=repo

## Tags

- Email Marketing
- Campaigns
- Subscribers
- Transactional Email
- Segments
- Newsletters
- Automation

## APIs

### Campaign Monitor API

REST API covering ten primary areas: Account, Campaigns, Clients, Journeys, Lists, Segments, Subscribers, Templates, Transactional, and Webhooks. Responses are available in JSON or XML (transactional endpoints are JSON only).

- **Base URL:** https://api.createsend.com/api/v3.3/
- **Documentation:** https://www.campaignmonitor.com/api/
- **Authentication:** API Key (HTTP Basic Auth) or OAuth 2.0
- **GitHub SDKs:** https://github.com/campaignmonitor

## Plans, Rate Limits, and FinOps

- **Plans/Pricing:** [plans/campaignmonitor-plans-pricing.yml](plans/campaignmonitor-plans-pricing.yml) — Five tiers: Free Trial, Lite ($13/mo), Essentials ($31/mo), Premier ($171/mo), Enterprise (custom). All priced by active contact count.
- **Rate Limits:** [rate-limits/campaignmonitor-rate-limits.yml](rate-limits/campaignmonitor-rate-limits.yml) — Rate limiting applies to `/transactional` endpoints; HTTP 429 on exceeded limits with `X-RateLimit-*` headers.
- **FinOps:** [finops/campaignmonitor-finops.yml](finops/campaignmonitor-finops.yml) — FOCUS-aligned cost tracking covering contact-based billing, send limits, and cost optimization strategies.

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## Common

| Type | URL |
|------|-----|
| Website | https://www.campaignmonitor.com/ |
| Documentation | https://www.campaignmonitor.com/api/ |
| GitHub Org | https://github.com/campaignmonitor |
| LinkedIn | https://www.linkedin.com/company/campaign-monitor |
| Blog | https://www.campaignmonitor.com/blog/ |
| Pricing | https://www.campaignmonitor.com/pricing/ |
| Status Page | https://status.campaignmonitor.com/ |
| X | https://x.com/campaignmonitor |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
