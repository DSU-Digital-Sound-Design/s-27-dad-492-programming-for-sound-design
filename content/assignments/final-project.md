---
title: "Final Project"
number: "03"
weight: 3
week: 13
assigned: "2027-04-09"
due: "2027-05-03"
summary: "An original effect or instrument, exported, documented, and presented at the final exam."
tools: ["plugdata", "Heavy", "REAPER"]
steps:
  - "Proposal (due 4/16): one page describing the plugin, who it's for, a block diagram, and the parameters you plan to expose."
  - "Prototype check-in (4/23): a working version, played for the group."
  - "Studio days: refine the interface and ranges, and test in more than one DAW."
  - "Final: export, document, and present."
deliverables:
  - "The patch (.pd) and the exported plugin in at least one format."
  - "A README with installation steps, a block diagram, a description of each control, and known issues."
  - "A 1–2 minute audio or video demo."
  - "A 5-minute presentation at the final exam."
rubric:
  - key: "Design"
    weight: "30%"
    detail: "An original idea, carried through to a plugin someone would want to use."
  - key: "Technical execution"
    weight: "35%"
    detail: "Exports and runs reliably, with considered parameter ranges and no audio problems."
  - key: "Documentation and demo"
    weight: "20%"
    detail: "Someone could install and use it from the README alone."
  - key: "Presentation"
    weight: "15%"
    detail: "Explains the idea, shows how it works inside, and plays convincing examples."
---

Design and build an original plugin: an effect, an instrument, or a procedural
sound generator. It can grow out of Project 1 or 2, but it should go well
beyond them. Instruments take MIDI input with `[notein]`; effects can sync to
the DAW tempo with `[r __hv_dpf_bpm]`.
