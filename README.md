# RBAC (rbac)

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

Role-Based Access Control (RBAC) is a security paradigm that restricts system access based on assigned roles rather than individual user identities. Users are granted permissions through role membership, simplifying access management and ensuring the principle of least privilege. RBAC is foundational to enterprise identity, authorization, and compliance programs and is implemented across operating systems, cloud platforms, databases, and APIs.

The NIST/ANSI/INCITS 359-2004 standard formally defines the RBAC model across four components: Core RBAC, Hierarchical RBAC, Static Separation of Duty, and Dynamic Separation of Duty. Cloud platforms (AWS IAM, Azure RBAC, GCP IAM) and Kubernetes all implement RBAC natively, making it the de facto authorization standard for enterprise and cloud-native environments.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Access Control, Authorization, Cloud Native, Compliance, Identity Management, Kubernetes, RBAC, Security

## JSON Schemas

| Schema | Description |
|--------|-------------|
| [RBAC Role Schema](json-schema/rbac-role.json) | JSON Schema for an RBAC role |
| [RBAC Permission Schema](json-schema/rbac-permission.json) | JSON Schema for an RBAC permission |
| [RBAC Assignment Schema](json-schema/rbac-assignment.json) | JSON Schema for a role assignment |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [RBAC Role Structure](json-structure/rbac-role-structure.json) | Field-level documentation for the role object |
| [RBAC Permission Structure](json-structure/rbac-permission-structure.json) | Field-level documentation for the permission object |
| [RBAC Assignment Structure](json-structure/rbac-assignment-structure.json) | Field-level documentation for the role assignment object |

## JSON-LD Context

| Context | Description |
|---------|-------------|
| [RBAC Context](json-ld/rbac-context.jsonld) | JSON-LD context mapping RBAC vocabulary to linked data identifiers |

## Examples

| Example | Description |
|---------|-------------|
| [RBAC Role Example](examples/rbac-role-example.json) | Example role object (Content Editor) |
| [RBAC Permission Example](examples/rbac-permission-example.json) | Example permission object (Publish Content) |
| [RBAC Assignment Example](examples/rbac-assignment-example.json) | Example role assignment binding a user to a role |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [RBAC Vocabulary](vocabulary/rbac-vocabulary.yml) | Domain vocabulary covering RBAC concepts, terms, and implementation patterns |

## Standards & References

- [ANSI/INCITS 359 RBAC Standard (NIST)](https://csrc.nist.gov/projects/role-based-access-control)
- [Kubernetes RBAC Authorization](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)
- [AWS IAM RBAC Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html)

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
