# Latch-based-Integrated-Clock-Gating-Cell
The purpose of this Hackathon is to implement the proposed design in 28 nm PDK (Process Design Kit).

This is a Report Submission for successful completion of Latch-based-Integrated-Clock-Gating-Cell simulating the proposed circuit as a result of literature survey conducted, for  [Cloud Based Analog IC Design Hackathon](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/)

## Table of Contents
- [Introduction](#introduction)
- [Reference_Circuit](#reference_circuit)
- [Implementation](#implementation)
- [Schematic_Netlist_Waveform](#schematic_netlist_waveform)
- [Methodology](#methodology)
- [Challenge](#challenge)
- [Troubleshooting](#troubleshooting)
- [Reproduce_waveforms](#reproduce_waveforms)
- [Limitations](#limitations)
- [References](#references)
- [Acknowledgements](#acknowledgements)
- [Author](#author)

## Introduction
Now a days in ASIC design there are billions of cells due to which power becomes a crucial factor in determining the quality of a chip. Due do this huge no of cells, there’s a high switching activity of clock, which consumes a lot of dynamic power. So, in order to reduce dynamic power consumption in chip, one of the techniques used is clock gating. For instance If the flops work based on enable signal there is no need of providing each and every pulse of clock, instead of that we provide a selective pulse to flop which reduces the switching factor of clock.
