# 4D-ID™

### One persistent name for everything real. A candidate open standard for spatial identity.

Different systems can keep their own maps, coordinates, and internal IDs. Once an entity is grounded, 4D-ID gives them a shared way to refer to the same persistent thing. Grounding determines the referent; localization determines where it is; 4D-ID preserves which thing it is across systems and time.

4D-ID does not perform perception, localization, geometric registration, or rendering. Observations remain evidence, external matchers supply correspondence evidence, and authorized lifecycle decisions preserve reconciliation history.

> **Identities can be shared, while each deployment controls what it discloses and authorizes.**

**▶ Try the isolated demos at [4d-id.org](https://4d-id.org/)** — a browser sandbox of records created from caller-supplied grounding. Nothing there writes to a live namespace.

This profile describes a **candidate open standard**. It has no claimed industry adoption, standards-body adoption, or production deployment.

## Repositories

| Repo | What it is |
|---|---|
| **[spec](https://github.com/4d-id/spec)** | The specification. Six parts, ~100 requirements, each with a test. Start here. |
| **[reference-resolver](https://github.com/4d-id/reference-resolver)** | A resolver you can run in an afternoon. Apache-2.0. |
| **[js-sdk](https://github.com/4d-id/js-sdk)** | The TypeScript / JavaScript client. `npm i @4d-id/js`. |
| **[demos](https://github.com/4d-id/demos)** | The interactive browser demos. |
| **[adapters](https://github.com/4d-id/adapters)** | The IFC adapter is implemented; ROS 2 tf2, glTF, 3D Tiles, and OpenXR remain planned. |
| **[conformance](https://github.com/4d-id/conformance)** | Conformance diagnostics: exactly 15 schema-level checks pass; functional work continues. |

## Four concepts

Identity, hierarchy, pose, time. Every other clause is a rule about how those four behave under a named pressure, or a binding to a standard that already exists (OGC GeoPose and DGGS, ISO 8601, OpenXR, glTF). 4D-ID is not a new coordinate system; it is the name that lets the ones we have agree.

## Candidate, open, and not adopted

The specification is a candidate open standard, not an adopted standard. A 4D-ID can be syntactically generated from caller-supplied grounding and a descriptor; that syntax is not identity truth. The reference resolver has no built-in authentication, so production deployments must enforce authorization policy around lifecycle operations.

Apache-2.0 for the implementation, SDKs, schemas, and conformance suite.
