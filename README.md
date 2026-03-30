# Wireless Power Transfer System

## Overview
This project designs and simulates a wireless power transfer system using an H-bridge inverter, transformer coupling, rectification, and DC filtering.

## Tools Used
- LTspice
- KiCad

## System Architecture
- DC Source
- H-Bridge Inverter (MOSFET-based)
- Transformer Coupling Stage
- Rectifier
- Output Filter

## Key Results
- Stable DC output achieved through transient simulation
- Minimal ripple after filtering stage
- ~80% theoretical efficiency under ideal coupling conditions

## Key Concepts
- Electromagnetic induction
- Transient response
- Switching behavior of MOSFETs
- Power electronics design

## Files
- `/schematics` → KiCad files
- `/simulations` → LTspice files
- `/results` → waveform screenshots

## Notes
Future improvements include modeling non-ideal coupling and switching losses in greater detail.
