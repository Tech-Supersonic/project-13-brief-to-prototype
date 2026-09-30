# 4. What You Will Build

Before Engagement 1, open `examples/worked-example-loandesk/mockup.html` in a browser and click through it, then read its `compilation.md`. That is what "done" looks like.

## The Five Engagements

Each brief is deliberately short. Scoping it is part of the work.

| # | Engagement | The client wants | The worst failure |
|---|---|---|---|
| 1 | **LabLine** (Healthcare) | Lab results: test orders, reference-range flagging, a doctor release gate, consent capture, critical-value alerts | A result reaching a patient before a doctor has reviewed it |
| 2 | **ClauseTrack** (Legal) | Contracts: clause library, version history, approval chain, deadline tracking, an AI summary shown beside its source clause | Someone relying on a wrong AI summary |
| 3 | **ClaimGate** (Insurance) | Claims: intake, photo evidence, policy validation, fraud scoring that flags for a human, assessor assignment, settlement | A claim rejected with no human seeing it |
| 4 | **ColdChain** (Logistics) | Cold chain monitoring: shipments, a temperature feed you simulate, breach detection, custody handovers, a liability report | A breach nobody can trace back to its cause |
| 5 | **PayRun** (HR and Finance) | Payroll: salary structures, attendance import, tax, payslips, disbursement export, a month-end lock | Someone quietly editing a closed pay period |

## What Each Engagement Leaves Behind

| File | What it is |
|---|---|
| `context/scenario-N-name/spec.md` | The spec you gave your coding agent, written **before** it built anything |
| `docs/scenario-N-name/compilation.md` | The seven-section document (headings already in the file) |
| `src/scenario-N-name/mockup.html` | One self-contained file, opens from disk, clickable through the core flow |
| `proof/scenario-N-name/` | At least two screenshots of the core flow working |

The seven sections of `compilation.md`, in order:

1. **Feasibility Note:** real build and run costs, with reasoning
2. **SRS:** requirements, plus at least one domain rule you dug up yourself and checked
3. **System and Database Design:** schema and critical flow as diagrams
4. **Agent Direction Log:** what you asked for, what you corrected
5. **Test Sheet:** at least six checks, one regression case tied to a real defect
6. **Ship-Readiness Note:** what production would actually need
7. **Retrospective:** what went well, what you would change, how it compared with the last one

The worked example in `examples/worked-example-loandesk/` shows the depth expected. Copy its shape, not its wording.

## Your Two Days Per Engagement

Five engagements, two days each. By this point you have already learned the material (guide 1), set up your repository and read the standards (guide 2), and drafted your AI pipeline (guide 3).

| Day | Do this |
|---|---|
| Day 1 of the pair | **Requirements and design.** Find the unstated rule, check it, sketch the schema and flow by hand, write sections 1 to 3 |
| Day 2 of the pair | **Build and check.** Write `spec.md`, direct the agent, correct it, write section 4. Run the flow, take screenshots, write sections 5 to 7, commit |

So across the project: Engagement 1 on days 3 to 4, Engagement 2 on days 5 to 6, Engagement 3 on days 7 to 8, Engagement 4 on days 9 to 10, Engagement 5 on days 11 to 12. Feed anything the agent got wrong back into `CLAUDE.md` as you go, so the next engagement does not repeat it.

Out of scope on purpose: real servers, real integrations (simulate them), CI/CD, automated test suites, live hosting.
