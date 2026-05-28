# Security

Sapien is currently a conceptual architecture with no working
implementation. There is no running code, no deployed system,
and no attack surface.

This document will be updated when implementation begins.

---

## When Implementation Exists

When Sapien moves to Phase 2 (prototype implementation),
security considerations will include:

**Knowledge graph integrity**
The DAG must be protected from unauthorized modification.
WHY chains and provenance records must be immutable once
created. Any tampering must be detectable.

This mirrors the philosophy of L_INKBook — the tamper-proof
logbook project that shares Sapien's author. Cryptographic
integrity verification for knowledge graph entries is a
planned future consideration.

**Teacher model access**
API keys and access credentials for frontier teacher models
must never be committed to the repository. Environment
variables only.

**Human oversight interface**
Any interface exposing the knowledge graph or oversight tools
must be access-controlled. Unauthorized modification of
human supervisor flags or verifier outputs would compromise
the entire integrity system.

**Open world learning sandbox**
When open world internet access is implemented, it must
operate in a sandboxed environment with controlled egress.
Unrestricted internet access for a learning system carries
obvious risks.

---

## Reporting a Vulnerability

When implementation exists, security vulnerabilities should
be reported privately before public disclosure.

Contact: admin.forestritium@gmail.com

Subject line: [SAPIEN SECURITY] Brief description

Do not open public GitHub issues for security vulnerabilities.

---

*Sapien — AGPLv3 — 28 May 2026*
*Author: Aarav — A Solo Engineer*
