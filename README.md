# HotpotQA Alternate History Generator

A static documentation site that explains a system for generating alternate history narratives from HotpotQA dataset questions. The system uses the AFLOW algorithm to optimize LLM-based workflows that take multi-hop questions and produce plausible counterfactual scenarios.

## What This Repo Contains

This is not a runnable application. It is a single `index.html` page (served via GitHub Pages) that documents the architecture and approach of an alternate history generation system. The page includes Mermaid diagrams and an embedded audio narration.

| File | Purpose |
|------|---------|
| `index.html` | Static documentation page with architecture diagrams |
| `Aflow-HotpotQA Alternate History Generator.wav` | 26 MB audio narration |
| `.github/workflows/static.yml` | GitHub Pages deployment |
| `.github/workflows/self-improve.yml` | Claude Code automated improvement workflow |

## Architecture (as documented)

The described system has these components:

- **Data Loader** - reads questions from the HotpotQA dataset
- **Optimizer** - uses AFLOW to evolve prompt workflows
- **Workflow** - calls OpenAI API to generate alternate histories
- **Evaluator** - scores generated narratives

The actual implementation code is not in this repository. This is documentation only.

## Status

Experimental / documentation-only. The repo contains no runnable code -- just an HTML page describing the system design and a `.wav` audio file.

## License

No license specified.