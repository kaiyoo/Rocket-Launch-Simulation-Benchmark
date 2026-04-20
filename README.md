# Measuring Progress Toward AGI - Cognitive Abilities

This project is a benchmark designed to evaluate the cognitive abilities of large language models (LLMs) in the **Executive Functions Track** of the Kaggle competition *Measuring Progress Toward AGI - Cognitive Abilities*, hosted by Google DeepMind.

- Kaggle Competition: [Link](https://www.kaggle.com/competitions/kaggle-measuring-agi)  
- Benchmark Page: [Link](https://www.kaggle.com/benchmarks/kaiyoo88/rocket-launch-baseline?_gl=1*1dbkh4s*_ga*MTIzMTE4NzMyNC4xNzc1Nzg2MzE2*_ga_T7QHS60L4Q*czE3NzY2NTE2MDIkbzQkZzEkdDE3NzY2NTcxODckajU5JGwwJGgw)  
- Project Writeup: [Link](https://www.kaggle.com/competitions/kaggle-measuring-agi/writeups/new-writeup-1776304911484)

---

## Leaderboard

Below is a snapshot of benchmark results across different models and tasks:

![Leaderboard](./leaderboard.png)

---

## Overview

This project presents a benchmark for evaluating large language models (LLMs) in a structured, state-based decision-making setting using a **Europa exploration mission scenario**.

The benchmark simulates a full end-to-end pipeline:

- Launching from Earth  
- Traveling to Europa (a moon of Jupiter)  
- Drilling through ice  
- Extracting water  
- Generating hydrogen via electrolysis  
- Refueling  
- Collecting samples  
- Returning to Earth  

At each step, the model must select the most appropriate action based on the current state and constraints.

---

## Motivation

Unlike traditional QA-style benchmarks, this setup requires:

- Sequential reasoning  
- Policy-level decision making  
- Adaptation to dynamic environments  

Models must not only choose correct actions but also:

- Maintain consistency over time  
- Adapt to changing conditions  
- Avoid unsafe or invalid behaviors  

This benchmark is designed to evaluate **Executive Functions** in LLMs rather than static knowledge.

---

## Benchmark Tasks

The benchmark is composed of four complementary tasks:

### 1. Planning
Evaluates long-horizon reasoning through multi-step action prediction.

### 2. Working Memory
Tests the ability to use past context when parts of the current state are hidden.

### 3. Flexibility
Measures adaptation across stage transitions without repeating outdated strategies.

### 4. Robustness
Penalizes invalid or critical failure actions to assess safety and reliability.

---

## Key Features

- State-based decision-making framework  
- Sequential, multi-step reasoning evaluation  
- Safety-aware scoring (critical failure penalties)  
- Policy-level evaluation beyond single-step accuracy  

---

## Goal

This benchmark aims to provide a more realistic evaluation of LLM capabilities by measuring:

- Planning ability  
- Memory utilization  
- Adaptability  
- Safe decision-making  

Together, these tasks offer a comprehensive assessment of **cognitive abilities relevant to AGI** in sequential environments.
