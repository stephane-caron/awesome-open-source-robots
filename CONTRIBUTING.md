# Adding a robot to the list

Robots in this list should be open source **both** in hardware and software. If they don't qualify on one of the two criteria, we mark it out as a ❌.

### 🛠️ Open-source hardware

Instructions and build files, such as 3D printing models, should be published under an [open-source hardware](https://en.wikipedia.org/wiki/Open-source_hardware) license. For instance:

- [TAPR Open Hardware License](https://en.wikipedia.org/wiki/TAPR_Open_Hardware_License)
- [CERN Open Hardware Licence](https://en.wikipedia.org/wiki/CERN_Open_Hardware_Licence)
- Some Creative Commons licenses are OK, but not those with an NC clause at it goes against the [open-source definition](https://opensource.org/osd)

Ideally, build tools can all be bought online. For example, 3D printing in ABS or PETG works, but in tungsten carbide is not OK for all. Similarly, relying on a low-cost MEMS IMU works for most, but not a space-grade IMU.

### 🦾 Open-source software

All the software necessary to make the robot move should be available under a permissive or copyleft software license.

## Submitting a PR

Chime in with a [pull request](https://github.com/stephane-caron/awesome-open-source-robots/compare) if you check all these points:

- Hardware build and motion control software are open (see above)
- Use SPDX identifiers for hardware and software licenses
- Link to a project page in the first column, if there is one
- Link to build instructions in the Hardware column, if possible
- Link to the motion control Software in the corresponding column
