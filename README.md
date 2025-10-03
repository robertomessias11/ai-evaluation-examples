# ai-evaluation-examples

Examples of AI response evaluation (A/B testing): compare answers, rate quality, and justify decisions.

## Overview
This repository provides small A/B evaluation cases for AI-generated outputs.  
It includes markdown cases, an evaluation template, and a Python script to export judgments into CSV format.

## Structure
- `cases/` — Example A/B cases with paired answers.  
- `templates/` — Evaluation template for consistent judgments.  
- `scripts/` — Tools to parse cases and export judgments.  
- `.github/workflows/` — Simple lint workflow with GitHub Actions.  

## Usage
1. Explore `cases/` and read the paired answers.  
2. Use `templates/evaluation_template.md` to write judgments.  
3. Run `scripts/export_judgments.py` to generate `judgments.csv`:

```bash
python scripts/export_judgments.py
