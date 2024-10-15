# Project Overview

## Tyrian vs. Cobalt 110G Comparison

| Feature                   | Tyrian                                     | Cobalt 110G                           |
|---------------------------|--------------------------------------------|---------------------------------------|
| Altitude readings          | AGL (Above Ground Level)                   | MSL (Mean Sea Level)                  |
| Speed                      | M/S (Meters per second)                    | Knots                                 |
| Gauge cluster              | None                                       | Custom gauge cluster in Actions tab   |
| Elevation profile          | None in the mission plan                   | Available in the mission plan         |

## Goal
Redesign the Mission Planner for Tyrian to visually replicate the custom layout of the Cobalt 110G.

## Todo
1. [ ] In the Actions tab:
    - [x] Altitude tape: Change the Primary Flight Display to read in MSL instead of AGL.
    - [ ] Fly to Here: Update input from AGL to MSL.
    - [ ] Change Altitude: Modify the input on the Actions tab from AGL to MSL.
    - [x] Change Speed: Adjust the speed input on the Actions tab from M/S to Knots.
    - [ ] Custom gauge cluster: Replicate the custom gauge cluster of the Cobalt 110G.
2. [ ] In Mission Planning:
    - [ ] Change "Absolute" to MSL.
    - [ ] In the frame option, change "Relative" to AGL.
    - [ ] Set MSL as the default (no need to hide the default frame option).
    - [ ] Elevation Profile: Integrate the elevation profile feature from older mission planners.
3. [ ] Custom gauge colors:
    - [ ] Allow custom gauges to change colors based on received readings.
4. [ ] Additional tasks:
    - [ ] Remove unnecessary features to declutter the interface.
    - [ ] Fix layout issues (e.g., change speed, change altitude, set loiter radius).
