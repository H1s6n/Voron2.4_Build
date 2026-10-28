# Documented build workflow

This summary describes the historical graduation project. It is not a verified procedure for commissioning another printer.

## Mechanical phase

The report progresses through frame assembly, Z drives and idlers, A/B drives, gantry installation, Z belts, A/B belts, toolhead assembly and cable-chain installation. It directs the reader to the official Voron manual for detailed assembly instructions.

## Electrical phase

The team documented the power inlet, power distribution, bed connections, Raspberry Pi, Octopus controller, motor connections, toolhead wiring, fans and cable routing.

Power-supply labels and ratings should be checked against the actual installed components before being used in a reproduction. The historical report is not a verified electrical schematic.

## Software phase

1. Prepare an SD card using Raspberry Pi Imager.
2. Install MainsailOS on the Raspberry Pi.
3. Access the Mainsail interface over the local network.
4. Prepare Klipper firmware for the installed controller.
5. Transfer the firmware to the Octopus using an SD card.
6. Create `printer.cfg` from the official Voron template.
7. Adapt controller identification, printer size and sensor settings to the build.

The report describes Ethernet access. It does not provide a verified software-version inventory or a final machine-specific configuration in the material extracted for this package.

## Testing status

The project schedule includes testing and troubleshooting. The conclusion also calls for further setup and calibration. Neither statement alone verifies particular test outcomes. Quantitative results and sample-print evidence should be added only when supported by the team's records.

