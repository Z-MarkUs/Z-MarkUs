<div align="center">

# Hehan Zhao

**Python · reliable AI systems · reproducible evaluation · agent tooling**

Toronto · University of Toronto

</div>

I build software where the evidence and safety boundaries are as inspectable as the
demo. My recent work focuses on typed Python systems, honest AI evaluation, and
human-in-the-loop automation.

## Selected work

### [OmniScrape](https://github.com/Z-MarkUs/OmniScrape)

**Turn authorized web pages into validated article and product data—deterministically
by default.** OmniScrape combines structured data, readability parsing, and DOM
heuristics with opt-in Playwright rendering and OpenAI Responses modes. A shared
Pydantic-validated result contract is exposed through its Python library, CLI, FastAPI
JSON/SSE service, responsive web console, and MCP tool.

- Defends outbound fetches against SSRF and DNS rebinding by pinning validated IPs,
  revalidating redirects, checking connected peers, and bounding time, bytes, requests,
  and concurrency.
- Ships **276 tests, including five real-Chromium policy tests**, **over 91% combined
  statement-and-branch coverage**, CI on Python **3.10, 3.12, and 3.13**, CodeQL,
  dependency audits, and a non-root container tested with a read-only filesystem.
- Includes synchronized project skills for Codex and Claude Code plus an immutable,
  checksummed GitHub release backed by signed build-provenance attestations.

[Source and documentation](https://github.com/Z-MarkUs/OmniScrape)
· [Latest release](https://github.com/Z-MarkUs/OmniScrape/releases/latest)
· [CI](https://github.com/Z-MarkUs/OmniScrape/actions/workflows/ci.yml)

### [Prompt Refinement, Tested](https://github.com/Z-MarkUs/Prompt-Refinement-for-AI-Coding-Assistance)

<a href="https://z-markus.github.io/Prompt-Refinement-for-AI-Coding-Assistance/">
  <img src="https://raw.githubusercontent.com/Z-MarkUs/Prompt-Refinement-for-AI-Coding-Assistance/main/site/social-card.png" width="760" alt="Prompt Refinement, Tested case study">
</a>

A reproducible re-analysis of a historical LLM coding experiment—and an example of
reporting a negative result clearly instead of forcing a success story.

- Reconciles **592 judge records across 200 coding tasks** and compares workflows on
  exact task-ID intersections.
- Reports missingness, paired effect sizes, exact McNemar tests, task-identity
  sensitivity, and training-overlap risk.
- Ships as a typed Python package and CLI with **100 offline tests**, **89.68% coverage**,
  multi-version CI, deterministic evidence artifacts, and repository skills for Codex
  and Claude Code.

[Live case study](https://z-markus.github.io/Prompt-Refinement-for-AI-Coding-Assistance/)
· [Generated evidence](https://github.com/Z-MarkUs/Prompt-Refinement-for-AI-Coding-Assistance/blob/main/docs/results.md)
· [Source](https://github.com/Z-MarkUs/Prompt-Refinement-for-AI-Coding-Assistance)

### [WatchDock](https://github.com/Z-MarkUs/WatchDock)

**Give agents a review queue—not unchecked file moves.** WatchDock is a cross-platform,
review-first file organizer with a desktop app, CLI, and constrained local MCP gateway.
It freezes proposals and source fingerprints in SQLite, keeps approval separate from
agent analysis, and revalidates destinations before applying a move.

[Source and documentation](https://github.com/Z-MarkUs/WatchDock)
· [PyPI](https://pypi.org/project/watchdock/)

## What I care about

- AI evaluations that preserve provenance, missingness, and inconvenient outcomes.
- Python systems with types, tests, clear interfaces, and reproducible builds.
- Automation that makes trust boundaries and human decisions explicit.
