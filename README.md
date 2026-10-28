# Voron 2.4 R2 — Graduation Project Build

A team build of a **Voron 2.4 R2 CoreXY 3D printer**, completed as a graduation project at the **College of Telecom & Electronics, Jeddah, in 2022**.

**Original design:** [VoronDesign/Voron-2](https://github.com/VoronDesign/Voron-2) · **Upstream licence:** [GNU GPL v3.0](https://github.com/VoronDesign/Voron-2/blob/Voron2.4/LICENSE) · **Repository licence:** [LICENSE](LICENSE)

All credit for the original printer design belongs to **Voron Design and its contributors**. This is an independent student build record, not an official Voron release.

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

## Project photos

Add your photos to the `images/` folder using the filenames below. Replace each placeholder with its image by removing `<!--` and `-->` around the Markdown image line.

### Completed printer

> **Photo placeholder:** Add a clear photo of the assembled printer.

<!-- ![Completed Voron 2.4 R2 printer](images/completed-printer.jpg) -->

### Mechanical assembly

> **Photo placeholder:** Add a photo of the frame, gantry or belt assembly during the build.

<!-- ![Frame and gantry assembly](images/mechanical-assembly.jpg) -->

### Electronics and wiring

> **Photo placeholder:** Add a photo showing the Octopus controller, Raspberry Pi and cable routing.

<!-- ![Electronics and wiring](images/electronics-wiring.jpg) -->

### Software setup

> **Photo placeholder:** Add a screenshot of your Mainsail interface or printer configuration. Remove private network details before uploading.

<!-- ![Mainsail software setup](images/mainsail-setup.png) -->

### Sample print

> **Photo placeholder:** Add a photo of a part produced by this printer, if available, with a short caption describing the material and settings.

<!-- ![Sample printed part](images/sample-print.jpg) -->

## My contribution

My assigned role in the final report was **software installation**. The software workflow documented in the report covers:

- Preparing the Raspberry Pi SD card using Raspberry Pi Imager.
- Installing MainsailOS and accessing the Mainsail web interface.
- Preparing Klipper firmware for the Octopus controller and transferring the firmware using an SD card.
- Creating `printer.cfg` from the official Voron configuration and identifying build-specific settings to change.
- Connecting the Raspberry Pi to the network over Ethernet for setup and access.

These activities used existing software and official configuration templates. This project does not claim original development of Voron, Klipper or Mainsail.

## Team contributions

Roles below follow the division of work recorded in the graduation report.

| Team member | Assigned responsibility |
|---|---|
| Khaled Bediwi | Team leader and hardware installation |
| Hassan | Software installation |
| Osama Althubyani | Coding |
| Basel Aljohani | Electrical connections |
| Hussam Almuntshri | Research, component sourcing and administrative tasks |

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
| [images/README.md](images/README.md) | Instructions for adding build photos |

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

The documentation created for this repository is released under the **GNU General Public License v3.0**; see [LICENSE](LICENSE) for the full text.

The original printer design is maintained at [VoronDesign/Voron-2](https://github.com/VoronDesign/Voron-2), whose [upstream licence](https://github.com/VoronDesign/Voron-2/blob/Voron2.4/LICENSE) is GPL-3.0. The included licence text was retrieved from that repository. Credit and applicable notices must be retained when reusing upstream material.

This package does not redistribute upstream CAD, firmware or manuals. Klipper, Mainsail and other third-party projects retain their own licences. The original team report, presentation and any third-party photographs are not included or relicensed by this documentation licence.

