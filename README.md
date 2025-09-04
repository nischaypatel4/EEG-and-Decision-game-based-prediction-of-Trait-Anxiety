# EEG and Decision Game-Based Prediction of Trait Anxiety

## Project Overview

This project aims to **predict trait anxiety levels** using a combination of **behavioral patterns** and **EEG signals** collected during a decision-making game. By leveraging **machine learning (ML)** and **deep learning (DL)** techniques, we seek to build **computational models** that provide a more objective understanding of anxiety—beyond traditional self-report tools.

---

## Problem Statement

Trait anxiety significantly impacts cognitive processes like decision-making, attentional control, and emotional regulation. While tools like the **State-Trait Anxiety Inventory (STAI)** offer psychological insight, they lack the neurophysiological depth needed for computational psychiatry.

This study integrates **EEG data**, **game-based behavior**, and **neurophysiological signals** (e.g., cortisol, norepinephrine) to build models capable of **distinguishing trait anxiety patterns** in naturalistic settings.

---

## Background & Significance

### 1. Trait vs. State Anxiety
- **Trait Anxiety:** Chronic tendency to feel anxious; stable across situations.
- **State Anxiety:** Transient anxiety response to specific events or stressors.

> Our focus is on **trait anxiety**, as it provides more consistent neural and behavioral markers.

### 2. Why Foraging Tasks?
- Foraging tasks simulate **real-world decisions under uncertainty**, ideal for studying anxiety-related cognitive mechanisms.
- Based on neuroscience findings on **theta-phase precession**, foraging tasks reflect natural decision-making circuits.

### 3. EEG as a Neurophysiological Marker
EEG frequency bands and their functions under anxiety:

| Wave Type | Frequency | Function | Effect in Anxiety/Stress |
|-----------|-----------|----------|---------------------------|
| **Delta** | 0.5–4 Hz  | Deep sleep, healing | ↓ Decreases |
| **Theta** | 4–8 Hz    | Emotion, memory | ↑ Increases |
| **Alpha** | 8–12 Hz   | Relaxation, clarity | ↓ Decreases |
| **Beta**  | 12–30 Hz  | Focus, alertness | ↑ Increases |
| **Gamma** | 30–50 Hz  | Cognition, fear response | ↑ Spikes in PTSD/trauma |

---

## Physiological & Neuromodulatory Data

### 1. Stress Pathways:
- **HPA Axis:** Cortisol regulation → Mood, energy, and anxiety modulation
- **SAM Axis:** Norepinephrine release → Heightened alertness (fight or flight)

### 2. Biomarkers:
- **Salivary cortisol** (pre- and post-game)
- **Salivary alpha-amylase (sAA)** for norepinephrine activity
- Ensured no significant increase in **state anxiety**, isolating trait anxiety effects

---

## Decision-Making Task Design

Data collected during 3 key windows:

### Tonic Epoch
- EEG recorded **1000 ms before decision**
- Captures brain activity during deliberation

### Decision Window
- Participant moves to center before choosing to **explore** (switch tree) or **exploit** (stay)
- Longer deliberation = greater hesitation

### Execution Window
- Time taken to **move mouse and click**
- Faster response = confidence  
- Slower response = hesitation or reconsideration

---

## Participants & Trials

- **N = 55 participants** (18 females)
- Each performed **~200–250 trials**
- Each trial = a single decision (explore/exploit)


