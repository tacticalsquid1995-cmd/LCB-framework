# LCB(w): A Vector-Based Framework for Evaluating Linguistic and Moral Actions

A compact evaluative framework that models linguistic tokens and actions as vectors in a three-dimensional moral-operational space.

## Quick Start
- See `LCB_framework.md` for the full paper
- See `arrow_codes.md` for the symbolic notation reference

## Overview
LCB(w) maps each word or action to a vector representing its effects on:
- **L** (Life/Legitimacy): effect on dignity, trust, stability, moral standing
- **C** (Cost/Harm): resource expenditure, risk, burden, damage  
- **B** (Benefit): value creation, utility, positive outcome

By treating words as force vectors rather than definitions, LCB(w) captures the real-world operational consequences of linguistic acts.

## Key Formula
```
Score = wL·L - wC·C + wB·B
```

Where:
- wL, wC, wB are normative weights
- L, C, B are normalized vectors in [-1, 1]

## Applications
- Governance & policy justification
- AI alignment & safety
- Ethics & moral philosophy
- Institutional transparency

## Paper Details
**Author:** Aaron Murray  
**Date:** 2026  
**Framework:** LCB(w) - Weighted Vector Evaluation Model