# AI Framework Map

A categorized, maintained map of the frameworks people actually use to build with AI — agents, orchestration, RAG, serving, fine-tuning, and evaluation. Pick a category, see what's real, and know what each one is for.

---

## What this is

The AI framework space moves fast and the names blur together. This repo is a **map**: every major framework, sorted by what it does, with a one-line description of who it's for and what stage it's at.

It is not a tutorial and not a benchmark. It is the overview you read **before** you pick a framework, and the reference you come back to when the landscape shifts.

---

## Why it exists

- Search results for "best AI framework" are dominated by SEO listicles that are outdated within weeks.
- Framework categories overlap (is this an agent framework or an orchestration framework?), so people compare things that aren't comparable.
- New frameworks appear monthly, and there's no single place that tracks **what's actively maintained, what's a wrapper, and what's abandoned**.

This map keeps those answers in one place, with a clear category structure and a maintenance date on every entry.

---

## The map

| Category | What it covers | Open |
|---|---|---|
| Agents | Frameworks for building autonomous or semi-autonomous agents | [`agents/`](./agents/README.md) |
| Orchestration | Multi-step pipelines, chains, workflow engines | [`orchestration/`](./orchestration/README.md) |
| RAG & retrieval | Retrieval, vector stores, document pipelines | [`rag/`](./rag/README.md) |
| Serving & inference | Model serving, gateways, local inference | [`serving/`](./serving/README.md) |
| Fine-tuning | Training, adapters, dataset tooling | [`fine-tuning/](./fine-tuning/README.md) |
| Evaluation | Evals, benchmarks, observability for LLM apps | [`evaluation/`](./evaluation/README.md) |

Each category page lists frameworks in a fixed format: **name · one-line purpose · language · license · last release · maintenance status**. No rankings, no hype — just the facts you need to shortlist.

---

## How to use it

1. Open the category closest to what you're building.
2. Shortlist two or three frameworks from the table.
3. Check the "last release" and "status" columns before you commit — that's where most surprises hide.

---

## Who it's for

- Engineers picking a framework for a new project
- Teams evaluating whether to switch or consolidate
- Anyone tired of comparing frameworks that solve different problems

---

## Contributing

Additions and corrections are welcome. Every entry must follow the format in [`CONTRIBUTING.md`](./CONTRIBUTING.md) and include a source for the maintenance status. Frameworks that are abandoned or unmaintained are moved to `archived/`, not deleted — the map should show what's gone, too.

## License

[MIT](./LICENSE)
