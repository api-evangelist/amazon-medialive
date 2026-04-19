# Amazon MediaLive (amazon-medialive)
AWS Elemental MediaLive is a broadcast-grade live video processing service that creates high-quality video streams for delivery to broadcast televisions and internet-connected multiscreen devices.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-medialive/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Broadcasting, Media Processing, Media

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon MediaLive API
AWS Elemental MediaLive is a broadcast-grade live video processing service that creates high-quality video streams for delivery to broadcast televisions and internet-connected multiscreen devices.

**Human URL:** [https://aws.amazon.com/medialive/](https://aws.amazon.com/medialive/)

#### Tags:

 - Broadcasting, Media Processing, Media

#### Properties

- [Documentation](https://docs.aws.amazon.com/medialive/)
- [OpenAPI](openapi/amazon-medialive-openapi-original.yml)
- [GettingStarted](https://aws.amazon.com/medialive/getting-started/)
- [Pricing](https://aws.amazon.com/medialive/pricing/)
- [FAQ](https://aws.amazon.com/medialive/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/medialive/)
- [Documentation](https://docs.aws.amazon.com/medialive/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/media/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/medialive/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Live Video Encoding | Broadcast-grade live video encoding supporting H.264, H.265, and other professional codecs. |
| Multiple Input Types | Accept live video from RTP, RTMP, HLS pull, MediaConnect, MP4, and other source types. |
| Redundant Encoding | Pipeline redundancy for high-availability live events with automatic failover. |
| Dynamic Ad Insertion Markers | Insert SCTE-35 markers for downstream ad replacement in live streams. |
| Multiple Output Groups | Deliver to HLS, DASH, RTMP, archive, UDP, MediaPackage, and other output destinations simultaneously. |
| Input Switching | Dynamically switch between input sources during a live event without interruption. |

## Use Cases

| Name | Description |
|------|-------------|
| Live Television Broadcast | Encode and deliver live TV channels with broadcast-grade quality. |
| Live Sports Streaming | Handle large-scale live sports events with redundant pipelines. |
| Live News Production | Create live news channel workflows with multi-source input switching. |
| Virtual Events | Stream virtual conferences, concerts, and entertainment events. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Elemental MediaConnect | Receive high-quality video transport feeds from MediaConnect. |
| AWS Elemental MediaPackage | Send encoded outputs to MediaPackage for adaptive bitrate packaging. |
| Amazon S3 | Archive live stream recordings to S3 for storage and later processing. |
| Amazon CloudWatch | Monitor channel health metrics and set alerts for live events. |
| Amazon EventBridge | Trigger workflows based on channel state change events. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon MediaLive OpenAPI](openapi/amazon-medialive-openapi-original.yml)

### JSON Schema

- 620 schema files in [json-schema/](json-schema/)

### JSON Structure

- 620 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon MediaLive API Context](json-ld/amazon-medialive-medialive-api-context.jsonld)

### Examples

- 620 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon MediaLive](capabilities/shared/medialive.yaml) — 59 operations for media processing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon MediaLive Workflow](capabilities/amazon-medialive-media-workflow.yaml) | Amazon MediaLive | 8 | Broadcast Engineer |

## Vocabulary

- [Amazon MediaLive Vocabulary](vocabulary/amazon-medialive-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon MediaLive Spectral Rules](rules/amazon-medialive-spectral-rules.yml) — 20 rules across 8 categories enforcing Amazon MediaLive API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
