# Voron 2.4 R2 — Graduation Project Build



This repository documents the project's mechanical assembly, electronics integration and software setup. The printer uses the existing **Voron Design** platform. The team's work focused on building and integrating the system, with my primary responsibility being **software installation**.

## Project overview

| Item | Project details |
|---|---|
| Platform | Voron 2.4 R2 |
| Nominal print volume | 300 × 300 × 300 mm, as specified in the project documents |
| Host computer | Raspberry Pi; model not recorded in this repository |
| Controller | BIGTREETECH Octopus V1.1 |
| Software | MainsailOS, Mainsail and Klipper |
| Network connection documented | Ethernet |
| Academic context | Bachelor-level graduation project, 2022 |
| Supervisor | Dr. Jaber Yamani |

## My contribution

My assigned role in the final report was **software installation**. The software workflow documented in the report covers:

- Preparing the Raspberry Pi SD card using Raspberry Pi Imager.
- Installing MainsailOS and accessing the Mainsail web interface.
- Preparing Klipper firmware for the Octopus controller and transferring the firmware using an SD card.
- Creating `printer.cfg` from the official Voron configuration and identifying build-specific settings to change.
- Connecting the Raspberry Pi to the network over Ethernet for setup and access.

These activities used existing software and official configuration templates. This project does not claim original development of Voron, Klipper or Mainsail.

## Build documented in the report

### Mechanical assembly

The report covers the frame, Z drives and idlers, A/B drives, gantry, linear rails, belts, toolhead, cable chains and exhaust assembly. Assembly followed the Voron platform and its supporting documentation.

### Electronics integration

The build incorporates a Raspberry Pi, Octopus V1.1 controller, power supplies, a solid-state relay, motors, heaters and fans. The report documents wiring and cable routing as part of the team's integration work.

### Software setup

The Raspberry Pi hosts the printer software and web interface. The Octopus controller runs the microcontroller firmware used by Klipper. Build-specific settings are supplied through `printer.cfg`.

The original report points to the official Voron configuration as the starting point. A final tested configuration file is **not included in this repository version**.

## Evidence and current contents

This portfolio summary was prepared from the project's final graduation report and its week-two presentation.

| File | Purpose |
|---|---|
| `README.md` | Project overview, team roles and scope |
| [docs/build-summary.md](docs/build-summary.md) | Summary of the documented build and software workflow |
| [docs/evidence-status.md](docs/evidence-status.md) | Available evidence, documentation gaps and useful future additions |

The original report, presentation, build photographs, CAD files, firmware binaries and configuration files are not bundled in this version. The project documents describe assembly and software setup, but do not establish measured print accuracy, maximum working speed or long-term reliability. No such performance claims are made here.

## Skills demonstrated

- Raspberry Pi operating-system installation and network setup.
- Firmware deployment and configuration using an existing embedded platform.
- Integration of a host computer with a motion-control board.
- Understanding the relationship between mechanical assembly, electrical wiring and software configuration.
- Teamwork and technical documentation during a hardware build.

## Reproducing the build

Use the official manuals for the exact printer revision and installed electronics. This repository is a historical project record, not a complete wiring or commissioning guide. Configuration must match the actual controller, sensors, motors and printer dimensions. Mains wiring and heater setup require appropriate electrical checks before operation.

## Credits and references

- **Voron Design:** [Voron 2 source repository](https://github.com/VoronDesign/Voron-2) and [official documentation](https://docs.vorondesign.com/).
- **Voron software setup:** [Configuration guide](https://docs.vorondesign.com/build/software/configuration.html).
- **Klipper:** [Official project](https://www.klipper3d.org/).
- **Mainsail:** [Official documentation](https://docs.mainsail.xyz/).
- **BIGTREETECH:** Octopus V1.1 controller platform.
- **Academic supervision:** Dr. Jaber Yamani, College of Telecom & Electronics.

Original project records: *VORON 2.4 R2 3D PRINTER*, graduation report, 2022; and *Voron 2.4_WK2*, project presentation.

## Attribution and licensing

The upstream Voron 2 repository is distributed under GPL-3.0. Refer to each upstream project for its own licence and notices. No upstream CAD, firmware or manual files are redistributed in this package. No blanket licence is assigned here to the team's original report, presentation or third-party material.

