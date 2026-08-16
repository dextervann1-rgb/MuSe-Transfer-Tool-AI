# Public/Private Boundary

## Public shell purpose

The public shell exists to communicate non-sensitive architecture, interface concepts, and security expectations. It may contain generic examples that teach the intended control flow without exposing a live deployment.

## Private core purpose

The private MuSe core is the owner’s controlled workspace for non-public implementation, user-governed collaboration design, provider adapters, approved artifacts, and any integration that requires credentials or private context.

| Category | Public shell | Private core |
| --- | --- | --- |
| Architecture explanations | Yes, when sanitized | Yes |
| Interface signatures | Yes, generic and non-operational | Yes, with internal details as approved |
| Provider keys and tokens | Never | Runtime environment only; never committed |
| Repository source allow-list | Never | Ignored local configuration only |
| User feedback and teaching records | Never | Local/private storage only, with owner approval |
| Operational manifests and CIDs | Never by default | Retain only under owner-controlled policy |
| External write automation | Interface description only | Approval-gated implementation only |

## Release checklist

Before any material leaves the private core, the owner should confirm that it does not contain credentials, private URLs, personal information, third-party confidential material, hidden prompts, live configuration, unpublished operational evidence, or unreviewed provider output.

A public release should be a deliberate copy of selected sanitized material. It must never be an automatic synchronization of the private workspace.
