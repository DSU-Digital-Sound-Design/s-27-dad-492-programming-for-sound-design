+++
title = "What Is a Plugin?"
weight = 1
outputs = ["Reveal"]
[reveal_hugo]
margin = 0.2
+++

## What is a plugin?

- A small program that runs inside a DAW
- Audio goes in, gets changed, and comes out
- Knobs are **parameters** the DAW can save and automate

{{% note %}}

- Ask each student to name a plugin they use every session. Write the list on the board; we'll build most of it this semester.
- Point out that every plugin on the list is the same idea: numbers in, arithmetic, numbers out.

{{%/ note %}}

---

## What we'll build

- **Utility:** gain, pan, meter
- **Modulation:** tremolo, autopan, ring mod
- **Filters:** auto-wah, parametric EQ
- **Delay:** echo, chorus, flanger, phaser
- **Tone and dynamics:** distortion, bitcrusher, compressor, gate
- **Space:** reverb
- **Instruments:** a synthesizer

---

## And three of your own

1. A modulation effect (Project 1)
2. A hybrid effect (Project 2)
3. An effect or instrument of your choice (final project)

Each one is exported as a standalone plugin that anyone can load.

---

## plugdata

- A visual programming environment built on Pure Data
- You connect boxes (objects) with cables
- It runs on its own, or as a plugin inside REAPER

{{% note %}}

- Open plugdata inside REAPER and patch `[osc~ 220]` → `[*~ 0.1]` → `[dac~]` live. Turn it up slowly.
- Keep the demo under five minutes; the point is that sound comes out right away.

{{%/ note %}}

---

## Two ways to make a plugin

{{< slide-columns >}}
{{< slide-column title="Run the patch in plugdata" >}}
- Every object and library works
- Knobs reach the DAW through `[param]`
- Whoever uses it also needs plugdata
{{< /slide-column >}}
{{< slide-column title="Compile it with Heavy" >}}
- Exports a real VST3, AU, or CLAP
- Only some Pd vanilla objects are supported
- Turn on **Compiled Mode** to see which
{{< /slide-column >}}
{{< /slide-columns >}}

{{% note %}}

- We keep Compiled Mode on for most of the semester, so everything students build can be exported.
- The ELSE library is fine for sketching ideas but won't compile.

{{%/ note %}}

---

## This week

- **Wednesday:** install plugdata, REAPER, and the Heavy toolchain
- **Friday:** your first patch, running inside REAPER
- Bring headphones every class
