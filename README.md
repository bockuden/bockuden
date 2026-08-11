# Hi, I'm Yehor Maksimov

I help teams build resilient automation and data systems that remain testable,
observable, and recoverable under real-world failures.

Senior .NET/Python engineer with 15+ years of professional C# experience.
My public work spans browser automation, developer tooling, applied ML,
and reproducible data pipelines.

## Work with me

Available for part-time consulting and project-based work in:

- resilient browser and API automation
- developer tooling for failure and recovery testing
- reproducible data and applied-ML pipelines

I am not currently considering full-time roles.

- Email: [bockuden@gmail.com](mailto:bockuden@gmail.com)
- Telegram: [@bockuden](https://t.me/bockuden)

## Flagship open-source work

### [Resilient Automation Test Stand](https://github.com/bockuden/resilient-automation-test-stand)

A ready-to-run deterministic failure sandbox for Playwright, Selenium,
scrapers, and HTTP automation workers.

It provides reproducible browser and API scenarios for transient `503`
responses, permanent failures, delays, authentication, pagination, duplicate
records, DOM changes, cancellation, and checkpoint recovery.

Each run is isolated by `run_id`, allowing the same failure sequence to be
reproduced locally and in CI.

The project is distributed as a Python package and container image. It includes
a CLI, a stable OpenAPI contract, automated compatibility checks, and runnable
resilience examples.

[Repository](https://github.com/bockuden/resilient-automation-test-stand)
· [PyPI](https://pypi.org/project/resilient-automation-test-stand/)
· [Container](https://github.com/bockuden/resilient-automation-test-stand/pkgs/container/resilient-automation-test-stand)
· [Resilience Challenge](https://github.com/bockuden/resilient-automation-test-stand/blob/main/CHALLENGE.md)

### [Resilient Browser Automation](https://github.com/bockuden/resilient-browser-automation)

A production-style .NET 10 and Playwright worker designed for interrupted jobs,
repeated delivery, transient failures, DOM changes, duplicates, cancellation,
and recovery from durable checkpoints.

The project includes:

- SQLite persistence and idempotent processing
- bounded retries, concurrency, and per-target rate limiting
- checkpoint-based resume after interruption
- structured logging and OpenTelemetry metrics
- screenshots, HTML snapshots, traces, and machine-readable failure evidence
- unit, integration, and deterministic browser E2E tests
- a reproducible Docker Compose demo

The worker is validated against a pinned release of the independently published
[Resilient Automation Test Stand](https://github.com/bockuden/resilient-automation-test-stand).

[Repository](https://github.com/bockuden/resilient-browser-automation)
· [Release](https://github.com/bockuden/resilient-browser-automation/releases)
· [Architecture](https://github.com/bockuden/resilient-browser-automation/blob/main/docs/architecture.md)
· [Compatibility matrix](https://github.com/bockuden/resilient-browser-automation/blob/main/docs/compatibility-matrix.md)

## Security & Applied ML

### [FlowSentinel — PCAP Intrusion Detection & Anomaly Scoring](https://github.com/bockuden/pcap-intrusion-detection)

I built a reproducible, resource-aware PCAP analytics pipeline with
leakage-aware validation, transparent model comparison, resumable data
processing, and safe local scoring.

FlowSentinel converts multi-gigabyte CICIoT2023 captures into auditable
packet-feature datasets, keeps TCP flows disjoint across train, validation,
and test, and supports both supervised intrusion classification and
benign-only anomaly scoring. The published benchmark compares tabular,
neural, and unsupervised baselines without claiming unseen-capture
generalization where the source data cannot support it.

[Repository](https://github.com/bockuden/pcap-intrusion-detection)
· [Release](https://github.com/bockuden/pcap-intrusion-detection/releases/tag/v0.1.0)
· [Benchmark](https://github.com/bockuden/pcap-intrusion-detection/blob/main/docs/RESULTS_V0.1.0.md)
· [Data card](https://github.com/bockuden/pcap-intrusion-detection/blob/main/docs/DATA_CARD.md)

## Applied research

My research repositories emphasize explicit assumptions, evidence provenance,
reproducible pipelines, and honest reporting of negative or inconclusive
results.

| Project | Research question | Approach | Current conclusion |
| --- | --- | --- | --- |
| [OpenAI 30 GW U.S. Grid Exposure Screen](https://github.com/bockuden/openai-30gw-grid-exposure) | How sensitive could U.S. balancing authorities be to different hypothetical allocations of 30 GW of compute load? | EIA data, scenario analysis, evidence ledger, data-quality audits, robustness checks, and reproducible offline builds | A dispersed load is modest relative to combined national peak, while concentrated deployment can create materially larger local exposure. This is an independent sensitivity study, not a siting or blackout forecast. |
| [US Fertility, Housing, and Income Drivers](https://github.com/bockuden/us-fertility-housing-income) | How are housing costs, housing structure, income, and fertility associated across different levels of U.S. data? | State-year baseline, metro fixed-effects models, and SIPP household-panel analysis | Housing-related signals remain visible in richer panel designs, but the current evidence does not justify a simple causal claim. |
| [Crypto Cointegration Stability Study](https://github.com/bockuden/crypto-cointegration-research) | Do highly correlated crypto perpetual pairs remain cointegrated and economically useful out of sample? | Rolling correlation, Engle–Granger tests, stability filters, walk-forward evaluation, and trading-cost modeling | Most candidates are unstable or unprofitable. The limited positive result is exploratory and requires confirmation on untouched data. |

## Engineering background

- 15+ years of professional C# development
- Browser automation and reliable web data extraction
- Python, FastAPI, Playwright, and SQLite
- Resilient workers, retries, idempotency, and checkpoint recovery
- OpenCV, TensorFlow, and applied machine learning
- Time-series analysis, econometrics, and quantitative research
- Reproducible data pipelines and research artifacts
- University degree in education, specializing in physics and mathematics teaching
