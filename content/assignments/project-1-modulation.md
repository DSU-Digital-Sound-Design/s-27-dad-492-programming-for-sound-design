---
title: "Modulation Effect"
number: "01"
weight: 1
week: 5
assigned: "2027-02-12"
due: "2027-02-26"
summary: "Design an original effect built on modulation, and export it as a standalone plugin."
tools: ["plugdata", "Heavy", "REAPER"]
steps:
  - "Listen to modulation effects you like and write down what moves in each one: volume, pitch, pan, or tone."
  - "Sketch your effect as a block diagram before you patch it."
  - "Build it in plugdata with Compiled Mode on, so you only use objects that export."
  - "Give it three to six parameters with sensible ranges and defaults."
  - "Export it with Heavy and test it in REAPER on at least two kinds of material."
deliverables:
  - "The patch (.pd) and the exported plugin."
  - "A short README: what it does, what each control does, and a suggested starting setting."
  - "A 30–60 second audio demo."
rubric:
  - key: "Design"
    weight: "30%"
    detail: "The effect has a clear idea, and its controls serve that idea."
  - key: "Technical execution"
    weight: "40%"
    detail: "It exports, loads, and runs without clicks, dropouts, or runaway levels."
  - key: "Documentation and demo"
    weight: "30%"
    detail: "Someone else could pick it up and use it from the README alone."
---

Using the oscillators, LFOs, and gain changes from the first five weeks,
design a modulation effect that doesn't exist yet. It could be a tremolo with a
strange LFO shape, an autopanner that follows the input level, or a ring
modulator tuned to the notes of a scale. Your plugin must be yours: start from
a sound you want, not from the in-class patch.

You'll play your plugin for the group on the due date. Bring a track that
shows what it can do.
