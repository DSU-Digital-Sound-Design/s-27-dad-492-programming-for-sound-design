---
title: "Hybrid Effect"
number: "02"
weight: 2
week: 9
assigned: "2027-03-12"
due: "2027-04-09"
summary: "Combine two or more building blocks (filter, delay, distortion, dynamics) into one original effect."
tools: ["plugdata", "Heavy", "REAPER"]
steps:
  - "Pick at least two building blocks from class and decide how they interact. One should change the behavior of the other, not just sit next to it in a chain."
  - "Draw the signal flow, including any feedback paths and where each parameter enters."
  - "Build it with Compiled Mode on."
  - "Tune the parameter ranges so every setting sounds usable."
  - "Export it and test it in REAPER, including automation of at least one parameter."
deliverables:
  - "The patch (.pd) and the exported plugin."
  - "A README with a block diagram, a description of each control, and two or three presets written as parameter values."
  - "A 60–90 second audio demo."
rubric:
  - key: "Design"
    weight: "30%"
    detail: "The building blocks interact in a way that makes a new kind of effect."
  - key: "Technical execution"
    weight: "40%"
    detail: "Stable at every setting: no clicks, runaway feedback, or clipping."
  - key: "Documentation and demo"
    weight: "30%"
    detail: "The diagram and README explain how it works and how to use it."
---

Examples: a delay whose repeats get more distorted each time, a filter whose
cutoff follows a compressor's gain reduction, or a reverb that ducks while you
play. You'll play your plugin for the group on the due date.
