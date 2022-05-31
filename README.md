# Ender 3 Stealthburner Edition
 Voron Aesthetic/Hardware Mod for Original Ender3 V1.

 This is an upgrade in Hardware, Electronics, Software and aesthetic for the Ender 3. It represents a massive increase in capability for your old Ender that will allow it to keep up with much more advanced (and expensive) 3D Printers.
 This mod is designed to be extremely cheap, utilising as much of the old system as possible.

 The main upgrades of this mod are;

 1: A switch from a Bowden fed PTFE Lined hotend system, to a direct drive all metal hotend using the Voron Stealthburner (Files not included, instead find them here; https://vorondesign.com/voron_stealthburner)

 2: The rewiring of the Power system to facilitate cleaner connections and easier integration with the raspberry Pi.

 3: The replacement of Marlin firmware with Klipper for both a performance and technical ability improvement.

 4: Replacement of the print bed surface with steel spring sheet for better adhesion and addition of very cheap auto levelling probe.

 Information;
 - This printer uses a Voron Stealthburner featuring an all metal E3D V6 hotend (with a 40W Heater cartridge) for printing up to 300C.
 - The bed is a Steel Spring textured PEI surface which can be used with most plastics with no need for any adhesive or layer agent.
 - The Klipper host used is a Raspberry Pi. This machine is running a Raspberry Pi 2, although can use a RPI 3, 4 or Zero 2.
 - The MCU is an upgraded Creality 4.2.7 32 bit mainboard, although in theory this should work with an original Creality 1.x.x board.
 - The power supply has been replaced (my original failed), but it is still running its original 24V 350W PSU (Non Meanwell).
 - The touch probe being used is based on Klicky, called the KlackEnder. Link to the files can be found here (Note, all KlackEnder Parts should be printed in ABS to ensure heat tolerance at higher temperatures); https://github.com/kevinakasam/KlackEnder-Probe
 - Environment temperature sensor used is a BMP280, which connects to the RPI and integrates with Klipper over I2C Bus.
 - Relay is used to control electronics cooling fans, with additional relay channels being added for extra features in time.

This documentation is a Work In Progress and will be updated over time, however the 3D Printer is fully functional and works correctly at this point.

CAD Model status: Incomplete - use at your own risk
Printer Status: Beta.

Credit for 3rd Party files used;

- Stealthburner (Missing from CAD Model) - Voron Design
- KlackEnder (Missing from CAD Model) - kevinakasam
- Creality MCU Board mount (Not used in CAD model but required - CAD Model Board mount deprecated) - DemoSTH (https://www.teamfdm.com/files/file/170-ender-3pro-switchwire/)

