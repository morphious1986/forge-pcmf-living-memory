# Forge PCMF / Living Memory

Deterministic persistent-memory engine for Linux with governed admission,
provenance, and owner authorization.

## Which public repository contains the source?

**Current sanitized native-source review:** [forge-pcmf-engine.](https://github.com/morphious1986/forge-pcmf-engine./pull/2)

- R17/R244 native source is already visible on the public
  `review/pcmf-r244-public-source-20261109` branch.
- [R244 community review PR #2](https://github.com/morphious1986/forge-pcmf-engine./pull/2)
  is open and **not merged** into `main`. It is a source-review candidate,
  **not** a stable release or an authorization to install.
- Separate experimental Control Center work:
  [PR #3](https://github.com/morphious1986/forge-pcmf-engine./pull/3).
- Separate synthetic memory-integrity benchmark:
  [PR #4](https://github.com/morphious1986/forge-pcmf-engine./pull/4).
- Separate sanitized language-semantics article:
  [PR #5](https://github.com/morphious1986/forge-pcmf-engine./pull/5).

This repository is retained as a **historical public project index**.
Do not assume its older package status describes the current native-source
review branch.

## Historical R16/R4 release candidate

The locally verified R16/R4 native offline archive was
`pcmf-living-memory-r16-r4-native-offline.tar.gz`, SHA-256
`3bdba83f8111497a6fd3392aad76edab2fb631944694cf3b2a99c61c99519186`
(recorded 2026-10-31). The offline archive has **not** been published here;
the historical documentation does not establish a public binary release.

The earlier USB file `PCMF_NATIVE_R13_GLM_HANDOFF_20261024.zip` is historical,
not the current engine source.

## Publication and operational boundaries

Public source visibility is distinct from review acceptance, stable release,
and local production deployment. Private memory records, keys, credentials,
user-specific configuration, historical operational data, and compiled
private packages must not enter a public repository. Only the owner and
governed local mechanisms can authorize changes to a live PCMF instance.

This is a documentation update only. No service, installation, or canonical
memory-writer state is changed.
