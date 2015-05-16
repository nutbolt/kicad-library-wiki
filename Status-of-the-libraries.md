This table shows the current status of the various libraries in relation to the rules contained in [[KiCad Library Convention]] (KLC).

A user who wants to make any of the libraries compliant (complex edit) should subscribe to the table and let other users know his editing intentions in order to avoid duplication of work.

| Library name               | KLC Compliant | Action / Information    | By person          |
|----------------------------|---------------|-------------------------|--------------------|
| `74xgxx.lib`               |               |                         |                    |
| `74xx.lib`                 |               |                         |                    |
| `ac-dc.lib`                | Yes           |                         |                    |
| `actel.lib`                | Yes           |                         |                    |
| `adc-dac.lib`              | Yes           |                         |                    |
| `Altera.lib`               |               |                         |                    |
| `analog_devices.lib`       | Yes           |                         |                    |
| `analog_switches.lib`      |               |                         |                    |
| `atmel.lib`                | No            | Bottom pad should be included. https://github.com/KiCad/kicad-library/issues/13 |                    |
| `audio.lib`                |               |                         |                    |
| `brooktre.lib`             |               |                         |                    |
| `cmos4000.lib`             |               |                         |                    |
| `cmos_ieee.lib`            |               |                         |                    |
| `conn.lib`                 |               |                         |                    |
| `contrib.lib`              | Yes           |                         |                    |
| `cypress.lib`              | Yes           |                         |                    |
| `dc-dc.lib`                | Partial       | Need improvements       |                    |
| `device.lib`               |               |                         |                    |
| `digital-audio.lib`        | Yes           |                         |                    |
| `display.lib`              |               |                         |                    |
| `dsp.lib`                  | Yes           |                         |                    |
| `elec-unifil.lib`          | N/A           | ---                     | ---                |
| `ESD_Protection.lib`       |               |                         |                    |
| `ftdi.lib`                 | Yes           |                         |                    |
| `gennum.lib`               |               |                         |                    |
| `graphic.lib`              | N/A           | ---                     | ---                |
| `hc11.lib`                 | Yes           |                         |                    |
| `intel.lib`                | Yes           |                         |                    |
| `interface.lib`            | Partial       | Need improvements       |                    |
| `ir.lib`                   | Yes           |                         |                    |
| `Lattice.lib`              | Yes           |                         |                    |
| `linear.lib`               |               |                         |                    |
| `logo.lib`                 | N/A           | ---                     | ---                |
| `maxim.lib`                | Partial       | Need improvements       |                    |
| `memory.lib`               |               |                         |                    |
| `microchip.lib`            | Yes           |                         |                    |
| `microchip_dspic33dsc.lib` | Yes           |                         |                    |
| `microchip_pic10mcu.lib`   | Yes           |                         |                    |
| `microchip_pic12mcu.lib`   | Yes           |                         |                    |
| `microchip_pic16mcu.lib`   | Yes           |                         |                    |
| `microchip_pic18mcu.lib`   | Yes           |                         |                    |
| `microchip_pic32mcu.lib`   | Yes           |                         |                    |
| `microcontrollers.lib`     | Yes           |                         |                    |
| `motorola.lib`             |               |                         |                    |
| `motor_drivers.lib`        | Yes           |                         |                    |
| `msp430.lib`               |               |                         |                    |
| `nordicsemi.lib`           | Yes           |                         |                    |
| `nxp_armmcu.lib`           |               |                         |                    |
| `onsemi.lib`               | Yes           |                         |                    |
| `opto.lib`                 | Partial       | Need improvements       |                    |
| `Oscillators.lib`          |               |                         |                    |
| `philips.lib`              | Yes           |                         |                    |
| `power.lib`                | Yes           |                         |                    |
| `powerint.lib`             | Yes           |                         |                    |
| `Power_Management.lib`     |               |                         |                    |
| `pspice.lib`               |               |                         |                    |
| `references.lib`           |               |                         |                    |
| `regul.lib`                |               |                         |                    |
| `relays.lib`               | Yes           |                         |                    |
| `rfcom.lib`                | Partial       | Need improvements       |                    |
| `sensors.lib`              | Partial       | Need improvements       |                    |
| `silabs.lib`               | Yes           |                         |                    |
| `siliconi.lib`             |               |                         |                    |
| `stm32.lib`                | Pending       | **In Progress** (PR #127) | Mateusz Krawczuk   |
| `stm8.lib`                 | Yes           |                         |                    |
| `supertex.lib`             | Yes           |                         |                    |
| `switches.lib`             | Partial       | Need improvements       |                    |
| `texas.lib`                | Partial       | Need improvements       |                    |
| `transf.lib`               | Yes           |                         |                    |
| `transistors.lib`          | Partial       | Need improvements       |                    |
| `ttl_ieee.lib`             |               |                         |                    |
| `valves.lib`               | Partial       | Need improvements       |                    |
| `video.lib`                | Partial       | Need improvements       |                    |
| `Xicor.lib`                | Yes           |                         |                    |
| `xilinx.lib`               |               |                         |                    |
| `Zilog.lib`                | Yes           |                         |                    |

Overall status: only **45%** of library set meet the KLC rules.