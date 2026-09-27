---
type: questions
plane: intents
level: 1
status: draft
exclude: []
tags:
  - inception
---

# Open questions

*Decided questions leave this page; IDs stay stable. Q4 (the exclusion field) and Q10 (Obsidian) are decided, see [[Review]].*

| ID | Question | Options so far |
| --- | --- | --- |
| Q1 | *Names for planes and levels?* | *Baseline / Delta, As-is / Change, Record / Intent. Avoid state, model, spec.* |
| Q2 | *How to measure stability and review coverage?* | *Share of italic text; code churn not traced to specs; mutation score.* |
| Q3 | *Is a separate review tool needed?* | *Marks plus a script; a ledger based on git blame; Reviewable.* |
| Q5 | *Which level 2 tools?* | *Examples on [[Review]]; nothing chosen.* |
| Q6 | *superpowers: fork or only inspiration?* | *Fork; standalone skills.* |
| Q7 | *Existing codebases in the first version?* | *New projects first.* |
| Q8 | *Solo or with collaborators; a date?* | *Not discussed yet.* |
| Q9 | *Gherkin for natural-language tests?* | *Gherkin; other forms to explore.* |
| Q11 | *Which discussion ideas to adopt?* | *Normative vs generated near-code docs; fix specs first; checks in CI; links only from intents to specs; a gap log; forbidden synonyms in the glossary.* |
| Q12 | *When and how to track dependencies?* | *OpenFastTrace; Obsidian links; later.* |
| Q13 | *What is the skill called?* | *see-no-evil (author's proposal), maybe with speak-no-evil and hear-no-evil; see-no-monkey; mizaru.* |
| Q14 | *What does bold mean?* | *Emphasis for agents too, if they can tell edits from comments; or a human's inline comment that must not survive the next iteration.* |
| Q15 | *Underline or highlight for "important"?* | *HTML `<u>`; native `==highlight==`.* |
| Q16 | *Code and configs as plain Markdown?* | *Plain Markdown, same marks everywhere; code blocks, no inline marks.* |
| Q17 | *Do headings and diagrams carry a status?* | *No, they are structure; a status per block.* |
| Q18 | *How are marks protected from agents?* | *Only a human removes italics, checked per commit; no check.* |
