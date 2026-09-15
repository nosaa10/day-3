# Day 3 — From Prototype to Enterprise

A staged training lab exploring how a multi-agent report generator gains reliability, configuration, observability, guardrails, and an API.

تطبيق تدريبي لتطوير نموذج أولي لوكلاء الذكاء الاصطناعي وإضافة الاعتمادية والمراقبة وواجهة API.

[All labs](https://github.com/nosaa10/SDAIA-Agentic-AI-Engineering) · [Previous: Research Agent](https://github.com/nosaa10/day-2) · [Next: Security & Monitoring](https://github.com/nosaa10/day-4)

## Learning stages

| Stage | Focus |
| --- | --- |
| 0 | Prototype multi-agent graph |
| 1 | Retries, backoff, timeouts, and graceful failure |
| 2 | Environment-based configuration |
| 3 | Structured logs, latency, and run IDs |
| 4 | Input/output validation and token budget |
| 5 | FastAPI serving |

The source contains student exercises marked `YOUR TURN`.

## Files

- [Python lab](lab_prototype_to_enterprise.py)
- [Dependencies](requirements.txt)
- [Dockerfile](Dockerfile)
- [Docker guide](NEXT_STEPS_DOCKER.md)
- [Saved report](final_report.txt)

## Quick start with a mock model

Create and activate a Python virtual environment, then install dependencies:

```bash
pip install -r requirements.txt
```

**Windows PowerShell**

```powershell
$env:MOCK="1"
$env:LAB_STAGE="3"
python lab_prototype_to_enterprise.py
```

**macOS / Linux**

```bash
MOCK=1 LAB_STAGE=3 python lab_prototype_to_enterprise.py
```

Mock mode uses a fake model and does not require a model API key. See the source header for other stages and serving commands.

## Context

Educational lab materials from the SDAIA program. The stages demonstrate engineering concepts and include exercises; this README does not certify production readiness.
