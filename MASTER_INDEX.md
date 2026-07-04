# AI Research Baseline — Master Index

Curated forks under `sureshsolannki-ai/` (personal, original 6 domains) and `sureshsolanki-labs/` (org, LCA & Climate/Geospatial AI tranche), cloned locally under `/Users/sureshsolanki/ai-research/`.
Each repo has a `RESEARCH_NOTES.md` on branch `ai-research-baseline`.

**Baseline date:** 2026-07-04
**Total repos tracked:** 45
**Scoring cutoff applied:** total >= 18/25 (relevance + activity + code quality + license + docs)
**License filter:** permissive only (MIT / Apache-2.0 / BSD-2-Clause / BSD-3-Clause / MPL-2.0). Four documented deviations admitted by explicit user decision — flagged in-row and in each `RESEARCH_NOTES.md`:
- `timescaledb` — NOASSERTION (TSL + Apache-2.0 dual)
- `pytorch` — NOASSERTION (BSD-3-style + patent grant; practically permissive)
- `autogen` — CC-BY-4.0 (docs licence, not code)
- `redis` — NOASSERTION (Redis 8+ triple: RSALv2 + SSPLv1 + AGPLv3; **none permissive** — prefer `valkey-io/valkey` for production)

| Domain | Repo | Local Path | Use Case | Adaptation Priority |
|---|---|---|---|---|
| Agentic AI / Adaptive Intelligence | [crewAIInc/crewAI](https://github.com/sureshsolannki-ai/crewAI) | `ai-research/crewAI` | Multi-agent orchestration for chamelion-agent evidence/calibration/batch-lifecycle workflows | **High** |
| Agentic AI / Adaptive Intelligence | [langchain-ai/langgraph](https://github.com/sureshsolannki-ai/langgraph) | `ai-research/langgraph` | Graph-state modelling for evidence-pipeline choreography and onboarding flows | **High** |
| Agentic AI / Adaptive Intelligence | [openai/openai-agents-python](https://github.com/sureshsolannki-ai/openai-agents-python) | `ai-research/openai-agents-python` | Compact multi-agent primitives; reference for report drafting / verifier Q&A | Med |
| Multimodal & Perception | [NVlabs/VILA](https://github.com/sureshsolannki-ai/VILA) | `ai-research/VILA` | Edge VLM for on-site biochar batch QA (color, granularity, kiln residue) | Med |
| Multimodal & Perception | [QwenLM/Qwen3-VL](https://github.com/sureshsolannki-ai/Qwen3-VL) | `ai-research/Qwen3-VL` | Multimodal doc extraction (invoices, calibration certs, verifier reports; multilingual) | Med |
| Multimodal & Perception | [LLaVA-VL/LLaVA-NeXT](https://github.com/sureshsolannki-ai/LLaVA-NeXT) | `ai-research/LLaVA-NeXT` | Open VLM lineage baseline for reproducibility checks | Med |
| Robotics | [huggingface/lerobot](https://github.com/sureshsolannki-ai/lerobot) | `ai-research/lerobot` | Dataset format reference for structured sensor+camera evidence; future automated samplers | **High** |
| Robotics | [google-deepmind/mujoco](https://github.com/sureshsolannki-ai/mujoco) | `ai-research/mujoco` | Physics sim reference; potential future sampler simulation | Med |
| Robotics | [openvla/openvla](https://github.com/sureshsolannki-ai/openvla) | `ai-research/openvla` | Vision-language-action deferred; track releases only | Low |
| Sustainability & Climate | [mlco2/codecarbon](https://github.com/sureshsolannki-ai/codecarbon) | `ai-research/codecarbon` | Track chamelion-agent inference emissions (self-scope-2 of the dMRV runtime) | **High** |
| Sustainability & Climate | [Green-Software-Foundation/if](https://github.com/sureshsolannki-ai/if) | `ai-research/if` | GSF Impact Framework alignment; transparent platform footprint | **High** |
| Sustainability & Climate | [openclimatedata/openclimatedata](https://github.com/sureshsolannki-ai/openclimatedata) | `ai-research/openclimatedata` | Reference climate dataset index for verifier docs | Low |
| Biochar | [NatLabRockies/multiscale-biomass-pyrolysis](https://github.com/sureshsolannki-ai/multiscale-biomass-pyrolysis) | `ai-research/multiscale-biomass-pyrolysis` | Multiscale kinetic modelling; batch-lifecycle parameter priors | **High** |
| Biochar | [SinceraXY/LLMs-BiocharPredict](https://github.com/sureshsolannki-ai/LLMs-BiocharPredict) | `ai-research/LLMs-BiocharPredict` | LLM+ML biochar property prediction; comparator for field-measured chars | **High** |
| AI Foundation & Infra | [ollama/ollama](https://github.com/sureshsolannki-ai/ollama) | `ai-research/ollama` | Local LLM runtime for offline/edge (Akshaya Dhara rural, air-gapped verifier tools) | **High** |
| AI Foundation & Infra | [vllm-project/vllm](https://github.com/sureshsolannki-ai/vllm) | `ai-research/vllm` | Server-side LLM serving for centralized chamelion.ai workflows | Med |
| AI Foundation & Infra | [ray-project/ray](https://github.com/sureshsolannki-ai/ray) | `ai-research/ray` | Distributed compute for batch evidence-pipeline jobs | Med |
| Sustainability & Climate | [brightway-lca/brightway2](https://github.com/sureshsolanki-labs/brightway2) | `ai-research/brightway2` | Foundational LCA metapackage for biochar life-cycle characterisation (biomass → pyrolysis → application) | **High** |
| Sustainability & Climate | [os-climate/ITR](https://github.com/sureshsolanki-labs/ITR) | `ai-research/ITR` | Implied Temperature Rise methodology; portfolio-level climate alignment roll-up interface | **High** |
| Sustainability & Climate | [google-deepmind/graphcast](https://github.com/sureshsolanki-labs/graphcast) | `ai-research/graphcast` | Global weather forecasting; biomass sourcing seasonality & site climate context (advisory only) | Med |
| Sustainability & Climate | [torchgeo/torchgeo](https://github.com/sureshsolanki-labs/torchgeo) | `ai-research/torchgeo` | Geospatial ML for biomass availability, land-use change, post-application soil monitoring | **High** |
| Sustainability & Climate | [PyPSA/PyPSA](https://github.com/sureshsolanki-labs/PyPSA) | `ai-research/PyPSA` | Power system analysis for plant-level electricity footprint / scope-2 modelling | Med |
| Productivity & Tooling | [astral-sh/uv](https://github.com/sureshsolanki-labs/uv) | `ai-research/uv` | Rust-based Python installer/resolver; default across ai-research Python work | **High** |
| Productivity & Tooling | [astral-sh/ruff](https://github.com/sureshsolanki-labs/ruff) | `ai-research/ruff` | Uniform Python linter + formatter across research forks | **High** |
| Productivity & Tooling | [mlflow/mlflow](https://github.com/sureshsolanki-labs/mlflow) | `ai-research/mlflow` | Track VLM / biochar-property / LLM eval runs; internal provenance only | **High** |
| Productivity & Tooling | [iterative/dvc](https://github.com/sureshsolanki-labs/dvc) | `ai-research/dvc` | Dataset versioning for research benchmarks (never the canonical evidence store) | **High** |
| Productivity & Tooling | [tiangolo/fastapi](https://github.com/sureshsolanki-labs/fastapi) | `ai-research/fastapi` | Async Python framework for optional ML inference sidecars | Med |
| Productivity & Tooling | [dagster-io/dagster](https://github.com/sureshsolanki-labs/dagster) | `ai-research/dagster` | Orchestration for offline evidence-analysis batch jobs (research only) | Med |
| Database & Storage | [supabase/supabase](https://github.com/sureshsolanki-labs/supabase) | `ai-research/supabase` | Postgres BaaS reference (auth/RLS patterns); not a production fit | Med |
| Database & Storage | [supabase/supabase-py](https://github.com/sureshsolanki-labs/supabase-py) | `ai-research/supabase-py` | Python client for Supabase; reference only | Med |
| Database & Storage | [chroma-core/chroma](https://github.com/sureshsolanki-labs/chroma) | `ai-research/chroma` | Vector DB for methodology/doc RAG (advisory tier, off canonical path) | **High** |
| Database & Storage | [qdrant/qdrant](https://github.com/sureshsolanki-labs/qdrant) | `ai-research/qdrant` | Production-grade vector DB (Rust); comparator to chroma | **High** |
| Database & Storage | [sqlalchemy/sqlalchemy](https://github.com/sureshsolanki-labs/sqlalchemy) | `ai-research/sqlalchemy` | Standard Python ORM for auxiliary tooling | Med |
| Database & Storage | [duckdb/duckdb](https://github.com/sureshsolanki-labs/duckdb) | `ai-research/duckdb` | In-process analytics engine for evidence-package extracts | **High** |
| Database & Storage | [timescale/timescaledb](https://github.com/sureshsolanki-labs/timescaledb) | `ai-research/timescaledb` | Time-series DB; sensor-stream reference. **⚠ NOASSERTION (TSL + Apache-2.0 dual)** — verify licence before adapting | **High** |
| Database & Storage | [delta-io/delta-rs](https://github.com/sureshsolanki-labs/delta-rs) | `ai-research/delta-rs` | Rust Delta Lake bindings; reference for future evidence-archive volumes | Med |
| Database & Storage | [apache/arrow](https://github.com/sureshsolanki-labs/arrow) | `ai-research/arrow` | Columnar interchange format for cross-language evidence handoff | **High** |
| AI Foundation & Infra | [huggingface/transformers](https://github.com/sureshsolanki-labs/transformers) | `ai-research/transformers` | Foundation model library; VLM/LLM benchmarks, tokenizers, adapters | **High** |
| AI Foundation & Infra | [pytorch/pytorch](https://github.com/sureshsolanki-labs/pytorch) | `ai-research/pytorch` | Underlying DL framework for VLM / biochar-property / geospatial ML. **⚠ NOASSERTION (BSD-3-style + patent grant)** | **High** |
| Agentic AI / Adaptive Intelligence | [langchain-ai/langchain](https://github.com/sureshsolanki-labs/langchain) | `ai-research/langchain` | LLM app framework; retrieval/prompt/tool pattern reference (langgraph still preferred for stateful agents) | **High** |
| Agentic AI / Adaptive Intelligence | [microsoft/autogen](https://github.com/sureshsolanki-labs/autogen) | `ai-research/autogen` | Multi-agent conversation framework. **⚠ CC-BY-4.0 (docs licence, not code)** — user override | **High** |
| Agentic AI / Adaptive Intelligence | [pydantic/pydantic-ai](https://github.com/sureshsolanki-labs/pydantic-ai) | `ai-research/pydantic-ai` | Type-safe agent framework — pydantic-native alternative to langgraph for schema-strict flows | **High** |
| Productivity & Tooling | [pydantic/pydantic](https://github.com/sureshsolanki-labs/pydantic) | `ai-research/pydantic` | Foundational Python typed-model/validation library; standard for schemas across our Python | **High** |
| Multimodal & Perception | [openai/whisper](https://github.com/sureshsolanki-labs/whisper) | `ai-research/whisper` | ASR (speech-to-text) for Akshaya Dhara rural voice-capture and verifier-call transcription | **High** |
| Database & Storage | [redis/redis](https://github.com/sureshsolanki-labs/redis) | `ai-research/redis` | In-memory KV/cache reference. **⚠ NOASSERTION (Redis 8+: RSALv2 + SSPLv1 + AGPLv3, non-permissive)** — user override; prefer `valkey-io/valkey` for production | **High** |

## Clone strategy

- **Full clone (9):** crewAI, langgraph, lerobot, codecarbon, multiscale-biomass-pyrolysis, LLMs-BiocharPredict, brightway2, ITR, graphcast — candidates for upstream contribution, deep adaptation, or methodology work
- **Shallow (`--depth=1`) clone (36):** everything else — read-only reference for now
- **Namespace split:** original 17 under `sureshsolannki-ai/` (personal); everything else (28) under `sureshsolanki-labs/` (org).
- **Domain consolidation (2026-07-04):**
  - Sustainability / Carbon + LCA & Materials + Climate & Geospatial AI → **Sustainability & Climate**
  - Vision Language Models + Audio & Speech (whisper) → **Multimodal & Perception**
  - AI Foundation + Deeptech / General AI infrastructure → **AI Foundation & Infra**
  - Final domain count: **8**.

## Boundaries (repo-wide)

- These are **research forks**. Nothing here has been validated for production dMRV use.
- Advisory tier unless upgraded via an approved methodology gate.
- No repo in this collection is authorised for the Aadhaar/registry/beneficiary/payout paths.
- Never treat model output as sensor-tier evidence (respect T3/T4/T5 discipline).
- `.env` is git-ignored per-repo; only `.env.template` at this root is tracked.

## Notable exclusions from the shortlist

- **microsoft/autogen** — GitHub reports license as CC-BY-4.0 (docs licence), failed the "permissive code licence" filter.
- **electricitymaps/electricitymaps-contrib** — AGPL-3.0, strong copyleft.
- **NVIDIA/TensorRT-LLM** — license NOASSERTION.
- **ros2/ros2**, **mujoco_menagerie**, **Erastova-group/Biochar_MolecularModels**, **SLU-biochar/biocharStability**, **chihebguesmi11/LLMAgentResearcher**, **uiedu/CharAI** — no licence or CC-BY-SA.
- **haotian-liu/LLaVA** — scored 22/25 but last pushed 2024-08; picked LLaVA-NeXT (fresher) instead.
- **transition-zero/tz-osemosys** — AGPL-3.0, strong copyleft.
- **os-climate/os-climate**, **climatebert/climatebert**, **climatiq/climatiq-python** — requested names do not exist on GitHub. os-climate substituted with `os-climate/ITR`; climatebert had no active permissively-licensed alternative and was dropped by decision; climatiq skipped.

## Biochar note

Biochar is a genuinely thin OSS domain: most active biochar repos on GitHub are academic drops with **no licence**, so are not safely forkable/adaptable. Only 2 permissively-licensed active repos cleared the >=18/25 threshold. This is honest, not a search failure.
