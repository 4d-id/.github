# 4D-ID™

### One persistent name for everything real. An open standard for spatial identity.

The web gave every document a name that worked across every browser and server. **4D-ID does the same for the physical world**: a persistent, self-minting identity for every object, surface, agent, and environment, physical or virtual. It survives movement, re-observation, vendor boundaries, and the boundary between real and virtual, so every system can agree on which thing it means while keeping its own coordinates.

> **Identities are shared and global, but what you can see and say about them is yours.**

**▶ Try it live at [4d-id.org](https://4d-id.org/)** — an interactive globe you can name the world on, plus a robot-and-drone building and a container-ship demo, all running real minted 4D-IDs.

## Repositories

| Repo | What it is |
|---|---|
| **[spec](https://github.com/4d-id/spec)** | The specification. Six parts, ~100 requirements, each with a test. Start here. |
| **[reference-resolver](https://github.com/4d-id/reference-resolver)** | A resolver you can run in an afternoon. Apache-2.0. |
| **[js-sdk](https://github.com/4d-id/js-sdk)** | The TypeScript / JavaScript client. `npm i @4d-id/js`. |
| **[demos](https://github.com/4d-id/demos)** | The interactive browser demos. |
| **[adapters](https://github.com/4d-id/adapters)** | Bridges to ROS 2 tf2, IFC, glTF, 3D Tiles, OpenXR. |
| **[conformance](https://github.com/4d-id/conformance)** | The conformance CLI: the badge that means "4D-ID compliant." |

## Four concepts

Identity, hierarchy, pose, time. Every other clause is a rule about how those four behave under a named pressure, or a binding to a standard that already exists (OGC GeoPose and DGGS, ISO 8601, OpenXR, glTF). 4D-ID is not a new coordinate system; it is the name that lets the ones we have agree.

## Open and permissionless

A 4D-ID is self-minting from a discrete global grid cell and a unique descriptor: no central registry, no gatekeeper, no fee. Resolution is delegated, in the manner of DNS, with no root anyone owns. The specification is intended to be royalty-free and contributed to a neutral standards body (OGC, with a Khronos liaison). See each repo's `GOVERNANCE.md`.

Apache-2.0 for the implementation, SDKs, schemas, and conformance suite.
