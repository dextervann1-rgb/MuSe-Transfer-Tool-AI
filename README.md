# MuSe Transfer Tool AI — Public Shell

This repository is the **sanitized public documentation and interface layer** for MuSe Transfer Tool AI. It describes a controlled pattern for repository mirroring, secret scanning, SHA-256 evidence, and explicitly approved distribution.

The owner-controlled implementation, private collaboration design, provider adapters, runtime configuration, repository source lists, credentials, teaching records, and operational artifacts are intentionally **not** included here.

## Public scope

| Included | Intentionally excluded |
| --- | --- |
| Architecture overview | Private MuSe core implementation |
| Non-secret interface contracts | Provider API keys, GitHub tokens, and Pinata credentials |
| Generic examples | Approved repository URLs and local configuration |
| Security boundaries and release principles | Teaching memory, collaboration records, and operational evidence |

## Design principle

> Callers may request an approved operation. The owner controls the systems, sources, credentials, destinations, and release decisions behind it.

The public shell is designed for transparency and discussion. It is not a hosted service, a credentialed deployment package, or a copy of the private MuSe AI collaboration workspace.

## What the system conceptually does

1. An owner approves a configured set of repository sources.
2. The implementation mirrors those sources and runs a redacted secret scan.
3. A clean scan permits SHA-256 manifest generation and checksum verification.
4. Optional distribution requires explicit owner approval and runtime-only credentials.

See [Public/private boundary](docs/PUBLIC_PRIVATE_BOUNDARY.md), [interface contract](api/openapi-shell.yaml), and [security guidance](docs/SECURITY.md).

## Release and rights notice

No public release should be treated as access to any private MuSe core, personal data, credentials, provider account, or unpublished artifact. A formal public license has not been selected for this shell; do not assume permission to reuse material beyond applicable law without the owner’s written authorization.
