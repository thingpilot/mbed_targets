## Thingpilot Mbed Targets - How To
Using the custom targets that we've defined in [custom_targets.json](https://github.com/thingpilot/mbed_targets/blob/master/custom_targets.json) is easy. Simply clone the version of the repository that you require (this is likely the latest tagged version or master) and place `custom_targets.json` in the top level of your Mbed program. See below for an example:

 1. `git clone https://github.com/thingpilot/mbed_targets`
 2. `cd mbed_targets`
 3. `git checkout master`
 4. `git pull` 
 5. Copy `custom_targets.json` into the directory of your Mbed program that contains `main.cpp`

## Thingpilot Mbed Targets Release Notes
**v0.2.1**  *15/11/2019*

- Add how-to to readme

**v0.2.0**  *15/11/2019*

- Add Buffer maximum reading times (user defined)
- Add max retries for clock synchronisation
- STM32L0xx UUID register

**v0.1.0**  *15/11/2019*

- Add Thingpilot Wright v1.0.0 (TP_WRIGHT_V1_0_0)
- Add Thingpilot Earhart v1.0.0 (TP_EARHART_V1_0_0)
- Add Thingpilot Development Board v1.1.0 (TP_DEV_BOARD_V1_1_0)