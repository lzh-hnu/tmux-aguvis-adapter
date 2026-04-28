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

## Hero Image Prompt Summary

A 700x500 academic technical illustration for tmux adaptation research with Aguvis, emphasizing terminal panes, agent traces, reproducible evaluation, and a serious research discussion style. The generated image was copied into `docs/assets/hero.png` and normalized to 700x500 pixels.
