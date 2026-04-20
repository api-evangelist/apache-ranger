# Apache Ranger (apache-ranger)
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
