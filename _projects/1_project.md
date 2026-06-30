---
layout: page
title: Pulse Design for Pre-6G Mobile Radio Systems
description: Constrained optimization of FDSS pulse parameters for pre-6G uplink — M.Sc. thesis at Rohde & Schwarz
importance: 1
category: work
---

**Institution:** University of Kassel — in collaboration with Rohde & Schwarz GmbH & Co. KG, Munich

**Period:** Oct 2025 – Apr 2026

> Implementation code is confidential under the Rohde & Schwarz collaboration agreement and is not published.

---

## Overview

This thesis benchmarks next-generation uplink waveform candidates against the 5G NR baseline, with a focus on optimizing Frequency Domain Spectral Shaping (FDSS) with symmetric spectral extension.

## Waveforms Compared

| Waveform | Role |
|---|---|
| CP-OFDM | 5G NR downlink baseline |
| DFT-s-OFDM | 5G NR uplink baseline |
| FDSS-enhanced DFT-s-OFDM (+ spectral extension) | Primary contribution |
| OTFS | Alternative candidate |

## Optimization Framework

- **Design vector:** truncation factor, roll-off factor, spectral extension ratio
- **Objective:** minimize BER under constraints on PAPR, ACLR, and throughput
- **Channels evaluated:** AWGN, TDL-D (indoor, 3 km/h), TDL-C (high-mobility, 120 km/h)

## Key Finding

The optimization reveals a **two-regime behaviour**:
- At low SNR: BER-optimal configurations prioritize spectral extension
- At high SNR: PAPR-optimal configurations emerge with significantly lower PAPR

Spectral extension consistently recovers the BER penalty of bare FDSS across all regimes.

## Tools

MATLAB (5G NR Toolbox, Communications Toolbox, Signal Processing Toolbox, Parallel Computing Toolbox), LaTeX

<a href="https://github.com/janinduhm/Pulse-Design-for-Pre-6G-Mobile-Radio-Systems" target="_blank">GitHub Repository</a>
