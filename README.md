# Victor Zhang — AimPCB

PCB design, PCBA and box build at **Tianjin Huaxing Chengda Electronics Co., Ltd.** (brand: **AimPCB**).
We build boards for engineers in Europe and North America — prototype through volume, with the design review done before the stencil is cut.

Most of what we publish here comes out of real jobs: boards we were asked to quote, review, fix or manufacture. Schematics and layouts are shared only where we have the right to do so, and always with the customer's identifying details removed.

---

## Technical write-ups

### Flyback Power Supply PCB Design

A full engineering review of a real 12 V / 1 A offline isolated flyback converter — DK112 controller, EE19 transformer, SR3100 secondary rectifier, TL431 / PC817 feedback.

The topology is conventional and sound. The engineering data behind it was not: a 10 mil global clearance rule applied across the mains-to-SELV barrier, safety capacitors specified by voltage alone, a transformer called out only as "EE19 5+2", and an empty net stream that made net-aware DRC unusable.

The review covers primary-to-secondary isolation and creepage, switching-loop layout, component qualification, feedback-loop corners, thermal and EMI considerations, and a prioritised list of what must be fixed before a production release.

📄 **Read it:** https://aimpcb.com/blog/flyback-power-supply-pcb-design/
📝 **Outline and notes:** see the `pcb-engineering-notes` repository

---

## What we do

| Area | Link |
|---|---|
| PCB design | https://aimpcb.com/pcb-design/ |
| Schematic design | https://aimpcb.com/pcb-schematic-design/ |
| Layout design | https://aimpcb.com/pcb-layout-design/ |
| Design review & DFM | https://aimpcb.com/pcb-design-review-dfm/ |
| High-speed PCB design | https://aimpcb.com/high-speed-pcb-design/ |
| PCB fabrication | https://aimpcb.com/pcb-fabrication/ |
| SMT / THT / mixed assembly | https://aimpcb.com/pcb-assembly/ |
| Turnkey PCB assembly | https://aimpcb.com/turnkey-pcb-assembly/ |
| Component sourcing | https://aimpcb.com/electronic-component-sourcing/ |
| Testing & inspection | https://aimpcb.com/pcb-testing-inspection/ |
| Box build & OEM | https://aimpcb.com/box-build-oem/ |

---

## Contact

Site: https://aimpcb.com
Design review or quote: https://aimpcb.com/contact-us/
LinkedIn: https://www.linkedin.com/in/victor-grant-zhang-0516532ba/

Send a schematic, a layout, a Gerber set or just a description of what the board has to do. We will tell you what we would change before we tell you what it costs.
