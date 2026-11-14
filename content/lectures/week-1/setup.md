---
title: "Setup: plugdata, REAPER, and the Heavy Toolchain"
summary: "Install everything you need for the semester and check that it works."
weight: 2
---

## 1. Start the Heavy toolchain download

The toolchain is large (around 1.5 GB), so start it first and let it run while
you do everything else.

<!-- TODO: add the exact menu steps for installing the toolchain in the current plugdata version. -->

## 2. Install plugdata

Download plugdata from [plugdata.org](https://plugdata.org/download.html) and
install both the standalone app and the plugin formats (VST3, AU on macOS, CLAP).

## 3. Install REAPER

Download [REAPER](https://www.reaper.fm/). The 60-day evaluation is fully
functional. Open it once, then rescan plugins so it finds plugdata.

## 4. Check that it works

1. In REAPER, create a track and add plugdata as an effect.
2. In the plugdata window, create `[osc~ 220]`, connect it to `[*~ 0.1]`, and connect that to both inlets of `[dac~]`.
3. Turn on DSP. You should hear a quiet sine wave.

## 5. Turn on Compiled Mode

Find the Compiled Mode toggle in plugdata's main menu and turn it on. Objects
that the Heavy compiler can't export are now outlined. Leave it on unless a lab
says otherwise.

## Troubleshooting

- **No sound:** check that DSP is on and that REAPER's audio device is set.
- **REAPER doesn't list plugdata:** rescan plugins in REAPER's preferences.
- **Export fails later:** make sure the export folder's path has no spaces in it.
