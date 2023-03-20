# Millicast native SDK

## Supported OSes.

| Windows | MacOs | Linux | iOS | Android | AppleTV |
| --- | --- | --- | --- | --- | --- |
| [x] Win10 | [x] MacOS Catalyna | [x] Ubuntu 20 | [x] iOS >= 14.5| [x] Android >= API 24 | [x] tvOS >= 14.5 |
|           | [x] MacOS BigSur | [x] Ubuntu 22 | | | |
|           | [x] MacOS Monterey | | | | |

## Audio Codecs and Quality - Encoding

- [x] G.711
- [ ] AAC
  - [ ] Number of channels
  - [ ] Sampling
  - [ ] LC / HE / HEv2
- [ ] Dolby AC3
- [x] Opus stereo
- [x] Opus 5.1 & 7.1



## Video Codecs and Quality - Encoding

| Codec | Profile | Bit | Chroma | Color Space | SVC | Intel HW | AMD HW | NV HW |
| ---   | :---:   | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
| [x] h.264 | Main |  8 | 4:2:0 | BT.601 | [/] Simulcast | [ ] | [ ] | [ ] |
| [/] h.264 | High |  8 | 4:2:0 | BT.601 | [ ] Simulcast | [ ] | [ ] | [ ] |
| [x] VP8   |      |  8 | 4:2:0 | BT.601 | [/] Simulcast | [ ] | [ ] | [ ] |
| [x] VP9   | 0    |  8 | 4:2:0 | ?      | [x]           | [ ] | [ ] | [ ] |
| [ ] VP9   | 1    |  8 | 4:2:2 | ?      | [ ]           | [ ] | [ ] | [ ] |
| [ ] VP9   | 1    |  8 | 4:4:4 | ?      | [ ]           | [ ] | [ ] | [ ] |
| [ ] VP9   | 2    | 10 | 4:2:0 | HDR10  | [/]           | [ ] | [ ] | [ ] |
| [ ] VP9   | 2    | 12 | 4:2:0 | ?      | [ ]           | [ ] | [ ] | [ ] |
| [ ] VP9   | 3    | 10 | 4:2:2 | ?      | [ ]           | [ ] | [ ] | [ ] |
| [ ] VP9   | 3    | 12 | 4:4:4 | ?      | [ ]           | [ ] | [ ] | [ ] |
| [/] HEVC  | ?    |  8 | 4:2:0 | ?      | [ ] Simulcast | [ ] | [ ] | [ ] |
| [x] AV1   | Main |  8 | 4:2:0 | ?      | [X] | [ ] | [ ] | [ ] |
| [ ] AV1   | Main | 10 | 4:2:0 | ?      | [ ] | [ ] | [ ] | [ ] |
| [ ] AV1   | High |  8 | 4:2:0 | ?      | [ ] | [ ] | [ ] | [ ] |
| [ ] AV1   | High | 10 | 4:2:0 | ?      | [ ] | [ ] | [ ] | [ ] |
| [ ] AV1   | High |  8 | 4:4:4 | ?      | [ ] | [ ] | [ ] | [ ] |
| [ ] AV1   | High | 10 | 4:4:4 | ?      | [ ] | [ ] | [ ] | [ ] |
| [ ] AV1   | Pro  | 8~12 | All | ?      | [ ] | [ ] | [ ] | [ ] |
