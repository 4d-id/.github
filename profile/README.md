# 4D-ID™

### One persistent name for everything real. A working draft offered for community review.

Different systems can keep their own maps, coordinates, and internal IDs. Once an entity is grounded, 4D-ID gives them a shared way to refer to the same persistent thing. Grounding determines the referent; localization determines where it is; 4D-ID preserves which thing it is across systems and time.

4D-ID does not perform perception, localization, geometric registration, or rendering. Observations remain evidence, external matchers supply correspondence evidence, and authorized lifecycle decisions preserve reconciliation history.

> **Identities can be shared, while each deployment controls what it discloses and authorizes.**

**▶ Try the isolated demos at [4d-id.org](https://4d-id.org/)** — a browser sandbox of records created from caller-supplied grounding. Nothing there writes to a live namespace.

This profile describes a **working draft offered for community review**. It has no claimed industry adoption, standards-body adoption, or production deployment.

## Repositories

| Repo | What it is |
|---|---|
| **[spec](https://github.com/4d-id/spec)** | The specification. Six parts, ~100 requirements, each with a test. Start here. |
| **[reference-resolver](https://github.com/4d-id/reference-resolver)** | A resolver you can run in an afternoon. Apache-2.0. |
| **[js-sdk](https://github.com/4d-id/js-sdk)** | The TypeScript / JavaScript client. `npm i @4d-id/js`. |
| **[demos](https://github.com/4d-id/demos)** | The interactive browser demos. |
| **[adapters](https://github.com/4d-id/adapters)** | Implemented reference adapters for IFC and Overture GERS; other integrations remain planned. |
| **[conformance](https://github.com/4d-id/conformance)** | Partial diagnostics: 15 schema checks implemented of 112 defined; functional work continues. |

Adapters currently implemented: IFC and Overture GERS.

## Four concepts

Identity, hierarchy, pose, time. Every other clause is a rule about how those four behave under a named pressure, or a binding to a standard that already exists (OGC GeoPose and DGGS, ISO 8601, OpenXR, glTF). 4D-ID is not a new coordinate system; it is the name that lets the ones we have agree.

## Working draft, open, and not adopted

The specification is a working draft offered for community review, not an adopted standard. A 4D-ID can be syntactically generated from caller-supplied grounding and a descriptor; that syntax is not identity truth. The reference resolver has no built-in authentication, so production deployments must enforce authorization policy around lifecycle operations.

A DGGS cell routes, partitions, and filters spatial records. It may appear as immutable genesis metadata in the spatial identifier form, but it is not the identity and it is not the entity's current location. The 2.4 draft also defines a non-spatial privacy mode.

Apache-2.0 for the implementation, SDKs, schemas, and conformance suite.
