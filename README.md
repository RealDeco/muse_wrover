# Sendspin Firmware for Muse Luxe, Muse Proto and ESP32-WROVER

Open-standard protocol for synchronized audio playback and media orchestration across multiple clients and smart home devices, functioning as an open alternative to proprietary ecosystems like AirPlay or Sonos.

<img width="1916" height="613" alt="15b462db-294b-4376-9991-0213d637deeb" src="https://github.com/user-attachments/assets/409514a5-06fa-468b-a918-39f7255ca898" />

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

[Flash WRover Dev Module Firmware](https://realdeco.github.io/muse_wrover/WRover/)


---
