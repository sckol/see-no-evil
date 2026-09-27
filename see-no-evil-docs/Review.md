---
type: idea
plane: intents
level: 1
hypotheses: [H8, H9]
status: draft
exclude: []
tags:
  - inception
---

# Review

How a human reviews without reading code; hypotheses H8 and H9 on the [[Inception canvas]].

## Review vault

All documents for review live in one folder of vanilla Obsidian Markdown, including code and configs turned into Markdown, which gives formatting, links, properties, tags and splitting. Comparing a page with its previous version shows the agent what the human changed.

## Review marks

| Mark                      | Meaning                                           |
| ------------------------- | ------------------------------------------------- |
| `*text*`, italic          | Generated, not reviewed.                          |
| `text`, plain             | Reviewed.                                         |
| `~~text~~`, strikethrough | Want not to review, leave it to implementers.     |
| `<u>text</u>`, underline  | Important; keep close to as is when regenerating. |
| `**text**`, bold          | Not decided yet (Q14).                            |

*The human strikes text; the agent moves it into the page's `exclude` property and deletes it. Open: Q14, Q15, Q17, Q18. In this folder for now, headings, table headers, properties and diagrams have no status, and phrases the author typed are plain.*

## Level 2 projections

*A script turns configs, code and projections into Markdown, with its settings in the page's properties, so the page can be regenerated and compared with previous versions. Plain Markdown instead of code blocks is less pretty, but the same marks work everywhere (Q16).*

*Tool examples from the discussion, not a decision (Q5, Q9):*

| Near-code doc | Examples |
| --- | --- |
| *Natural-language tests* | *Gherkin with pytest-bdd or behave; Playwright* |
| *Interfaces* | *`__all__`, Protocols, type hints; mypy or pyright; strict tsc* |
| *API surface* | *griffe, Storybook, OpenAPI with openapi-typescript* |
| *Structure and dependencies* | *import-linter, dependency-cruiser, deptry* |
| *Config and conventions* | *pydantic-settings, ruff, ESLint or Biome* |
