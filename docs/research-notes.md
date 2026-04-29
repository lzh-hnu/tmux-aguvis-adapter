# tmux for Aguvis: Visual-Terminal Grounding Adapter

## Purpose

This document records the research framing behind the static GitHub Pages site. The project studies how tmux can be adapted for Aguvis as a durable terminal substrate for agentic work.

## Research Question

How can Aguvis align visual observations with terminal semantics when panes, scrollback, and command phases change over time?

## Working Thesis

The adapter pairs visual pane localization with symbolic terminal events, giving Aguvis a richer account of what changed and why.

## Design Claims

- Visual pane regions are linked to shell-level event streams.
- Scrollback and active output are modeled separately.
- Session replay preserves both visual snapshots and terminal text.

## Evaluation Lens

- Visual pane localization
- State alignment across scrollback changes
- Trace usefulness for multimodal diagnosis


## Threats to Validity

- Terminal state can be over-instrumented, causing an adapter to measure artifacts of the harness rather than real agent behavior.
- A final successful artifact may hide poor recovery behavior, repeated command attempts, or fragile focus management.
- Agent-specific adapters can become difficult to compare unless trace schemas remain explicit and documented.

## Hero Image Source

The GitHub Pages hero image uses a 700x500 version of the shared tmux CUA screenshot, copied into `docs/assets/hero.png` and displayed below the page title at its native size.
