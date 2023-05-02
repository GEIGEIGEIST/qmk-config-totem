<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/docs/images/TOTEM_logo_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="/docs/images/TOTEM_logo_bright.svg">
  <img alt="TOTEM logo font" src="/docs/images/TOTEM_logo_bright.svg">
</picture>

# QMK CONFIG FOR THE TOTEM SPLIT KEYBOARD

> **Note**
> The qmk firmware for the TOTEM should work, but I haven't tested it yet. So if problems occur please contact me.

[Here](https://github.com/GEIGEIGEIST/totem) you can find the hardware files and build guide.\
[Here](https://github.com/GEIGEIGEIST/zmk-config-totem) you can find the ZMK config for the TOTEM.

TOTEM is a 38 key column-staggered split keyboard running [QMK](https://docs.qmk.fm/) or [ZMK](https://zmk.dev/). It's meant to be used with a SEEED XIAO RP2040 or BLE.


![TOTEM layout](/docs/images/TOTEM_layout.svg)



## HOW TO USE

Place the totem folder from this repository in the keyboards folder of your qmk installation.\
Then use this command in QMK MSYS to create the firmware.

`qmk compile -kb totem -km default`

If you use just a random keymap to test you can use the `totem_default.uf2` which you can find in the root of the repository.

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) for more information. If you never used QMK, you can start with the [Newbs Guide](https://docs.qmk.fm/#/newbs).
