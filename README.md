# Firmware for ESP32-WROVER, Muse Luxe, and Muse Proto

---

## Muse Luxe

Basic YAML firmware with simple functionality:

- Volume buttons control the volume.. 🤦
- Play button starts and stops playback.
- Double-clicking skips to the next song.
- Triple-clicking goes to the previous song.
- LED is green while playing and red while in standby.

[Flash Muse Luxe Firmware](https://realdeco.github.io/muse_wrover/Muse_Luxe/)

## Muse Proto

- GPIO0 (boot) button starts and stops playback.
- Double-clicking skips to the next song.
- Triple-clicking goes to the previous song.
- LED is green while playing and red while in standby.

[Flash Muse Proto Firmware](https://realdeco.github.io/muse_wrover/Muse_Proto/)

## WRover Dev Module

connected to a MAX98357 speaker amplifier like this:

| MAX98357A Pin | ESP32 Pin |
|--------------|-----------|
| LRC          | GPIO25    |
| BCLK         | GPIO33    |
| DIN          | GPIO32    |

- GPIO0 (boot) button starts and stops playback.
- Double-clicking skips to the next song.
- Triple-clicking goes to the previous song.
- LED is blinking blue while playing and OFF while in standby.

---
