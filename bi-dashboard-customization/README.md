# BI Dashboard & Visualization Customization
## Interactive Prototype

I developed an interactive HTML prototype to explore
customizable BI visualization configurations, including
metric-specific settings, thresholds, progress visualization,
and chart customization.

**[▶ Open Interactive Demo](https://anhthaojb.github.io/professional-experience/bi-dashboard-customization/bar_pie_progress.html)**
## Overview

Worked with frontend and backend developers to customize and test
visualization capabilities for an internal BI product based on
Apache Superset. Developed an interactive prototype for three chart
types, introducing configurable visualization rules and
threshold-based alerts to help users identify metrics requiring attention.

## What I Worked On

### 1. Custom Visualization

Customized **three core chart types**:

* **Bar Chart** — configurable metric visualization with threshold-based styling and comparison options.
* **Progress Chart** — visualizes metric progress against defined targets or thresholds.
* **Pie Chart** — supports configurable slice-level visualization and threshold-based rules.

The customization focused on making visualization behavior configurable while keeping the interaction simple for end users.

---

### 2. Threshold & Alert Logic

Designed a configurable **threshold-based alert mechanism** to help users identify metrics that require attention.

Users can define rules for individual metrics, allowing the visualization to automatically reflect different states based on the configured thresholds.

For example:

```text
Metric
   ↓
Compare with threshold
   ↓
┌───────────────┐
│ Normal        │ → Standard visualization
│ Warning       │ → Attention indicator
│ Critical      │ → Alert indicator
└───────────────┘
```

This allows the dashboard to communicate not only **“what is the value?”**, but also **“does this value require attention?”**

---

### 3. Metric-Specific Configuration

One of the key requirements was supporting different visualization rules for different metrics.

The prototype therefore explores configurations such as:

* Common rules for all metrics
* Individual rules for selected metrics
* Metric-specific threshold values
* Metric-specific visualization states
* Different visual responses based on the selected metric

This makes the same chart component reusable across different KPIs without requiring users to manually configure each visualization from scratch.

---

## Key Features

* Custom configuration for **3 chart types**
* Metric-level threshold configuration
* Alert / warning logic
* Progress visualization
* Conditional visual states
* Flexible metric-specific rules
* Interactive configuration panel
* Reusable visualization settings

---

## My Contribution

* Translated visualization requirements into configurable chart behavior.
* Designed the configuration logic for the three supported chart types.
* Developed threshold-based alert logic for KPI monitoring.
* Tested different metric and threshold combinations.
* Identified and refined inconsistent visualization behavior.
* Worked with frontend/backend developers to align the prototype with BI product requirements.

---

## Technology

**Apache Superset · SQL · HTML · CSS · JavaScript · BI Visualization**

---

## Why It Matters

> The customization focuses on turning static BI charts into more actionable visualizations, where users can configure metrics, define thresholds, and quickly identify indicators that require attention.

---











