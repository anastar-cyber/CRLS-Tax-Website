# TaxEcon — Supply, Demand & Taxes Interactive Learning Game

An interactive web-based economics game designed for high school students to learn about supply and demand, taxation models, and income tax systems through live simulations, charts, and quizzes.

## Overview

TaxEcon is a single-file HTML application that guides students through five progressive modules, each building on the last. Students interact with live charts, adjust tax sliders, and test their knowledge — all without any setup or installation.

## Features

- **5 Learning Modules** covering supply/demand fundamentals through advanced tax concepts
- **Interactive supply & demand charts** rendered with HTML5 Canvas
- **Live tax simulators** with real-time price and quantity recalculation
- **Income tax calculator** using real 2024 U.S. federal tax brackets
- **10-question quiz** with instant feedback and explanations
- **Progress tracking** via a visual dot indicator in the navigation bar
- **No dependencies** — runs entirely in the browser from a single HTML file

## Modules

### Module 1 — Supply & Demand Basics
- The demand and supply curve model
- Equilibrium price and quantity (P* and Q*)
- Surplus and shortage zones
- Interactive curve shift simulator (demand shifts right, supply shifts left)

### Module 2 — Consumer Tax
- How a per-unit tax on consumers shifts the demand curve left
- Live slider ($0–$60 tax) updates the chart in real time
- Readout shows: consumer price, producer price, quantity traded, government revenue, and deadweight loss
- Explanation of tax burden splitting (tax incidence)

### Module 3 — Producer Tax
- How a per-unit tax on producers shifts the supply curve left (upward)
- Same live slider simulation as Module 2 for direct comparison
- Side-by-side comparison table: Consumer Tax vs. Producer Tax
- Demonstrates the **Tax Equivalence Theorem** — identical economic outcomes regardless of who legally pays

### Module 4 — Tax Types & Income Tax
- **Tax structures:** Progressive, Regressive, and Proportional (Flat) taxes explained with examples
- **Income Tax Calculator:** Enter any income from $10k–$500k; calculates total tax, effective rate, marginal rate, and monthly take-home pay using 2024 U.S. federal brackets
- **Busts the common myth** that a raise can cause you to take home less money
- **Other tax types:** Sales tax, payroll tax, property tax, excise/sin tax, capital gains tax, corporate tax
- **Visual comparison chart** showing how effective tax rate changes with income across all three structures

### Module 5 — Quiz
- 10 multiple-choice questions
- Instant correct/incorrect feedback with a full explanation for every answer
- Final score with percentage and a personalized message
- Retake option and link back to review material

## How to Use

1. Open `economics-tax-game.html` in any modern web browser
2. No internet connection required after the initial page load (Google Fonts are loaded from CDN)
3. Navigate using the top navigation bar or the Next/Back buttons at the bottom of each module
4. Progress dots in the top-right corner show which modules have been visited

## Technical Details

- **Single file:** All HTML, CSS, and JavaScript in one `.html` file — no build step, no framework
- **Charts:** Drawn with native HTML5 Canvas API (no charting library)
- **Fonts:** Syne (headings), DM Mono (labels/code), Nunito (body) via Google Fonts
- **Economics model used:**
  - Demand: P = 100 − Q/2
  - Supply: P = 20 + Q/2
  - Baseline equilibrium: P* = $60, Q* = 80 units
  - Tax effects calculated algebraically in real time

## Learning Outcomes

By the end of TaxEcon, students will be able to:

- Draw and interpret a supply and demand diagram
- Explain how a consumer tax shifts the demand curve and affects equilibrium
- Explain how a producer tax shifts the supply curve and affects equilibrium
- Define deadweight loss and explain why it represents a cost to society
- State the Tax Equivalence Theorem and explain what it means
- Distinguish between progressive, regressive, and proportional tax systems
- Calculate effective and marginal income tax rates
- Name and describe at least five types of taxes used in the U.S.

## Compatibility

Works in all modern browsers: Chrome, Firefox, Safari, Edge. No plugins or extensions required.
