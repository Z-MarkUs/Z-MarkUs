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

<a href="https://github.com/Z-MarkUs/OmniScrape">
  <img src="https://raw.githubusercontent.com/Z-MarkUs/OmniScrape/main/docs/assets/omniscrape-result.png" width="760" alt="OmniScrape deterministic extraction console with a typed result">
</a>

**Turn authorized web pages into validated article and product data—deterministically
by default.** OmniScrape combines structured data, readability parsing, and DOM
heuristics with opt-in Playwright rendering and OpenAI Responses modes. A shared
Pydantic-validated result contract is exposed through its Python library, CLI, FastAPI
JSON/SSE service, responsive web console, and MCP tool with enumerated inputs,
discriminated outputs, and safe operation annotations.

- Enforces optional exact hostname/host:port allowlists before DNS, across redirects,
  and throughout browser navigation.
- Ships **359 offline tests across its complete optional stack, including five in real
  Chromium**, **over 91% combined statement-and-branch coverage**, and CI on Python
  **3.10–3.13**, with CodeQL, dependency audits, and read-only container smoke tests.
- Scores all **76/76 present fields exact and complete**, plus **8/8 expected
  absences**, across 14 checked-in synthetic cases with zero errors. These results
  describe the bundled corpus, not the open web.
- Includes Codex and Claude Code skills plus an immutable, checksummed **v0.3.0**
  release backed by GitHub build provenance.

[Source and documentation](https://github.com/Z-MarkUs/OmniScrape)
· [v0.3.0 release](https://github.com/Z-MarkUs/OmniScrape/releases/tag/v0.3.0)
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
