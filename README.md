# Sentala Hardware Engineer Take-Home
## Solar-Charged Off-Grid Sensor Node

Candidate: Jyotiraditya Ingawale

This archive contains my Rev A design for the Sentala solar-powered environmental sensing node take-home evaluation.

## Contents

- `Sentala_TakeHome_Writeup_Jyotiraditya_Ingawale.pdf`
  Design rationale, calculations, assumptions, PCB floorplan, firmware sequencing, standards considerations, and validation plan.

- `Sentala_Schematic.pdf`
  Exported complete hierarchical schematic.

- `BOM.csv`
  Preliminary BOM with manufacturer part numbers where finalized.

- `KiCad/`
  KiCad project and schematic source files.

## Scope

The design was intentionally time-boxed to approximately six hours.

I prioritized:
- system architecture
- charging and battery safety
- power-path design
- power and energy sizing
- thermal and environmental considerations
- fault handling
- schematic implementation
- remote diagnosability

Detailed PCB routing, manufacturing outputs, enclosure CAD, exhaustive passive optimization, and formal qualification were intentionally left outside the time box.

Items not fully selected are clearly marked:

`TBD — not finalized within time box`

## Tools

I used manufacturer datasheets, TI reference designs, KiCad, and an AI assistant during drafting and design review.

Critical design decisions were cross-checked against manufacturer documentation.

See `Sentala_TakeHome_Writeup_Jyotiraditya_Ingawale.pdf` for the full design discussion.