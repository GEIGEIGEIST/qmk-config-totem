<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/docs/images/TOTEM_logo_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="/docs/images/TOTEM_logo_bright.svg">
  <img alt="TOTEM logo font" src="/docs/images/TOTEM_logo_bright.svg">
</picture>

# QMK CONFIG FOR THE TOTEM SPLIT KEYBOARD

[Here](https://github.com/GEIGEIGEIST/totem) you can find the hardware files and build guide.\
[Here](https://github.com/GEIGEIGEIST/zmk-config-totem) you can find the ZMK config for the TOTEM.

TOTEM is 38 keys column-staggered split keyboard running [QMK](https://docs.qmk.fm/) or [ZMK](https://zmk.dev/). It's meant to be used with a SEEED XIAO RP2040 or BLE.


![TOTEM layout](/docs/images/TOTEM_layout.svg)



## HOW TO USE

Place the totem folder from this repository in the keyboards folder of your qmk installation.\
Than use this command in QMK MSYS to create the firmware

`qmk compile -kb totem -km default`