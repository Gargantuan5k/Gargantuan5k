<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=2800&pause=700&color=7AA2F7&center=true&vCenter=true&width=700&lines=%3E+Hello%2C+world+%F0%9F%91%8B;%3E+I+write+RTL+that+survives+cosmic+rays+%E2%98%84%EF%B8%8F;%3E+Flight+computers+%E2%80%A2+FPGAs+%E2%80%A2+ASICs;%3E+Currently+arguing+with+the+timing+report;%3E+sudo+make+me+a+tapeout" alt="Typing SVG" />

</div>

```
                                                  .  *        .       .        *     .
                                           *   .        __|__   .  *        .         .
                                        .         --====|[O]|====--      ☄️<- not today, cosmic ray
                                           .   *        |___|      .     *        .
                                       .          *      / \   .       .     *         .
```

<div align="center">

![Profile views](https://komarev.com/ghpvc/?username=Gargantuan5k&color=7aa2f7&style=flat-square&label=times+ive+viewed+my+own+profile)
![SEUs survived](https://img.shields.io/badge/SEUs%20survived-all%20of%20them*-9ece6a?style=flat-square)
![Timing](https://img.shields.io/badge/timing-almost%20met-e0af68?style=flat-square)

<sub>*hopefully</sub>

</div>

---

<!-- <div align="center">
  <img src="./terminal.svg" alt="Terminal: whoami, ls research/, make tapeout PDK=sky130, uptime" width="100%" />
</div> -->

## Research

| | Thread | Status |
|---|---|---|
| 🛡️ | **[MAC Sentry](https://github.com/Gargantuan5k/mac-sentry)**: a radiation-hardened multiply-accumulate unit protected by BCH error correction (syndrome → Berlekamp–Massey → Chien search, all in GF(2^m)). Being integrated with a friend's NPU over Wishbone, headed for a **sky130 tapeout** | ![](https://img.shields.io/badge/-RTL%20→%20silicon-7aa2f7?style=flat-square) |
| 🧠 | **Runtime-reconfigurable LUT neural networks**: every neuron *is* a LUT (CFGLUT5), retrained on-chip to recover the accuracy a gas-sensor classifier loses to drift | ![](https://img.shields.io/badge/-paper%20in%20progress-e0af68?style=flat-square) |
| ⏱️ | **Autonomous timing closure**: an evolutionary agent that rewrites RTL until the timing report stops yelling, built on open-source EDA | ![](https://img.shields.io/badge/-evolving-9ece6a?style=flat-square) |
| 🔐 | **Hardware security**: S-box implementations and how much they leak | ![](https://img.shields.io/badge/-exploring-bb9af7?style=flat-square) |
| 🫀 | **TinyML for wearables**: blood-pressure estimation from PPG on tiny, low-power hardware | ![](https://img.shields.io/badge/-curious-bb9af7?style=flat-square) |

## Other things I've built 

| Project | What it is | tldr |
|---|---|---|
| **ViT on FPGA** | Vision Transformer segmentation pipeline in hardware | attention is all you need (and a lot of BRAM) |
| **CNN MAC accelerator** | RTL → IP packaging → ZedBoard bitstream | 🟢 the LED blinked |
| **ASIC reverse-engineering** | GDS → netlist on sky130, purely for fun | archaeology, but for transistors |
| **Radiation pulse discrimination** | Nuclear pulse counting and classification on STM32 | counts particles so you don't have to |
| **17-bit framed serial bus** | A custom protocol between satellite subsystems | because 16 bits was too mainstream |
| **Pacman on STM32H7** | Exactly what it sounds like, on a DWIN LCD | 👾 waka waka |

## Toolchain

<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,py,matlab,linux,bash,git,latex&theme=dark" />
</p>

![Verilog](https://img.shields.io/badge/Verilog-1f2335?style=for-the-badge&logoColor=7aa2f7)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1f2335?style=for-the-badge&logoColor=7aa2f7)
![Vivado](https://img.shields.io/badge/Vivado-1f2335?style=for-the-badge&logo=amd&logoColor=ff5370)
![STM32](https://img.shields.io/badge/STM32-1f2335?style=for-the-badge&logo=stmicroelectronics&logoColor=e0e0e0)
![Yosys](https://img.shields.io/badge/Yosys-1f2335?style=for-the-badge&logoColor=9ece6a)
![OpenROAD](https://img.shields.io/badge/OpenROAD-1f2335?style=for-the-badge&logoColor=9ece6a)
![sky130](https://img.shields.io/badge/sky130-1f2335?style=for-the-badge&logoColor=e0af68)

## Telemetry

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Gargantuan5k&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gargantuan5k&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Gargantuan5k&theme=tokyonight&hide_border=true" />
</div>

## Known issues

```diff
+ FIXED   Single-event upsets in the MAC datapath (BCH says hi)
+ FIXED   LED did not blink (it was the reset polarity. it is always the reset polarity.)
! OPEN    Will explain Galois fields to anyone who stands still long enough
! OPEN    Says "just one more synthesis run" at 2 AM
- WONTFIX Opens the 8259A datasheet for fun
```

<details>
<summary><b>Fun facts (click to expand)</b></summary>
<br/>

- My favourite failure mode is the single-event upset. My second favourite is the one I haven't found yet.
- Competition-math kid who never really stopped.
- Linguistics nerd. Ask me about phonology and I will not stop either.
- I can talk about interrupt controllers at parties. I am rarely invited back.
- I read a lot of fiction to recover from the datasheets.
- If my code works first time, I assume the simulator is broken.

</details>


<div align="center">

<br/>

<sub>you da real profile</sub>

</div>
