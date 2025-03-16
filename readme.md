# FX19 Firmware

This repository contains the firmware for the FX19 number pad.
**Huge apologies for not including this earlier, as I made this months ago and didn't remember.**

## Contents

- **Source Code**: 
    - `src/keymaps/via`: Source code with VIA support.
    - `src/keymaps/default`: Source code without VIA support.

- **Precompiled Binaries**:
    - `falsonix_fx19_via.hex`: Precompiled binary **with** VIA support.
    - `falsonix_fx19_default.hex`: Precompiled binary **without** VIA support.
    - Both of these binaries can be flashed to the board via QMK Toolbox or another similar tool.

- **VIA Layout file**
    - `via.json`: VIA layout file for use with the VIA configurator at [https://usevia.app/](https://usevia.app/)