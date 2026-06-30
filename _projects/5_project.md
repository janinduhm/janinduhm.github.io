---
layout: page
title: Root-Finding IC
description: Digital IC for root-finding using IEEE-754 16-bit floating-point with FPU and Taylor series
importance: 5
category: engineering
---

**Period:** Nov 2019 – Jan 2020

## Overview

A digital IC designed for root-finding operations using the **IEEE-754 16-bit** floating-point format, featuring a **Floating Point Unit (FPU)** and a **Master Algorithm Unit (MAU)**.

## Design

- Implemented arithmetic operations (addition, subtraction, multiplication, division) in IEEE-754 16-bit format
- Developed hardware logic for **ln(x)** approximation using a 5th-order **Chebyshev polynomial** evaluated via Horner's method
- Includes normalization logic and internal data flow control between FPU and MAU
- Verified through simulation testbenches

## Tools

Verilog HDL

<a href="https://github.com/janinduhm/Root-Finding-IC" target="_blank">GitHub Repository</a>
