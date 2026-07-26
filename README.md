# Hi, I'm Yehor Maksimov

Senior Software Engineer building resilient automation, developer tools,
and reproducible data and ML systems.

**15+ years in C# · Python and FastAPI · Browser Automation · Applied ML · Time-Series Research**

I combine production-oriented software engineering with applied research.
My work focuses on systems that remain testable, explainable, and
reproducible under real-world constraints.

## Featured open-source work

### [Resilient Automation Test Stand](https://github.com/bockuden/resilient-automation-test-stand)

An open-source, ready-to-run failure sandbox for Playwright, Selenium,
scrapers, and HTTP automation workers.

It provides deterministic stateful scenarios for transient `503` responses,
permanent failures, delays, login flows, pagination, duplicate records,
DOM changes, cancellation, and checkpoint/recovery testing. Runs are isolated
by `run_id`, making failure sequences reproducible locally and in CI.

Published as a
[Python package](https://pypi.org/project/resilient-automation-test-stand/)
with a CLI, container releases, a stable OpenAPI contract, and automated
compatibility checks.

[Repository](https://github.com/bockuden/resilient-automation-test-stand)
· [PyPI](https://pypi.org/project/resilient-automation-test-stand/)
· [Resilience Challenge](https://github.com/bockuden/resilient-automation-test-stand/blob/main/CHALLENGE.md)

### [Resilient Browser Automation](https://github.com/bockuden/resilient-browser-automation)

A production-style .NET and Playwright worker designed for interrupted jobs,
repeated delivery, retries, DOM changes, duplicates, cancellation, and
recovery from durable checkpoints.

The project includes SQLite persistence, bounded concurrency, structured
logging, failure evidence, deterministic end-to-end tests, Docker Compose,
and GitHub Actions.

It is validated against the independently released
[Resilient Automation Test Stand](https://github.com/bockuden/resilient-automation-test-stand).

### [OpenAI 30 GW U.S. Grid Exposure Screen](https://github.com/bockuden/openai-30gw-grid-exposure)

A reproducible balancing-authority-level sensitivity study of hypothetical
large compute loads on the U.S. electrical grid.

The project emphasizes evidence provenance, data-quality auditing, explicit
scenario boundaries, robustness checks, and reproducible offline builds.

### [US Fertility, Housing, and Income Drivers](https://github.com/bockuden/us-fertility-housing-income)

A public-data research pipeline progressing from a state-level baseline to
metro fixed-effects models and household-panel analysis.

The repository documents how data limitations, geographic resolution, and
identification assumptions affect the conclusions.

### [Crypto Cointegration Stability Study](https://github.com/bockuden/crypto-cointegration-research)

Reproducible quantitative research on rolling correlation, Engle–Granger
cointegration, stability, and out-of-sample mean-reversion tests for crypto
perpetual pairs.

The study reports negative and inconclusive results alongside promising ones,
without presenting exploratory backtests as production trading claims.

## Background

- 15+ years of C# development, browser automation, and web data extraction
- Python, FastAPI, OpenCV, TensorFlow, and applied machine learning
- Quantitative strategy research and backtesting
- Time-series analysis and reproducible data pipelines
- University degree in physics and mathematics education

## Current focus

- Open-source developer tooling
- Resilient browser automation
- Production-oriented data and ML pipelines
- Reproducible quantitative research
