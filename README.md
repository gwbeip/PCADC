The PCADC Series Project
============
[![State-of-the-art Shitcode](https://img.shields.io/static/v1?label=State-of-the-art&message=Shitcode&color=7B5804)](https://github.com/trekhleb/state-of-the-art-shitcode)

This repository is an introduction to a series of project named "PCADC" short for "**P**ractice of **C**omputer **A**rchitecture during my **D**octoral **C**andidate".

The series of PCADC are listed below:

| Series Number | ISA | Privilege | pipline depth | Issue | OoO | Status |
| :---: | :----: | :---: | :----: | :------: | :---: | :---: |
| S0 | RV64I | M | multi-cycle | single | N | under dev |


# Features of different series
The features are briefly described here. For more specific description, refer to the documents in repositories of each series.

## PCADC-S0
The main features of [PCADC-S0](https://github.com/gwbeip/PCADCS0) are listed below:
- multi-cycle processor
- RV64-I ISA, machime mode only
- Timmer interrupt
- Support [RT-Thread](https://github.com/RT-Thread/rt-thread) operating system
- It is used for verifing the understanding of the RISC-V ISA. So, in the design time, the efficiency or clock frequency is not seriously considered.

<!--
- Support RISC-V RV64IMAC ISA, pipline multiplier and multicycle divider.
- Machine mode only.
- 5-stage pipline.
- L1 I/D cache.
- Dynamic branch prediction.
- RT-Thread OS support. -->
