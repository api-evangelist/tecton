# Tecton

Tecton is the enterprise feature platform (feature store) for real-time machine learning and AI at scale. It transforms raw batch, streaming, and real-time data into ML-ready features and embeddings, orchestrates the pipelines that materialize them, and serves them to models online with low latency and ~100ms freshness while guaranteeing training/serving consistency.

- Website: https://www.tecton.ai
- Documentation: https://docs.tecton.ai
- Status: https://tecton.statuspage.io
- GitHub: https://github.com/tecton-ai
- Backed by: a16z, Lux Capital, SV Angel

## Developer surface
- **FeatureService HTTP API** — low-latency online feature serving (single/batch reads, wildcard queries, metadata); `Authorization: Tecton-key <key>` bound to Service Accounts.
- **Python SDK** (`pip install tecton`) — feature-as-code definition, apply, and testing; ships the `tecton` CLI.
- **Clients** — `tecton-client` (Python) and `ai.tecton:java-client` / `ai.tecton:http-client` (Java) wrap the HTTP API.
- **Compliance** — SOC 2, ISO 27001, GDPR.

Enriched by the API Evangelist enrichment pipeline (local-v1) on 2026-07-21.
