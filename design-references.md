# Design References

Running list of sites/techniques worth revisiting for the portfolio.

## therawmaterials.com/hello

**URL:** https://www.therawmaterials.com/hello
**Added:** 2026-09-22

A scroll-driven "hello" section (numbered 01/05, section title "(Hello)") with a colored heading block — e.g. "Unusual Wins" on an orange background (`.hello-media-block.orangeBackground`).

**The technique to look at:** a Three.js (r150) `<canvas>` renders the actual 3D/WebGL scene but is kept invisible (`opacity: 0`) — visually, the canvas output is instead converted in real time into a colored monospace `<table>` overlay (Courier New, ~14px, -1px letter-spacing) sitting on top, i.e. the WebGL frame is being sampled and redrawn as an ASCII/character-grid art piece. Rest of the layout is a simple flex block: heading, section label, section counter.

Worth digging into for: an animated ASCII/text-art treatment on Home or a case-study hero, as a more distinctive alternative to the current mesh-gradient tile treatment.
