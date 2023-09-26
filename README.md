# [🇺🇸] My Hackintosh EFI!

<img src="https://moe-counter.glitch.me/get/@hackintoshefiinalol?theme=rule34"><hr>

[Procurando a versão em português?](https://github.com/ina-lol/B560M-Elite-Hackintosh-EFI/blob/main/READMEPTBR.md)<br><br>
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com) ![](https://camo.githubusercontent.com/67eb7c8b1ed6c9019f25d5ac1331577db2b42f15303a452aa91e94fc4565019a/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76312e7376673f6c6162656c3d436f6e747269627574696f6e73266d6573736167653d57656c636f6d6526636f6c6f723d303035396233267374796c653d666c61742d737175617265)

![About](https://raw.githubusercontent.com/ina-lol/B560M-Elite-Hackintosh-EFI/main/Assets/Screenshot%202023-06-23%20at%2014.04.21.png)

**Opencore version**: 0.9.3<br>
**Latest macOS working**: 13.4.1 (22F82)

## Specs:

**Processor**: i7-10700f<br>
**Motherboard**: Gigabyte B560M Aorus Elite (Unsure of BIOS version)<br>
**Graphic card**: Sapphire AMD RX550 Lexa 4 GB<br>
**Ram**: XPG Spectrix D41 TUF Gaming Limited Edition RGB 3200MHz 16GB (2x8)<br>

## What is working:

GPU Acceleration ([See RX550 LEXA patch](https://github.com/ina-lol/B560M-Elite-Hackintosh-EFI#rx-550-lexa-patch))<br>
Audio<br>
All USB Ports<br>
iCloud<br>

## What dosen't work:

H264 & HEVC Codecs<br>

## Benchmarks:

CPU: [Click here](https://browser.geekbench.com/v5/cpu/19326059)

## CPU & GPU name

The GPU name is modified by the efi, using a key on Device properties and the CPU name can be accurate to your CPU using CPUname [here](https://github.com/corpnewt/CPU-Name), this script uses the restrict events kext (already included on the EFI)

## RX 550 LEXA patch:

RX 550 has 2 models Lexa and Baffin, the lexa models are incompatible with macOS however we can get then to work with some patches
[See Gabriel Luchina's video](https://www.youtube.com/watch?v=mSnqjKFXbBg)<br>
Which RX 550 model do i have?<br> 
[See this issue](https://github.com/dortania/bugtracker/issues/129)

## Thanks:

[Apple for macOS](https://apple.com)<br>
[Gabriel Luchina for hackintosh guides and base efi](https://www.youtube.com/c/GabrielLuchina)<br>
[Opencore team for opencore](https://dortania.github.io/getting-started/)<br>

PS: Currently theres no way of contacting me because i won't read emails or dms for now
