
# 🎛 ToneSmith Deck

## A Professional DIY MIDI Creative Control Surface

ToneSmith Deck is a high-input, USB-MIDI control surface designed to provide fast, tactile access to creative software controls.

Built around an Arduino Pro Micro and analog multiplexing, ToneSmith Deck replaces repetitive mouse work with precise physical interaction — accelerating editing, sound design, and parameter control workflows.

# 🚀 Project Vision

Professional creative controllers often cost $300–$600.
ToneSmith Deck aims to deliver similar functionality at a significantly lower cost while remaining fully customizable and open-source friendly.

The goal is simple:

* Make advanced control accessible
* Minimize mouse usage
* Improve workflow speed
* Deliver professional-grade tactile feedback
* Keep the system affordable and reproducible

---

# ✨ Key Features

* 48 total hardware inputs
* 32 precision 10k potentiometers
* 16 programmable buttons
* USB plug-and-play MIDI output
* Multi-profile workflow support (HSL / Custom / DAW mapping)
* Copy / Paste parameter support
* Navigation controls
* Undo / Redo functionality
* Expandable firmware
* Custom PCB design
* 3D printable enclosure
* Fully customizable labels and control layout

---

# 🧠 Technical Overview

ToneSmith Deck uses:

* Arduino Pro Micro (USB HID enabled)
* 3× CD74HC4067 multiplexers (48 total inputs)
* Control Surface Arduino library
* USB MIDI protocol
* Custom PCB (Gerber files included)
* 3D printed enclosure

The device connects via USB and is recognized by the system as a standard MIDI controller.

---

# 🛠 Hardware Components & Cost Breakdown

| Component                | Quantity | Estimated Cost (USD) |
| ------------------------ | -------- | -------------------- |
| Arduino Pro Micro        | 1        | $12                  |
| CD74HC4067 Multiplexer   | 3        | $15                  |
| 10k RV09 Potentiometers  | 32       | $48                  |
| Tactile/Silicone Buttons | 16       | $20                  |
| Custom PCB (JLCPCB)      | 1        | $40                  |
| 3D Printed Case (PLA)    | 1        | $35                  |
| Knobs & Button Caps      | 48       | $45                  |
| Wiring, headers, screws  | —        | $25                  |
| Sticker printing         | —        | $10                  |

### 💰 Total Estimated Build Cost:

**≈ $250**

---

# 💼 Market Comparison & Value

Comparable creative MIDI controllers typically cost:

* $300 – $600 (commercial alternatives)

ToneSmith Deck estimated value:
**$349 – $379**

This pricing reflects:

* Hardware cost
* Assembly time
* Firmware setup
* Customization flexibility
* Design and documentation work

---

# 🖨 Enclosure & Assembly

## Assembly Steps

1. Mount PCB inside base enclosure
2. Install potentiometers
3. Install buttons and supports
4. Close top enclosure
5. Attach knobs and caps
6. Connect via USB and test

Optional finishing:

* Sanding and painting enclosure
* Custom label design
* Enhanced aesthetic finishing

---

# ⚙ Software Setup

## Requirements

* Arduino IDE
* Control Surface library

## Lightroom Workflow (Optional)

1. Install MIDI2LR plugin
2. Load provided XML profiles
3. Connect device
4. Select desired profile (Hue / Lum / Sat)
5. Begin editing

## DAW Workflow

ToneSmith Deck outputs standard MIDI CC messages and can be mapped in:

* Ableton
* FL Studio
* Logic Pro
* Any MIDI-compatible software

Mapping is done directly inside the DAW.


# 🔍 Innovation & Educational Value

ToneSmith Deck demonstrates:

* Analog signal multiplexing
* MIDI communication protocol
* Embedded firmware design
* Custom PCB manufacturing workflow
* 3D mechanical design
* Open-source hardware adaptation

The project integrates electrical engineering, firmware programming, mechanical design, and workflow optimization into a single cohesive system.

# 📈 Future Expansion

Planned upgrades:

* OLED display integration
* RGB backlighting
* Rotary encoders (in place of standard potentiometers)
* Profile selection hardware switch
* Custom firmware UI
* Premium enclosure materials

---

# 🎯 Conclusion

ToneSmith Deck proves that professional creative control hardware can be:

* Affordable
* Customizable
* Expandable
* Educational
* Open-source friendly

It transforms repetitive digital workflows into tactile, efficient creative experiences.
