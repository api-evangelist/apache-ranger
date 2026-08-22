# Apache Ranger (apache-ranger)

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

Apache Ranger is a framework to enable, monitor, and manage comprehensive data security across the Hadoop platform. It provides centralized security administration for fine-grained authorization policies across Hadoop ecosystem components.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-ranger/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-ranger/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Access Control, Authorization, Hadoop, Policy Management, Security, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Ranger REST API
The Ranger REST API provides endpoints for policy management, service management, user/group management, audit log retrieval, and security zone administration, with plugin APIs for enforcing policies in HDFS, Hive, HBase, and other services.

**Human URL:** [https://ranger.apache.org/](https://ranger.apache.org/)

#### Tags:

 - Access Control, Policy Management, REST, Apache, Open Source

#### Properties

- [Documentation](https://ranger.apache.org/)
- [OpenAPI](openapi/apache-ranger-rest-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/ranger)
- [Documentation](https://ranger.apache.org/)
- [SpectralRules](rules/apache-ranger-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-ranger-vocabulary.yaml)
- [NaftikoCapability](capabilities/ranger-workflow.yaml)
- [JSON-LD](json-ld/apache-ranger-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Centralized Policy Management | Manage security policies for all Hadoop services from a single interface |
| Fine-Grained Access Control | Column-level, row-level, and data masking policies for Hive and HBase |
| Attribute-Based Access Control | Context-aware policies based on user attributes and tag classifications |
| Audit Logging | Comprehensive audit trail of all resource access events |
| Multi-Service Support | Supports HDFS, Hive, HBase, Kafka, Storm, Solr, Kudu, and more |
| LDAP/AD Integration | Sync users and groups from Active Directory or LDAP |
| Security Zones | Delegate policy administration with security zones |

## Use Cases

| Name | Description |
|------|-------------|
| Data Lake Security | Enforce column and row-level security on Hadoop data lake |
| Regulatory Compliance | Meet GDPR, HIPAA, and SOX requirements with audit logs and masking |
| Multi-Tenant Authorization | Isolate access between teams and business units |
| Kafka Topic Authorization | Control which applications can produce and consume Kafka topics |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop | Native HDFS and YARN authorization integration |
| Apache Hive | Column-level and row-level security for Hive queries |
| Apache HBase | Table and column family security for HBase |
| Apache Kafka | Topic-level authorization for Kafka producers and consumers |
| Apache Atlas | Tag-based policies using Atlas data classifications |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Ranger REST API](openapi/apache-ranger-rest-api.yaml)

### JSON Schema

- [Policy](json-schema/apache-ranger-policy-schema.json)
- [Ranger Service](json-schema/apache-ranger-ranger-service-schema.json)
- [Audit Entry](json-schema/apache-ranger-audit-entry-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache Ranger JSON Structures](json-structure/)

### JSON-LD

- [Apache Ranger Context](json-ld/apache-ranger-context.jsonld)

### Examples

- [Apache Ranger Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Security Policy Workflow](capabilities/ranger-workflow.yaml) | Apache Ranger | 8 | Security Administrator, Compliance Officer |

## Vocabulary

- [Apache Ranger Vocabulary](vocabulary/apache-ranger-vocabulary.yaml) — Unified taxonomy mapping security policy management resources, actions, workflows, and personas

## Rules

- [Apache Ranger Spectral Rules](rules/apache-ranger-spectral-rules.yml) — Rules enforcing Apache Ranger API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
