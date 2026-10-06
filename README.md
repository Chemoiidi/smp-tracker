# SMP Tracker

A 28-day performance analysis tracker for the Self-Made Protocol (SMP) fitness program.

Analyzes daily steps, sleep, water intake, fasting protocol, cold showers, and bench press performance using Pandas and NumPy.

## What It Does

* Stores and analyzes 28 days of fitness tracking data
* Inspects the dataset for shape, columns, data types, and missing values
* Identifies high-performance days based on 10,000+ steps and 7.5+ hours of sleep
* Compares performance across OMAD and 2MAD fasting protocols
* Calculates statistical metrics such as averages, standard deviation, percentiles, and correlations
* Tracks weekly step and bench press performance
* Identifies the top 3 days by step count
* Generates a formatted 28-day fitness analysis report

## Setup

```bash
pip install -r requirements.txt
```

## Usage

```bash
python tracker.py
```

The script will analyze the 28-day dataset and display:

* Overall fitness metrics
* Total and average daily steps
* Number and percentage of days reaching 10,000 steps
* Average sleep duration
* Bench press range and trend
* Week-by-week performance
* Fasting protocol comparison
* Top 3 step-count days

## Sample Output

```
======================================================
  SMP 28-DAY FITNESS ANALYSIS REPORT
======================================================

  OVERALL METRICS
  Days tracked:             28
  Total steps:              ...
  Avg daily steps:          ...
  Days hitting 10k:         .../28  (...%)
  Avg sleep:                ... hrs
  Bench press range:        ... to ... kg
  Bench press trend:        +... kg (wk1 to wk4)

  WEEKLY BREAKDOWN
  Week      Avg Steps  10k Days  Avg Bench
  --------------------------------------------
  Week 1       ...        .../7       ... kg
  Week 2       ...        .../7       ... kg
  Week 3       ...        .../7       ... kg
  Week 4       ...        .../7       ... kg

  PROTOCOL COMPARISON
  2MAD: avg steps=..., sleep=...h, bench=...kg
  OMAD: avg steps=..., sleep=...h, bench=...kg

  TOP 3 STEP DAYS
  Day ...: ... steps  (...)
  Day ...: ... steps  (...)
  Day ...: ... steps  (...)

======================================================
```

## Stack

Python, Pandas, NumPy.