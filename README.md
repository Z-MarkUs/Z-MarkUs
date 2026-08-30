<div align="center">

# Hehan Zhao

**Python · reliable AI systems · reproducible evaluation · agent tooling**

Toronto · University of Toronto

</div>

I build software where the evidence and safety boundaries are as inspectable as the
demo. My recent work focuses on typed Python systems, honest AI evaluation, and
human-in-the-loop automation.

## Selected work

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
