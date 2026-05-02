# RBAC (rbac)
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
