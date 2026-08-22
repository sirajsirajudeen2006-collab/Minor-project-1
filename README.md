# GroupDNA — WhatsApp Group Chat Analyzer

A Python analytics tool that decodes a WhatsApp group chat export into a personality and
activity report — active members, busiest hours, favourite words, response speed, silent
streaks, and a personality archetype for every participant. Built entirely with Python
fundamentals and NumPy — no pandas, no matplotlib, no regex, no collections.

## Project Info
- **Project:** GroupDNA (Week 1 Minor Project — The Unlox Academy)
- **Author:** Sirajudeen
- **Roll Number:** UNXBSARCIST-1360

## What's in this repo
- `GroupDNA_Sirajudeen_UNXBSARCIST-1360.ipynb` — the full analysis notebook
- `hostel_bois.txt` — the provided synthetic WhatsApp dataset (60 days, 6 participants, 3,174 messages)
- `README.md` — this file

## Constraints (what was allowed / forbidden)
**Allowed:** Python fundamentals (loops, conditionals, functions, f-strings), lists/tuples/sets/dicts,
NumPy, `open()`/file reading, `datetime.strptime` + `timedelta`, string methods, list/dict
comprehensions, `sorted()` with `key=`.

**Forbidden:** pandas, matplotlib/seaborn/plotly, `collections.Counter`/`defaultdict`, `re` (regex),
any pre-built chat analyzer, any AI/ML library.

## Features implemented
1. Chat parser — handles system messages, media-omitted, deleted messages, multi-line continuations
2. Group overview — totals, date range, per-person message share
3. Most active day & hour
4. NumPy 6×24 activity heatmap, rendered as block-character
