---
type: canvas
plane: intents
level: 1
status: draft
exclude: []
tags:
  - inception
---

# Inception canvas

*The author's idea; everything named is an example. Based on the [arc42 Architecture Inception Canvas](https://canvas.arc42.org/architecture-inception-canvas) (CC BY-SA 4.0). Details: [[Method]], [[Review]], [[Glossary]], [[Roadmap]], [[Open questions]].*

## Business case

*LLM-built projects degrade into slop: knowledge lives in chats and per-feature plans, and humans can't keep up reading generated code. Instead, cheap models implement from a small, human-reviewed set of documents, and humans review documents, not code.*

## Functional overview

*Two planes of documents, an enforced glossary, curated one-page formats, thin plans checked by do and throw, and an Obsidian review folder where formatting records what a human has reviewed.*

## Quality goals

*Not ranked or measured yet (Q2): consistent documents across sessions and agents, implementable by a cheap model, cheap to review.*

## Business context

*The human writes and reviews the upper levels; a frontier model in any agent runs the workflow; a cheap model implements; Obsidian shows the repo's documents. Formats and tools are not chosen yet.*

## Constraints

*The author is not a specialist architect, so the method offers a curated choice from established sources. Human review time is scarce. Any coding agent, at least Claude Code and Codex; vanilla Obsidian, no custom CSS or plugins.*

## Architecture hypotheses

*Each needs checking before it becomes a decision. H1: two planes let a human review documents, not code. H2: an enforced glossary keeps specs consistent. H3: curated, extendable formats avoid overwhelming the user. H4: good specs allow thin plans. H5: do and throw finds spec gaps before review. H6: the spec step can be a modified superpowers-like workflow. H7: dependency tracking keeps the planes consistent. H8: review marks let agents regenerate safely. H9: code and configs in Markdown share one review convention.*

## Technical challenges and risks

*Specs may grow into code written in English; tests may pass without checking anything; agents may write generic text, drop review marks or behave differently across tools; documents may outgrow an agent's context; existing codebases need documents written after the fact.*
