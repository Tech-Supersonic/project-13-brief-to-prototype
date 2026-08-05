# Project 13: The Consultancy

| Field | Detail |
|---|---|
| Project Number | 13 |
| Project Name | The Consultancy |
| Tier | Mid |
| Deadline | 10 working days (2 weeks) |
| Tags | Requirements, Feasibility, SRS, System Design, AI-Built Prototypes, Client Presentation, Portfolio |

---

## Overview

You're going to run seven short client engagements, one after another, each in a different industry. A client comes to you with a real problem. You scope it, decide if it's actually worth building, design the system and database behind it, get an AI coding agent to build you a working prototype, test it, work out what it would take to really ship it, and present the whole thing back as if you're talking to the client who asked for it.

Before you touch Engagement 1, open `examples/worked-example-loandesk/`. It's one engagement done start to finish: a written document and a working mockup you can click through right now. That's your target. Copy its shape and depth, not its wording.

Everything you build here is a prototype, not a finished product. Every screen genuinely works when clicked, but there's no real server, database, hosting, or test suite behind it. You build each one as a single self-contained HTML file, with an AI coding agent doing the typing while you direct it. That's not a shortcut, it's the point of this project: your time goes into requirements, design, and presenting your work well, not into infrastructure.

Each engagement leaves behind exactly two files, a document and a mockup. Nothing else.

More than anything, this project is about explaining your own work clearly and confidently to someone non-technical, while they push back and ask questions. You do that seven times on purpose, because it's the skill most people get the least real practice at.

By the end you'll have seven small, documented prototypes in your own public GitHub, a portfolio page, and material for your resume.

---

## What This Trains

| Category | Skills |
|---|---|
| SDLC and Engineering Practices | Development lifecycle, testing discipline |
| Programming and Stack Fundamentals | API construction, database design |
| AI-Driven Development and Automation | Coding agents, multi-tool fluency |
| System Design and Architecture | Architecture tradeoffs, cost-aware design |
| Independent Operation and Delivery | Scoping, requirements, self-management |
| Career Assets and Hireability | Business and ROI fluency, portfolio, resume and LinkedIn readiness |

Trained harder here than anywhere else in the library: judging feasibility fast with no template to work from, surfacing the domain rules a client never states out loud, directing an AI agent as your builder instead of taking its first draft, and explaining the same piece of work to seven different audiences while they question you live.

---

## Before You Start

You should have already finished Project 1 or something equivalent, and be comfortable building a REST API and database from a written spec, directing a coding agent from a plan you wrote yourself, and asking clarifying questions before you start building.

Two skills live in `skills/` and are already set up for you: `teach-me` (say "teach me" plus a topic, log your confidence in `LEARNING_LOG.md`) and `troubleshoot` (describe what broke). On this project, your AI Instructor also plays a third role, a stand-in domain expert. Before writing requirements for an industry you don't know, ask it to walk you through the basics first, then verify what it tells you rather than taking it on faith.

Build each mockup as one self-contained HTML file: inline CSS and JavaScript, fixture data standing in for a database, built by directing an AI coding agent. Draw your diagrams as Mermaid code blocks inside `compilation.md` itself, so they render inline the moment someone opens it on GitHub, no separate tool needed. A frontend framework is fine too, as long as what you end up with still opens with no server and no build step.

Sketch the schema and the critical flow yourself, on paper or out loud with your AI Instructor, before you generate anything. What matters is that you can explain every decision afterward, in your own words, on all seven engagements.

---

## The Seven Engagements

Look at `examples/worked-example-loandesk/` again if you need a reminder of what "complete" looks like.

1. **LoanDesk (Financial).** A loan origination system: intake, a document checklist, an affordability rule you have to surface yourself, a two-step approval where different people recommend and approve, an amortization schedule, an audit trail.
2. **LabLine (Healthcare).** A lab results system: orders, reference-range flagging, a doctor release gate before a patient sees anything, consent capture, critical-value alerts. The worst failure here is a result reaching a patient before a doctor has reviewed it.
3. **ClauseTrack (Legal).** A contracts system: a clause library, version history, an approval chain, deadline tracking, and an AI summary that always sits beside its source clause, never presented as the final word on its own.
4. **ClaimGate (Insurance).** A claims system: incident intake, photo evidence, policy validation, fraud scoring that flags a claim for a human to look at, never auto-rejects it, assessor assignment, settlement calculation.
5. **ColdChain (Logistics).** A cold chain monitor: shipment registration, a temperature feed you simulate yourself, breach detection, a custody handover chain, and a liability report a court could actually follow.
6. **GrantBoard (Education).** A scholarship system: application windows, document verification, a weighted scoring rubric, recusal for committee members with a conflict of interest, award letters and appeals.
7. **PayRun (HR and Finance).** A payroll system: salary structures, attendance import, tax calculation, payslips, a disbursement export, and a month-end lock that cannot be bypassed. The worst failure here is someone quietly editing a period that's already closed.

---

## What Each Engagement Leaves Behind

One document, `compilation.md`, written in this order: a feasibility note with a real build and run cost, an SRS that includes at least one domain rule you had to dig up yourself, a system and database design with the schema and critical flow drawn as Mermaid diagrams, an agent direction log of what you asked for and what you had to fix, a test sheet, a one-paragraph ship-readiness note on what production would actually need, and a short retrospective.

One mockup file, self-contained, opening with nothing but a browser, genuinely clickable through its core flow.

