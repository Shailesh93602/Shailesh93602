# Shailesh Chaudhari

Full-stack engineer at **ContextQA**, strongest on the backend. I build the core QA-automation
product's backend — test-execution engine, VNC streaming, multi-cloud browser orchestration
(Playwright / WebdriverIO / LambdaTest) — and I ship the UI too: both products I shipped there are
React / Next.js / TypeScript, one of them an accessibility auditor.

What I care about: idempotency, concurrency control, and testing that actually proves something.

**Portfolio:** [shaileshchaudhari.vercel.app](https://shaileshchaudhari.vercel.app) ·
**How I verify:** [/engineering](https://shaileshchaudhari.vercel.app/engineering) — real defects
from my own production code, each with *why the wrong version looked correct*.

## Selected work

| Project | What it is |
|---|---|
| [BALLAST](https://github.com/Shailesh93602/ballast) | Deterministic simulation of a multi-tenant session control plane — per-tenant concurrency caps, quota windows, leases over an unreliable substrate. One integer seed in, one byte-identical decision log out. Judged by 8 invariants, a reference oracle, and mutation testing; it found real bugs, about half of them in the checker rather than the implementation. Zero runtime dependencies. |
| [EduScale](https://github.com/Shailesh93602/DevScale) | Real-time coding battles where the two players' events may land on **different Node instances** — Socket.io Redis adapter, Redlock battle-start mutex, circuit breakers, Prometheus metrics. [Live](https://eduscale.vercel.app). |
| [KhataGO](https://khatago.vercel.app) | WhatsApp-first bookkeeping. Meta delivers webhooks at least once, so idempotency is enforced in Postgres — a unique message id plus an atomic PENDING→PROCESSING claim — with a containerized polling worker and a dead-letter queue with audited replay. |
| [promptproof](https://github.com/Shailesh93602/promptproof) | Zero-dependency LLM eval + regression-diff kit — define cases, grade outputs, save a baseline, fail CI on any pass→fail. |
| [idempotency-kit](https://github.com/Shailesh93602/idempotency-kit) | The Stripe `Idempotency-Key` pattern as a zero-dependency wrapper, including the fingerprint-mismatch guard, plus a sliding-window rate limiter. |
| [grounded](https://github.com/Shailesh93602/grounded) | Production-grade RAG starter: cited answers, idempotent ingestion, an "I don't know" guardrail, and an eval harness that runs offline. |

## Reach me

[LinkedIn](https://linkedin.com/in/shaileshbhai-chaudhari) ·
[work.shailesh.chaudhari@gmail.com](mailto:work.shailesh.chaudhari@gmail.com) ·
[LeetCode](https://leetcode.com/shaileshbhai)
