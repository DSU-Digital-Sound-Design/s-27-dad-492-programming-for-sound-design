---
title: "Schedule"
layout: schedule
---

Mondays introduce the idea, Wednesdays build it, and Fridays are studio days
for finishing, extending, and playing each other's plugins. Every plugin you
build in class goes into your [plugin portfolio](/assignments/plugin-portfolio/).

## 1/11
- Class introductions
  - Your name, your DAW, and one plugin you can't live without
- Review the [syllabus](/syllabus/) and expectations
- [slides] [What is a plugin?](/lectures/week-1/intro/)

## 1/13
- [lab] [Setup: plugdata, REAPER, and the Heavy toolchain](/lectures/week-1/setup/)
  - The toolchain download is large. Start it at the beginning of class.

## 1/15
- [lab] First patch: a sine wave with a volume control, inside REAPER
### homework
- [watch] [Sound Codex plugdata tutorials](https://youtube.com/playlist?list=PLZYD2Edyty0BfJ1RAH2heamjJGVj0TEau), the first few videos
- [reading] Kreidler, [*Loadbang*](http://www.pd-tutorial.com/english/index.html), the opening chapters on Pd basics

## 1/18
- [off] **No class — Martin Luther King Jr. Day**

## 1/20
- [slides] Messages and signals: hot and cold inlets, `[trigger]`, math objects
- [lab] **Utility plugin**: gain, pan, phase flip, mono
  - Expose each knob to the DAW with `[param]`

## 1/22
- [lab] Finish the utility plugin and automate it in REAPER

## 1/25
- [slides] Digital audio: samples, sample rate, amplitude and dB, clipping
- [reading] Puckette, [*Theory and Technique of Electronic Music*](https://msp.ucsd.edu/techniques.htm), ch. 1

## 1/27
- [lab] **Meter and trim**: measure level with `[env~]`, then trim to a target

## 1/29
- [slides] Aliasing: why some sounds fold back
- [lab] Studio: finish the meter and trim plugin

## 2/1
- [slides] Oscillators and LFOs: `[osc~]`, `[phasor~]`, rate and depth
- [reading] Puckette ch. 2

## 2/3
- [lab] **Tremolo and autopan**

## 2/5
- [lab] **Ring modulator**, then trade plugins and play each other's

## 2/8
- [slides] Compiled Mode and the Heavy compiler: what exports and what doesn't
  - `[r name @hv_param min max default]` turns a receive into a plugin parameter

## 2/10
- [lab] **First export**: compile the tremolo as a VST3/AU and load it in REAPER

## 2/12
- [lab] Studio: fix export problems
- [project] [Project 1: Modulation effect](/assignments/project-1-modulation/) assigned

## 2/15
- [off] **No class — Presidents Day**

## 2/17
- [slides] Filters I: low-pass, high-pass, band-pass, resonance
- [reading] Puckette ch. 8
- [lab] **Auto-wah**: a filter swept by an LFO and an envelope follower

## 2/19
- [lab] Studio: Project 1 work

## 2/22
- [slides] Filters II: `[biquad~]` and the Audio EQ Cookbook
- [reading] [Audio EQ Cookbook](https://www.w3.org/TR/audio-eq-cookbook/)

## 2/24
- [lab] **Parametric EQ** with shelving bands

## 2/26
- [due] [Project 1](/assignments/project-1-modulation/), played in class

## 3/1
- [slides] Delay lines: `[delwrite~]`, `[delread4~]`, and feedback
- [reading] Puckette ch. 7

## 3/3
- [lab] **Echo and ping-pong delay**, synced to the DAW tempo

## 3/5
- [lab] Studio: feedback tone, filtering the repeats

## 3/8
- [slides] Modulated delay: vibrato, chorus, flanger
- [lab] **Chorus and flanger**

## 3/10
- [slides] Allpass filters
- [lab] **Phaser**

## 3/12
- [lab] Studio: finish the modulated-delay plugins
- [project] [Project 2: Hybrid effect](/assignments/project-2-hybrid/) assigned

## 3/15
- [off] **No class — Spring break** (3/15–3/19)

## 3/22
- [slides] Nonlinear processing: waveshaping, saturation, bitcrushing
- [reading] Puckette ch. 5, the section on waveshaping

## 3/24
- [lab] **Distortion and bitcrusher**

## 3/26
- [off] **No class — Easter break**

## 3/29
- [slides] Dynamics: envelope followers and gain computers

## 3/31
- [lab] **Compressor**

## 4/2
- [lab] **Noise gate**, then studio time for Project 2

## 4/5
- [slides] Reverb: Schroeder, Freeverb, and feedback delay networks
- [reading] [Let's Write a Reverb](https://signalsmith-audio.co.uk/writing/2021/lets-write-a-reverb/), Signalsmith Audio

## 4/7
- [lab] **Reverb**

## 4/9
- [due] [Project 2](/assignments/project-2-hybrid/), played in class
- [project] [Final project](/assignments/final-project/) assigned

## 4/12
- [slides] Instruments: MIDI in, `[mtof]`, envelopes

## 4/14
- [lab] **Mono subtractive synth**

## 4/16
- [due] Final project proposal

## 4/19
- [slides] Polyphony and voice management
- [reading] Puckette ch. 4

## 4/21
- [lab] **Polyphonic synth or procedural sound generator**
- [reading] Farnell, *Designing Sound*, one practical of your choice

## 4/23
- Final project check-in: a working prototype, played for the group

## 4/26
- Final project studio: interface and parameter ranges

## 4/28
- Final project studio: testing in more than one DAW, CPU load

## 4/30
- Final project studio: export, README, and audio demo
- [due] [Plugin portfolio](/assignments/plugin-portfolio/)

## 5/3
- [due] [Final project](/assignments/final-project/) presentations at the scheduled final exam time
