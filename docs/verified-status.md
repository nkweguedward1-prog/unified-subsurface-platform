# Verified Implementation Status

This document separates demonstrated implementation from roadmap intent. It is a portfolio record, not a claim of field deployment or commercial-product parity.

## Implemented and audited

### WP-01 — Canonical Model

- Immutable revisions and exact entity references
- Dependency tracking and stale-state propagation
- SQLite persistence and migrations
- Validation, provenance and array references
- Database-level hardening, including cycle protection

### WP-02 — Engine Services

- Neutral adapter protocols for scientific engines
- Capability discovery
- Job lifecycle and cancellation
- Runtime metadata validation
- Provenance and audit context
- Mock adapters and representative workflow tests

### WP-03 — Desktop Shell

- Desktop application lifecycle
- Project and session persistence
- Command registry
- Selection state with undo/redo
- Global selection, job presentation and messages
- Shutdown, reload and malformed-session handling

### WP-04 — Visualisation

- Engine-neutral scene and layer model
- VTK-backed 2D, 3D and cross-section views
- Picking, colour maps and clipping
- Strict validation and resource cleanup
- Transform metadata and stale-pick handling

## Implemented and qualified

### WP-05 — XTGeo Layer

- Neutral grids, properties, surfaces and trajectories
- ROFF, EGRID and GRDECL interchange paths
- Checksums and provenance
- Atomic writes and loss detection
- Known limitation: NNC support was not qualified in the recorded milestone

### WP-06 — Structural Modelling

- Common structural-engine interface
- GemPy and LoopStructural adapters
- Input validation and coordinate transforms
- Cross-engine comparison
- Stratigraphic-relationship support remained experimental in the recorded milestone

## Important limitations

The public showcase does not claim:

- Complete Petrel or ECLIPSE replacement parity
- Field calibration or operational deployment
- Production-scale performance
- Integration with proprietary licensed interfaces
- Completion of every roadmap work package
- That planned engines are already qualified or exposed in the UI

## Evidence policy

A capability should be described as implemented only when supported by source, executed tests, audit records, qualification evidence or a reproducible demonstration. Planned architecture is labelled separately.
