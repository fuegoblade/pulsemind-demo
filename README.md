# PulseMind™ Demo (Limited)

This repository contains a **restricted demo** of PulseMind™ — an AI‑assisted module that turns wearable signals
(HR, HRV, sleep, training load) into *readiness* and *overload risk* indicators.

> ⚠️ **Security & Scope**
> - This demo **does not** include the production AI weights, feature engineering, or proprietary heuristics.
> - Calculations here are **mocked/simplified** and intended **only for concept demonstration** with sample data.

---

## Quick Start (no build required)
Open `index.html` in a modern browser. You can:
- Paste or load the `data/sample_week.json`
- Press **Evaluate** to see **Readiness Score** and **Overload Risk** from simplified logic

> This is fully client‑side and works offline. No API keys required.

---

## Files
- `index.html` – self‑contained demo UI + simplified calculators (vanilla JS)
- `data/sample_week.json` – anonymized synthetic dataset (HR/HRV/sleep/load for 7 days)
- `docs/SECURITY_NOTES.md` – what’s intentionally omitted from this demo
- `LICENSE-DEMO.txt` – demo‑only license and usage rules
- `README.md` – this guide

---

## What’s intentionally omitted
- Feature pipelines, signal cleaning, and adaptive windows
- Production readiness model and overload classifier
- Personalization layers, constraints and alerting logic
- Any third‑party API client code or secrets

For production or licensing discussions, please reach out.
