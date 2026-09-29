# CYW43439 Wi-Fi radio images, firmware 7.95.49

The radio on the Raspberry Pi Pico W and Pico 2 W and on the Pimoroni Pico Plus 2 W.

**Source:** [georgerobotics/cyw43-driver](https://github.com/georgerobotics/cyw43-driver), the driver that Raspberry
Pi's Pico SDK uses.

| File | Bytes | SHA-256 | From |
|---|---|---|---|
| `wifi-fw.bin` | 224,190 | `dda7d2527e1cc9b1ebdd107d46932643617f6e83040f24cba722cbb0ded8c4a8` | the firmware part of the array in `firmware/w43439A0_7_95_49_00_combined.h`, commit `a1dc8859d09b8f547a4f4345fd0efb7300105e62` |
| `wifi-clm.blob` | 984 | `e712b3d218e8b1e2747b092e03b8b0afcb8c8c8e355d2a4a0d47b493800f3f89` | the regulatory (CLM) part of the same array, same commit |
| `wifi-settings.img` | 741 | `0517e0a609291e10c264d7d470acf3d823c23a9e7f7d5b12816a6d45b5cf1f71` | the settings in `firmware/wifi_nvram_43439.h`, commit `67b125457843a8eb4d3c374e9c48b7538e1e334d`, one NUL-terminated `key=value` string per setting and one more NUL at the end |
| `LICENSE.RP` | 1,789 | `67aca4f10d9edf489871f64cd8f0dcd6c5df3e4ce75bd39e1914fc54f99e40b3` | `LICENSE.RP`, commit `a1dc8859d09b8f547a4f4345fd0efb7300105e62` |
