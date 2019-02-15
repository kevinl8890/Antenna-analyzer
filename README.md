# Antenna analyzer "SWR-mouse"
EasyEDA project for simple and quick assembly of the "SWR-mouse" antenna analyzer adapted for installation in the G403 case (Gainta Industries). The project includes the "SWR-mouse" antenna analyzer schematic and the PCB file. Version for mounting SMD components. Based on the submitted files, you can independently manufacture a PCB or order its manufacturing at the factory. In turn, I developed PCB for the independently manufacturing based on the existing circuit.

## What is SWR?
[Standing wave ratio (SWR)](https://en.wikipedia.org/wiki/Standing_wave_ratio) is used as a measure of impedance matching of a load to the characteristic impedance of a transmission line carrying RF signals. This especially applies to transmission lines connecting radio transmitters and receivers with their antennas. Impedance matching is achieved when the source impedance is the complex conjugate of the load impedance. When there is a mismatch between the load impedance and the transmission line, part of the forward wave sent toward the load is reflected back along the transmission line towards the source. The source then sees a different impedance than it expects which can lead to lesser power being supplied by it, the result is very sensitive to the electrical length of the transmission line.

Such a mismatch results in standing waves along the transmission line which magnifies transmission line losses. The SWR is a measure of the depth of those standing waves and is, therefore, a measure of the matching of the load to the transmission line. A matched load would result in an SWR of 1:1 implying no reflected wave. An infinite SWR represents complete reflection by a load unable to absorb electrical power, with all the incident power reflected back towards the source.

SWR is usually measured using a dedicated instrument called an SWR meter.

## Current development progress:
[![Progress](https://img.shields.io/badge/Antenna%20analyzer%20%28SMD%29-not%20tested-yellow.svg)](https://easyeda.com/IgrikXD/Antenna-analyzer-SMD) [![Progress](https://img.shields.io/badge/version-1.2.0-blue.svg)](./EasyEDA)  

## Current available implementations at EasyEDA platform:
- [Antenna analyzer (SMD)] ([Components list](./Components%20list.md), [Assembly guide](./Assembly%20guide.md))

## How to use this repository?
In [Datasheets](./Datasheets) and [Schematics](./Schematics) directories, you can find all necessary technical documentation for the used components and schematic files in PDF format. If you only need GERBER files, you can find them in the appropriate [Gerbers](./Gerbers) directory. In the [EasyEDA](./EasyEDA) directory, you can find a list of files for implementing the ready device (files can be imported into EasyEDA editor). After that, based on submitted files, you can make the device independently or order printed circuit boards for factory manufacturing.

## What was used in the development?
| Source | Description |
| ------ | ------ |
| [UR5FFR • View topic - Антенный анализатор Si5351 SWR-mouse] | The original solution of the antenna analyzer "SWR-mouse" from the radio amateur UR5FFR. Article on the forum in Russian. |
| [Антенный Анализатор UR5FFR на ARDUINO и Si5351] | Video on YouTube from radio amateur R2AJI. It describes the process of manufacturing the "SWR-mouse" antenna analyzer circuit board for the G436/G407 case. In this version, there is an implementation of power supplying from a 18650 battery, a SO-239 connector, a Mini-USB power/data connector. |
| [Standing wave ratio - Wikipedia] | An article on Wikipedia describing what SWR is. |

## How to contact me?
- E-mail: igor.nikolaevich.96@gmail.com
- Telegram: https://t.me/igrikxd
- LinkedIn: https://www.linkedin.com/in/igor-yatsevich/

[Antenna analyzer (SMD)]: <https://easyeda.com/IgrikXD/Antenna-analyzer-SMD>
[UR5FFR • View topic - Антенный анализатор Si5351 SWR-mouse]: <http://dspview.com/viewtopic.php?f=14&t=189>
[Антенный Анализатор UR5FFR на ARDUINO и Si5351]: <https://www.youtube.com/watch?v=hkxOoky4vWA&t>
[Standing wave ratio - Wikipedia]: <>
