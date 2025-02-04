# Adding a robot to the list

Robots in this list should be open source **both** in hardware and software. If they don't qualify on one of the two criteria, we mark it out as a ❌.

### 🛠️ Open-source hardware

Instructions and build files, such as 3D printing models, should be published under an [open-source hardware](https://en.wikipedia.org/wiki/Open-source_hardware) license. For instance:

- [TAPR Open Hardware License](https://en.wikipedia.org/wiki/TAPR_Open_Hardware_License)
- [CERN Open Hardware Licence](https://en.wikipedia.org/wiki/CERN_Open_Hardware_Licence)
- Some Creative Commons licenses are OK, but not those with an NC clause at it goes against the [open-source definition](https://opensource.org/osd)

Ideally, build tools can all be bought online. For example, 3D printing in ABS or PETG works, but in tungsten carbide is not OK for all. Similarly, relying on a low-cost MEMS IMU works for most, but not a space-grade IMU.

### 💻 Open-source software

All the software necessary to make the robot move should be available under a permissive or copyleft software license.

## Submitting a PR

Chime in with a [pull request](https://github.com/stephane-caron/awesome-open-source-robots/compare) if a robot checks all points above. The addition should be a single line with the following columns:

- Project: project name, linked to the project page if there is one
- Maker: name of the maker for a single person's work, as soon as it is a group, make sure the label is general enough to include all contributors
- Hardware: link to hardware ressources (CAD files, 3D printing website, ...)
- HW License: SPDX identifier for the hardware license (see above for checking that the license is open source)
- Software: link to the robot's motion control software
- SW License: SPDX identifier for the software license
