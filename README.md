# Aleksei Vorobev | Patch34

Sound designer, composer, and REAPER scripting enthusiast.

I make small tools for audio work: REAPER scripts, JSFX plugins, workflow utilities, and experiments that sit somewhere between practical automation and weird DAW-specific ideas.

Most of my projects grow out of real post-production work: repetitive actions, render workflows, custom UI needs, sound design utilities, and small problems that become tools.

---

## REAPER scripts & workflow tools

### [Reaper Ping](https://github.com/patch-34/reaper-ping)
Telegram notifications for REAPER renders.

Runs REAPER’s Render dialog and sends a Telegram message when the render is finished. Useful for long exports, batch work, and render sessions where you do not want to keep checking the DAW manually.

### Region Time Counter
A REAPER utility for calculating the unique total duration of selected regions.

Built for editing, podcast production, and timeline analysis where overlapping regions, selected region sets, and real production timing matter more than simple item duration.

### Project Notepad
A small REAPER-side notepad for project-specific notes.

Designed for keeping session notes, reminders, production comments, and project context directly inside the DAW workflow.

### Small action scripts
Focused Lua scripts for repetitive REAPER actions: timeline editing, item duplication, render helpers, view/control utilities, and other workflow shortcuts.

---

## JSFX & sound tools

### [Patch34: Brickwall Limiter](https://github.com/patch-34/patch34-brickwall-limiter)
Sample-peak brickwall limiter for REAPER with a custom Escher-inspired JSFX interface.

### [Patch34: Raw Six](https://github.com/patch-34/raw-six)
Six-voice JSFX signal generator for procedural sound design, texture generation, tonal noise, drones, and experimental synthesis.

### [REAPER Pixel Art Generator](https://github.com/patch-34/reaper-pixel-art)
A browser-based generator that turns images into REAPER timeline pixel art by converting pixels into colored media items.

---

## Work in progress

### Patch34 UI Builder

A visual UI builder for REAPER scripts.

The goal is to make it easier to design ReaImGui-based interfaces without writing every layout detail by hand: place interface elements visually, define structure, and export Lua code with clear insertion points for script logic.

Current focus:
- visual layout building
- REAPER/ReaImGui-oriented UI structure
- exportable Lua scaffolding
- clearer separation between interface code and script logic
- helper layout elements such as child windows, groups, sections, and containers

This is still a work in progress, but it is becoming one of the main Patch34 directions.

---

## What I care about

- practical tools for real audio workflows
- REAPER automation
- small utilities that remove boring manual work
- experimental uses of DAWs
- custom interfaces for sound tools
- scripts that are useful, weird, or both

---

## Support

If you use these tools and want to say thanks:

[boosty.to/patch34/donate](https://boosty.to/patch34/donate)
