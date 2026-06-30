---
layout: page
title: Autonomous Search Rescue System
description: Systems design study for a fully autonomous marine rescue platform using UAV and ASV coordination
importance: 4
category: research
---

**Period:** Oct 2020 – Feb 2021 | Academic Systems Design Study

## Overview

A conceptual architecture for a fully autonomous marine rescue platform addressing the critical challenge of drowning response — overcoming deployment delays, risk to human crews in severe weather, and difficulty of continuous visual monitoring.

## System Architecture

Two autonomous platforms working in coordination:

**UAV Component**
- Detects drowning victims using deep learning
- Deploys a flotation device
- Transmits GPS waypoints to the surface vehicle
- Hardware: Pixhawk 2.4.8, u-blox 7020 GPS, XBee Pro

**Autonomous Surface Vehicle (ASV)**
- Receives GPS waypoints and navigates to victim
- Executes rescue operation
- Hardware: NVIDIA Jetson Nano (deep learning inference), Raspberry Pi 3 Model B+ (navigation and control), XBee Pro

## Key Innovation

Deep learning-based victim detection handles the unique challenges of marine environments — partial human visibility above water, wave reflections, and dynamic motion.

<a href="https://github.com/janinduhm/Autonomous-Search-Rescue-System" target="_blank">GitHub Repository</a>
