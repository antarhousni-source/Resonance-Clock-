# The Resonance Clock

A single-file, zero-dependency HTML instrument that reimagines the 24-hour day through a 9-phase resonance cycle.

## What it does

The Resonance Clock divides a standard day into **9 phases** of 2 hours 40 minutes each, with each phase containing **6 pulses** (26 min 40 s) and each pulse containing **10 ticks** (160 s). The result is a continuous, cyclical time display that feels more like a tide gauge or an analog synthesizer than a conventional clock.

## Features

- **Analog dial** with triad color bands (Charge / Surge / Ground) and a smooth sweep needle
- **Live readouts** for Resonance Time (`Phase.Pulse.Tick`) and standard reference time
- **Timezone selector** with support for major cities and UTC
- **Phase-change flash** and optional audio cues (tick clicks & phase tones)
- **Accessibility**: live region announcements, reduced-motion support, keyboard-focusable controls
- **Responsive** layout that works from 360 px mobile up to desktop
- **Zero dependencies** — runs entirely in the browser from a single HTML file

## How to use

1. Open `resonance-clock.html` in any modern browser.
2. Select your anchor timezone from the dropdown.
3. Toggle sound on/off to hear subtle phase and tick cues.
4. Watch the dial, pulse dots, and tick bar update in real time.

## Time structure

| Unit | Count | Duration |
|------|-------|----------|
| 1 cycle | 9 phases | 24 hours |
| 1 phase | 6 pulses | 2 h 40 m |
| 1 pulse | 10 ticks | 26 m 40 s |
| 1 tick | — | 160 s |

## Design

- **Typography**: Fraunces (serif) + Space Mono
- **Palette**: Deep brass, amber, teal, and ivory on a dark panel background
- **Aesthetic**: Vintage instrument panel with screw heads, radial gradients, and subtle glow effects

## License

MIT
