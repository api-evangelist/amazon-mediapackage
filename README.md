# Amazon MediaPackage (amazon-mediapackage)
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