The bar for both: real numbers, not placeholders. Diagrams live inside the document itself. Nothing needs a server, an account, or a build step to run. Every engagement should be presentable, cold, in under five minutes.

Out of scope on purpose: production hardening, real external integrations (simulate them instead), a real CI/CD pipeline or automated test suite (the ship-readiness note stands in for this), live hosting, and one shared codebase across all seven.

---

## How the Two Weeks Break Down

Roughly one working day per engagement, seven times, then one closing phase.

| Phase | What you're doing | What it produces |
|---|---|---|
| 1. Requirements and Planning | Surface the domain rules nobody stated, with help from your AI Instructor, then verify them yourself. Sketch the schema and critical flow by hand. | Feasibility, SRS, and design sections of `compilation.md` |
| 2. Prototype Build | Write a spec, direct your coding agent, correct what it gets wrong. | The mockup, plus the agent direction log |
| 3. Check and Present | Run it end to end, write the test sheet, the ship-readiness note, and the retrospective. Present live if this engagement was mentor-selected. | A finished `compilation.md` |
| 4. Portfolio Packaging, once, after all seven | Write your cross-engagement reflection. Make every folder public and clean. Add your strongest three to five to your Project 0 portfolio site. Write resume and LinkedIn material. | `docs/reflection.md`, an updated portfolio, resume material |

---

## Where Things Go

| Artifact | Location |
|---|---|
| Compiled document | `docs/scenario-N-name/compilation.md` |
| Standalone mockup | `src/scenario-N-name/` |
| Worked reference example | `examples/worked-example-loandesk/` |
| Cross-engagement reflection | `docs/reflection.md` |
| Learning log | `LEARNING_LOG.md` |
| Submission, portfolio, resume material | `PRESENTATION.md` |
| Screenshots and proof | `proof/scenario-N-name/` |

Scenario names: `scenario-1-loandesk`, `scenario-2-labline`, `scenario-3-clausetrack`, `scenario-4-claimgate`, `scenario-5-coldchain`, `scenario-6-grantboard`, `scenario-7-payrun`. There's no `Dockerfile`, `tests/`, or `.github/workflows/` here. Containers, an automated test suite, and CI aren't part of this project.

---

## Getting Started

Fork the repo, then open and click through `examples/worked-example-loandesk/mockup.html`, and read its `compilation.md`. Start Engagement 1 with Phase 1, before writing any code. Work through Phases 2 and 3, then move to the next engagement, and repeat for all seven. Commit as you finish each one, save your proof, and keep `LEARNING_LOG.md` current. After Engagement 7, run Phase 4, then fill in `PRESENTATION.md`. Add your mentor as a collaborator, schedule a call, and present.

---

## Definition of Done

- [ ] All seven engagements through Phases 1 to 3, each `compilation.md` complete with its Mermaid diagrams rendering
- [ ] A genuinely clickable, standalone mockup for each engagement
- [ ] Cross-engagement reflection, portfolio site, and resume and LinkedIn material done
- [ ] `LEARNING_LOG.md` and `PRESENTATION.md` complete
- [ ] A Loom video for each mentor-selected engagement
- [ ] Mentor added as collaborator, live call scheduled and completed

---

## Review and Presentation

**Written.** `PRESENTATION.md` gets the repo link, the mockup path, and a short note per engagement, plus your portfolio and resume material.

**Video.** A Loom walkthrough for the two engagements your mentor selects.

**Live.** Your mentor picks two of the seven at random. Present problem, solution, and implementation in under five minutes each, then answer client-style questions without notes.

---

## Bonus Practice

If communication has come up as something to work on, spend ten minutes a day talking through your work with an AI voice mode, either ChatGPT's Voice Mode or Gemini Live. Give it this prompt: *"You are my speaking coach. Each day I'll tell you which engagement I worked on, what I accomplished, and today's goal. Listen for about ten minutes, then give me clear feedback on my clarity, pace, and confidence, plus one specific thing to improve tomorrow."*

You can also just record yourself presenting one engagement, watch it back, then do it again after engagement 3 or 4 and compare the two.

---

## Interview Gap-Check Questions

1. Walk through your build and run cost estimate for any engagement. What does it depend on, and how does it change at ten times the usage?
2. LoanDesk: what happens the moment an application fails the affordability rule?
3. LabLine: what specifically stops a result reaching a patient before a doctor has reviewed it?
4. ClauseTrack: what stops your AI summary from becoming the thing someone relies on, if it's wrong?
5. ClaimGate: could a claim ever be auto-rejected with no human seeing it?
6. ColdChain: how does your simulator decide to report a breach, and how does the liability report trace back to it?
7. GrantBoard: how does your recusal mechanism actually stop a conflicted committee member from scoring an application?
8. PayRun: what happens if someone tries to edit a pay period that's already closed?
9. Pick an engagement where you corrected your AI coding agent. What was wrong, and what changed in your next spec?
10. Pick any engagement: what would need to change before it could handle real users and real money or medical data?
11. Which domain took the longest to scope correctly, and why?
12. Given a two-sentence client problem, what's the first thing you do before writing any requirement?
13. Show me your portfolio page, as if I'm a client deciding whether to hire you, in under two minutes.
14. Open any `compilation.md` cold. Find the ship-readiness note in ten seconds. What made that possible?

If you can't answer these comfortably, or can't clear a mentor-selected live presentation, you'll get a decimal variant: same structure, seven fresh domains, built again until the gap closes.
