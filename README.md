# Amazon MediaPackage (amazon-mediapackage)

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

AWS Elemental MediaPackage is a video origination and just-in-time packaging service that reliably prepares and protects video for delivery over the internet, creating multiple output formats from a single video input.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-mediapackage/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Broadcasting, Media Processing, Media

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon MediaPackage API
AWS Elemental MediaPackage is a video origination and just-in-time packaging service that reliably prepares and protects video for delivery over the internet, creating multiple output formats from a single video input.

**Human URL:** [https://aws.amazon.com/mediapackage/](https://aws.amazon.com/mediapackage/)

#### Tags:

 - Broadcasting, Media Processing, Media

#### Properties

- [Documentation](https://docs.aws.amazon.com/mediapackage/)
- [OpenAPI](openapi/amazon-mediapackage-openapi-original.yml)
- [GettingStarted](https://aws.amazon.com/mediapackage/getting-started/)
- [Pricing](https://aws.amazon.com/mediapackage/pricing/)
- [FAQ](https://aws.amazon.com/mediapackage/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/mediapackage/)
- [Documentation](https://docs.aws.amazon.com/mediapackage/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/media/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/mediapackage/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Just-in-Time Packaging | Package live video into HLS, DASH, CMAF, and Microsoft Smooth Streaming formats on demand. |
| Content Protection | Integrated DRM support with PlayReady, Widevine, FairPlay, and SPEKE standard. |
| Time-Shifted Viewing | Enable start-over, catch-up TV, and pause live TV with configurable time windows. |
| CDN Integration | Direct integration with CloudFront for scalable content delivery. |
| Harvest Jobs | Clip and archive live stream segments to S3 for VOD asset creation. |

## Use Cases

| Name | Description |
|------|-------------|
| Live OTT Streaming | Package live video for over-the-top delivery to mobile and connected devices. |
| Time-Shifted Television | Enable catch-up TV and start-over viewing experiences. |
| Multi-DRM Content Protection | Protect premium content with multiple DRM systems simultaneously. |
| Live Clipping | Create VOD clips from live streams for highlights and replays. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Elemental MediaLive | Receive live encoded streams from MediaLive for packaging. |
| Amazon CloudFront | Distribute packaged content globally via CloudFront CDN. |
| Amazon S3 | Store harvested clips and VOD assets in S3. |
| AWS Key Management Service | Manage DRM encryption keys with AWS KMS integration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon MediaPackage OpenAPI](openapi/amazon-mediapackage-openapi-original.yml)

### JSON Schema

- 76 schema files in [json-schema/](json-schema/)

### JSON Structure

- 76 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon MediaPackage API Context](json-ld/amazon-mediapackage-mediapackage-api-context.jsonld)

### Examples

- 76 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon MediaPackage](capabilities/shared/mediapackage.yaml) — 19 operations for media processing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon MediaPackage Workflow](capabilities/amazon-mediapackage-media-workflow.yaml) | Amazon MediaPackage | 8 | Broadcast Engineer |

## Vocabulary

- [Amazon MediaPackage Vocabulary](vocabulary/amazon-mediapackage-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon MediaPackage Spectral Rules](rules/amazon-mediapackage-spectral-rules.yml) — 20 rules across 8 categories enforcing Amazon MediaPackage API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
