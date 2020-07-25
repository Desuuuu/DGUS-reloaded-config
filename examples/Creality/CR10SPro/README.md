Here are some of the modifications made to this configuration:

* 300x310x350 build volume (Z reduced from 400 to prevent the bowden tube from flexing against the top bar)
* Proper steps/unit configuration
* Adjusted default feedrate and acceleration
* PID for the hotend and bed
* Leveling probe with proper offset and 2 probes for each point
* Bilinear leveling with a 5x5 mesh (segments length increased to 20mm)
* Leveling restored after G28
* Z safe homing
* Nozzle park
* Advanced pause with park on pause and filament unload G-codes
* Filament runout sensor without automatic filament unloading
* EEPROM settings storage
* Print statistics
* SD card support
* Power loss recovery
* Babystepping (with Z offset adjustment)
* Classic jerk
* S-Curve acceleration
* Disabled arc support

The following is also enabled to help with OctoPrint setups:

* Higher baudrate (250,000)
* Host action commands with host prompt support
* Emergency parser
* Advanced OK
