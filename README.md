# LaunchRock

Launchrock is a hosted launch-page and customer-acquisition tool for early-stage founders — a
drag-and-drop builder for pre-launch marketing pages with email capture, referral and sharing
mechanics, and simple surveys, so a founder can collect a waitlist before a product ships. It is
operated as one product line of the Startups.com platform, alongside Fundable, Bizplan and
Clarity.fm.

- Website: https://www.launchrock.com/
- Help center: https://help.startups.com/knowledge/launchrock
- Backed by: 500-global

## API status — no public API

As of the 2026-07-19 enrichment pass, Launchrock publishes **no public API**: no developer portal,
API reference, OpenAPI or AsyncAPI description, SDKs, CLI, Postman collection, webhook catalog or
sandbox. `/api`, `/docs`, `/developers`, `/developer`, `/blog`, `/changelog` and `/status` all
return 404, no `/.well-known/` documents or `/llms.txt` are served, and the `api.`, `developers.`,
`developer.`, `docs.`, `status.`, `trust.` and `blog.` subdomains are either 404, wildcard DNS onto
the Startups.com site cluster, or dead legacy hosts. Delivery is entirely through the hosted web
application.

## Artifacts

| Artifact | File |
|---|---|
| APIs.json profile | `apis.yml` |
| Domain security (probed) | `security/launchrock-domain-security.yml` |
| Well-known / discovery probe | `well-known/launchrock-well-known.yml` |
| llms.txt | `llms/launchrock-llms.txt` |
