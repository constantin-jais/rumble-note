# Product readiness cockpit

**Canonical date:** 2026-07-14  
**Snapshot:** `main@e0f66b4`  
**Maturity:** Specification  
**Availability:** discovery

This cockpit is the local source of truth for readiness. It reflects the repository’s documented boundary only; it does not claim a usable notebook runtime.

## Readiness summary

| Zone | Verdict | What we know |
| --- | --- | --- |
| prouvé | boundary / roadmap / security docs only | README, ROADMAP and SECURITY agree on local-first, private-by-default intent and on the current lack of runtime. |
| partiel | intentions | block-based capture/editing, explicit export, and privacy boundaries are described, but still at the specification level. |
| bloqué | runtime | there is no capture, editor, sync or export runtime yet. |
| later | post-gate scale-up | sync / multi-device only after encryption, conflict handling, and authorization are proven. |

## What is explicitly future work

- `NoteContextExport` is future work.
- No executable fixture exists yet for end-to-end validation.
- No block model exists yet beyond documentation intent.
- `0` open issue does **not** mean readiness.

## Gates

- **P0** — minimal block model + privacy export fixtures.
- **P1** — local capture / edit / export workflow.
- **P2** — sync / multi-device only after encryption, conflicts, and auth.

## Evidence anchors

- [README](../README.md)
- [Roadmap](../ROADMAP.md)
- [Security policy](../SECURITY.md)

## Notes

- This cockpit is dated and intentionally conservative.
- The goal is to keep the gap between documented intent and actual shipped capability visible.
