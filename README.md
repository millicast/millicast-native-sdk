# Millicast Studio

 - [X] Full App
 - [X] CLI
 - [ ] Remote Control through web Interface

## Features

| Inputs / Capture | Mixing | Millicast |
| ---              | ---    | ---       |
| <ul><li>[x] Encoder Mode (Single Stream Input)</li></ul>   | <ul><li>[ ] Video Compose</li></ul>        | <ul><li>[x] Rest API </li></ul>             | 
| <ul><li>[ ] Studio Mode (multiple inputs & mixer)</li></ul>| <ul><li>[ ] Audio Mixing</li></ul>         | <ul><li>[x] Websocket connection </li></ul> |
| <ul><li>[x] Devices</li></ul>                              | <ul><li>[ ] Audio Tracks mapping</li></ul> | <ul><li>[x] Subscription token </li></ul>   |
| <ul><li>[x] Screens / Monitors</li></ul>                   |                                            | <ul><li>[x] support/display outbound stats</li></ul>|
| <ul><li>[x] NDI</li></ul>                                  |                                            | <ul><li>[ ] report outbound stats</li></ul> |
| <ul><li>[x] SDI & HDMI - BlackMagic Decklink</li></ul>     |                                            | <ul><li>[ ] Cash capture and reporting</li></ul>|
| <ul><li>[ ] File Reader</li></ul>                          |                                            | <ul><li>[ ] End To End Encryption</li></ul> |
| <ul><li>[ ] Paced File Reader</li></ul>                    |                                            |                                             |

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

## Millicast Studio Loopback & Player 

Demo : https://www.youtube.com/watch?v=yTCERenocAY

- [ ] Audio Quality
- [ ] Video Frame Quality
  - [ ] PNSR
  - [ ] SSIM
  - [ ] WMAF
  - [ ] NARVAL
- [ ] Stats
  - [x] Support / Display Inbound stats
  - [ ] Report Inbound Stats

## Supported OSes

| Windows | MacOs | Linux | iOS | Android |
| --- | --- | --- | --- | --- |
| [x] Win10 | [x] MacOS 10.14 intel | [x] Linux 18 Deb Package | [X] iOS xxx on yyy | [ ] android xxx on yyy |
|           | [x] MacOS 10.15 intel | [x] Linux 18 AppImage    | | |
|           | [x ] MacOs 10.16 intel | [x] Linux 20 Deb Package | | |
|           |                       | [x] Linux 20 AppImage    | | |

# Millicast Player

## Features

- [ ] Forensic Watermarking
- [x] Outputs
  - [x] Attached Display
  - [x] NDI
  - [x] SDI + HDMI (Black Magic Decklink)


## Suported OSes.

| Windows | MacOs | Linux | iOS | Android | AppleTV |
| --- | --- | --- | --- | --- | --- |
| [x] Win10 | [x] MacOS Catalyna | [x] Ubuntu 20 | [x] iOS 14 | [x] android | [x] tvOS 14 |
|           | [x] MacOS BigSur | | | | |

# Thank you for reading so far

https://www.youtube.com/watch?v=MhpYPvtBSsQ
