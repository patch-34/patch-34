# Aleksei Vorobev | Patch34

Sound designer, composer, and REAPER scripting enthusiast.

I make small tools for audio work: REAPER scripts, JSFX plugins, workflow utilities, and experiments that sit somewhere between practical automation and weird DAW-specific ideas.

Most of my projects grow out of real post-production work: repetitive actions, render workflows, custom UI needs, sound design utilities, and small problems that become tools.

---

## REAPER scripts & workflow tools

### [Reaper Ping](https://github.com/patch-34/reaper-ping)
Telegram notifications for REAPER renders. Opens REAPER’s Render dialog and sends a Telegram message when the render is finished.  
Script: [`Patch34 - Render with Telegram notification.lua`](https://github.com/patch-34/reaper-ping/blob/main/Patch34%20-%20Render%20with%20Telegram%20notification.lua)

### [Duplicate selected items to next measure](https://github.com/patch-34/duplicate-items-to-next-measure)
Duplicates selected media items one measure forward instead of placing the duplicate directly after the item edge. Useful for one-shots, drums, short sound-design events, and musical `Ctrl+D` behavior.  
Script: [`Patch34 - Duplicate selected items to next measure.lua`](https://github.com/patch-34/duplicate-items-to-next-measure/blob/main/Patch34%20-%20Duplicate%20selected%20items%20to%20next%20measure.lua)

### [Region Time Counter Mini](https://github.com/patch-34/region-time-counter-mini)
Minimal floating window that displays the total unique length of all project regions in `HH:MM:SS`, with correct overlap handling and no double-counting.  
Script: [`Patch34_Region_Time_Counter_Mini.lua`](https://github.com/patch-34/region-time-counter-mini/blob/main/Patch34_Region_Time_Counter_Mini.lua)

### [Find and Recolor Glued Items](https://github.com/patch-34/find-and-recolor-glued-items)
Captures an item name, finds glued derivatives across the project, recolors them, and can auto-color new glued items after Glue actions.  
Script: [`Patch34_Find_and_Recolor_Glued_Items.lua`](https://github.com/patch-34/find-and-recolor-glued-items/blob/main/Patch34_Find_and_Recolor_Glued_Items.lua)

### [Focus Blanket](https://github.com/patch-34/focus-blanket)
One-click listening mode for REAPER. Adds a full-screen “focus blanket” track to reduce visual noise while listening, then restores the previous view context when toggled off.  
Script: [`Patch34_Focus_Blanket.lua`](https://github.com/patch-34/focus-blanket/blob/main/Patch34_Focus_Blanket.lua)

### [Play 2s Before Next Marker or Region](https://github.com/patch-34/edit-play-2s-before-next-marker-or-region)
Seeks to two seconds before the next marker or region start. If transport is active, it seeks without stopping playback.  
Script: [`Patch34_Play_2s_Before_Next_Marker_Or_Region.lua`](https://github.com/patch-34/edit-play-2s-before-next-marker-or-region/blob/main/Patch34_Play_2s_Before_Next_Marker_Or_Region.lua)

### [Delete Nearest Marker to Cursor](https://github.com/patch-34/delete-nearest-marker-to-cursor)
Deletes the project marker closest to the edit cursor. Regions are ignored.  
Script: [`Patch34_Delete_Nearest_Marker_To_Cursor.lua`](https://github.com/patch-34/delete-nearest-marker-to-cursor/blob/main/Patch34_Delete_Nearest_Marker_To_Cursor.lua)

---

## REAPER experiments

### [REAPER Timeline Screensaver](https://github.com/patch-34/reaper-timeline-screensaver)
A useless-but-real REAPER screensaver script: media items move and change color in real time across a large timeline grid.  
Script: [`Patch34_REAPER_Timeline_Screensaver.lua`](https://github.com/patch-34/reaper-timeline-screensaver/blob/main/Patch34_REAPER_Timeline_Screensaver.lua)

### [REAPER Pixel Art Generator](https://github.com/patch-34/reaper-pixel-art)
Browser-based generator that turns images into Lua scripts for REAPER timeline pixel art.

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
