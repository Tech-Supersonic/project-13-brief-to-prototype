# Project 13: The Consultancy

| Field | Detail |
|---|---|
| Project Number | 13 |
| Project Name | The Consultancy |
| Tier | Mid |
| Deadline | 10 working days (2 weeks) from your start date |
| Status | Active |
| Tags | Requirements Analysis, Feasibility, SRS, System and Database Design, AI-Built Prototypes, Client Presentation, Interview Readiness, Portfolio Packaging |

---

## Overview

You are running seven short client engagements, one per industry, one after another. Each one is a real business problem. For each, you: scope it, judge if it's worth building, design the system and database, direct an AI coding agent to build a working prototype, check it, decide how it would actually ship, and present it back as if to the client.

**Before you start, open `examples/worked-example-loandesk/`.** It's a complete, finished engagement: one document (`compilation.md`) and one working mockup (`mockup.html`) you can open right now. This is what "done" looks like. Match its shape and depth for your own seven; don't copy its wording.

**What you build is a prototype, not a production app.** Every screen genuinely works when clicked, but there's no real server, no database, no hosting, no automated test suite. Build it with an AI coding agent (Claude Code or similar) as a single standalone HTML file that opens in any browser, exactly like the worked example. This isn't a shortcut. It's the point: your time goes into requirements, design, and presentation, not infrastructure.

**Every engagement produces exactly two files:** `compilation.md` (one document, feasibility through retrospective, diagrams included as Mermaid so they render inline) and one mockup file. Nothing else. This is deliberately simpler than earlier drafts of this brief, so a reviewer never has more than two files to open per engagement.

This project trains one thing above all else: presenting your work, clearly and confidently, to someone who isn't technical, under real questioning. That's trained seven times here on purpose, because it's the skill most resources get the least practice on, and it doesn't improve without repetition.

By the end: seven documented prototypes in your own public GitHub repo, a portfolio page, and resume material.

---

## Covered Areas

| Category | Area |
|---|---|
| SDLC and Engineering Practices | Development Lifecycle, Testing Discipline |
| Programming and Stack Fundamentals | API Construction, Database Design |
| AI-Driven Development and Automation | Coding Agents, Multi-Tool Fluency |
| System Design and Architecture | Architecture and Tradeoffs, Cost-Aware Design |
| Independent Operation and Delivery | Scoping and Requirements, Self-Management |
| Career Assets and Hireability | Business and ROI Fluency, Portfolio Projects, Resume/LinkedIn/Upwork Readiness |

Communication and Client Readiness rides on every engagement's presentation, trained more heavily here than in any other project in this library.

---

## What This Trains

**Process, structure, and judgment**
- Judging feasibility and pricing build and run cost, fast, for a problem with no template
- Turning a short client ask into a proper SRS, surfacing rules the client never states
- Designing a system and a database that fit the actual domain, not a copy of a previous engagement with renamed tables
- Directing an AI coding agent as the builder: writing a spec it can work from, catching what it gets wrong, not accepting its first output

**Presentation and communication**
- Explaining problem, solution, and implementation clearly to a non-technical audience, seven times, sharper each time
- Answering client-style questions live, with no script
- Packaging finished work so a stranger, a client, or an interviewer understands it immediately

---

## Prerequisites

You should already have completed Project 1 (or equivalent) and be comfortable with:
- Building a REST API and a relational database from a written spec
- Directing an AI coding agent (such as Claude Code) to implement a feature from a plan you wrote
- Reading an unfamiliar problem statement and asking clarifying questions before building

### Your AI Instructor, troubleshooting partner, and domain expert

The same two skills from earlier projects are in `skills/`. Add both to your Claude project before you start.

- **Learning agent** (`skills/teach-me/SKILL.md`). Say "teach me" plus a topic. Log your confidence score in `LEARNING_LOG.md`.
- **Troubleshooting agent** (`skills/troubleshoot/SKILL.md`). Describe what broke, get guided to the cause.

For this project, your AI Instructor also plays a third role: a stand-in domain expert. Before writing requirements for an industry you don't know, ask it to explain the domain's basic rules first. Verify what it tells you rather than copying it blindly, the same way you'd verify a client's first explanation of their own business.

---

## Tools, Stack, and Diagrams

- **The mockup:** a single self-contained HTML file, inline CSS and JavaScript, fixture data standing in for a real database. Built by directing an AI coding agent such as Claude Code, exactly as shown in `examples/worked-example-loandesk/mockup.html`. It must open with nothing more than a browser: no server, no build step, no account.
- **Diagrams:** written in Mermaid, as code blocks inside `compilation.md` itself. GitHub renders these automatically, so a diagram shows up the moment someone opens the document, with no separate tool involved. See the worked example for what this looks like in practice.
- **If you strongly prefer a frontend framework** over plain HTML, that's fine, as long as the result still opens with no server and no build step.

### Work manually first, then let AI accelerate the rest

For every engagement, sketch the entities, schema, and critical flow yourself, or talk it through with your AI Instructor, before generating anything or handing a spec to your coding agent. What matters is that you can explain every decision afterward, in your own words, on all seven engagements.

---

## The Exact Brief

Run seven client engagements. Each one: scope it, design it, build a prototype with an AI coding agent, check it, write the ship-readiness note, present it. A closing phase turns all seven into a portfolio.

**Reference `examples/worked-example-loandesk/` for what a complete engagement looks like before you start Engagement 1.**

### The Seven Engagements

**1. LoanDesk (Financial Services).** A microfinance lender wants to stop originating loans over email and spreadsheets. Build: application intake, a document checklist, an affordability rule (you must surface this yourself, see the worked example), a two-step approval (reviewer recommends, a different person approves), an amortization schedule, an audit trail.

**2. LabLine (Healthcare).** A diagnostic lab wants to stop delivering results by phone and PDF email. Build: test orders linked to a patient, reference-range flagging, a doctor review and release gate before a patient sees anything, consent capture, a critical-value alert. Get the release gate right: a result reaching a patient before doctor review is the worst failure mode here.

**3. ClauseTrack (Legal).** A legal team wants to stop tracking contracts in a shared folder of Word documents. Build: a clause library, contract version history, an approval chain, renewal and obligation deadline tracking, an AI summary feature that always shows alongside its source clause, never presented as authoritative alone.

**4. ClaimGate (Insurance).** A motor insurer wants faster first notice of loss without auto-approving anything. Build: incident intake, photo evidence, policy validation, fraud red-flag scoring that surfaces suspicious claims for a human (never an auto-rejection), assessor assignment, settlement calculation.

**5. ColdChain (Logistics).** A pharma distributor needs proof its shipments stayed in range. Build: shipment registration, a simulated temperature feed you build yourself (normal or drifting on command), breach detection, a custody handover chain, a liability report a court could actually follow.

**6. GrantBoard (Education).** A scholarship foundation wants off a shared inbox. Build: application windows, document verification, a weighted scoring rubric, a recusal mechanism for connected committee members, award letters and appeals.

**7. PayRun (HR and Finance).** A small company wants off spreadsheet payroll. Build: salary structures, attendance import, tax calculation, payslips, a disbursement export, a month-end lock that cannot be bypassed. The worst failure mode: someone quietly editing a closed pay period.

### The Deliverable Set, Every Engagement

Exactly two files, every time:

**`compilation.md`**, one markdown file, these sections in order:
1. **Feasibility note** — build cost and run cost, with reasoning, not a placeholder number
2. **SRS** — functional requirements, including at least one domain rule you had to surface yourself
3. **System and database design** — components, schema, tradeoffs, with the schema and the critical flow as Mermaid diagrams in this section
4. **Agent direction log** — what you asked your coding agent to build, what it got right, what you corrected
5. **Test sheet** — what you checked, the result, any defect found
6. **Ship-readiness note** — one paragraph on what production would actually need
7. **Retrospective** — what went well, what you'd change, how this compared to the last engagement

**One mockup file**, self-contained, opens with nothing but a browser, every screen genuinely clickable.

### Quality Bar

- The feasibility number must be real and reasoned, not a placeholder
- At least one SRS requirement must be a domain rule you surfaced, not one stated outright above
- Diagrams live inside `compilation.md` as Mermaid, not a separate file
- The mockup must be genuinely clickable through its core flow, with no server, account, or build step
- Every engagement must be presentable, cold, in under five minutes

---

## Requirements and Scope

**In scope:** all seven engagements, one `compilation.md` and one mockup each, a final cross-engagement reflection, seven presentations (two live and mentor-selected, five written), a final portfolio packaging phase.

**Out of scope:** production hardening or compliance certification (the domain rules like consent gates and audit trails are required as features; a full audit is not), real external integrations (simulate them), real CI/CD or an automated regression suite (the ship-readiness note replaces this), live hosting of any mockup, one shared codebase across engagements.

**Definition of done, in plain language:** for each engagement, a stranger can open `compilation.md` and understand what was built and why, open the mockup file and see it genuinely work, and hear you present it without notes. By the end, all seven live in your public GitHub with a portfolio page and resume material.

---

## Project Phases

Each engagement runs the same three phases, roughly one working day, seven times, then one shared closing phase.

**Phase 1, Requirements and Planning.** Identify unstated domain rules using your AI Instructor as a stand-in expert, then verify what it tells you. Write the feasibility and SRS sections. Sketch the schema and critical flow by hand, then write the design section with both as Mermaid diagrams.

**Phase 2, Prototype Build.** Write a spec, direct your coding agent, correct what it gets wrong, note the corrections. Confirm the mockup opens with nothing but a browser.

**Phase 3, Check and Present.** Run the mockup end to end, write the test sheet, the ship-readiness note, and the retrospective. Present live if this is a mentor-selected engagement.

**Phase 4, Portfolio Packaging (once, after all seven).** Write the cross-engagement reflection. Confirm every folder is public and every `compilation.md` renders cleanly with diagrams visible. Add your strongest three to five engagements to your Project 0 portfolio site. Write resume bullets and a LinkedIn entry.

---

## Artifact and Folder Guide

| Artifact | Location |
|---|---|
| Compiled document (all seven sections) | `docs/scenario-N-name/compilation.md` |
| Standalone mockup | `src/scenario-N-name/` |
| Worked reference example | `examples/worked-example-loandesk/` |
| Cross-engagement reflection | `docs/reflection.md` |
| Learning log | `LEARNING_LOG.md` |
| Submission, portfolio, and resume material | `PRESENTATION.md` |
| Screenshots and other evidence | `proof/scenario-N-name/` |

Scenario names, in order: `scenario-1-loandesk`, `scenario-2-labline`, `scenario-3-clausetrack`, `scenario-4-claimgate`, `scenario-5-coldchain`, `scenario-6-grantboard`, `scenario-7-payrun`.

---

## How This Works

- Fork the repository. Open `examples/worked-example-loandesk/` before touching Engagement 1.
- Work through the seven engagements in order. Commit as you finish each one, proof into that engagement's `proof/` folder.
- Keep `LEARNING_LOG.md` updated as you go.
- After all seven, run Phase 4 (Portfolio Packaging), then fill in `PRESENTATION.md`.
- Add your mentor as a collaborator. Schedule a call and present.

## Repository Structure

```
project-13-the-consultancy/
  README.md              This brief.
  PRESENTATION.md         Your submission.
  LEARNING_LOG.md         One entry per skill.
  examples/
    worked-example-loandesk/
      compilation.md        A complete, finished reference document.
      mockup.html            The matching working prototype. Open it directly.
  skills/
    teach-me/SKILL.md
    troubleshoot/SKILL.md
  proof/
    scenario-1-loandesk/ ... scenario-7-payrun/
  docs/
    project-brief.md        Internal, mentor-facing.
    reflection.md            Your cross-engagement reflection, written last.
    scenario-1-loandesk/compilation.md
    scenario-2-labline/compilation.md
    scenario-3-clausetrack/compilation.md
    scenario-4-claimgate/compilation.md
    scenario-5-coldchain/compilation.md
    scenario-6-grantboard/compilation.md
    scenario-7-payrun/compilation.md
  src/
    scenario-1-loandesk/ ... scenario-7-payrun/    Your mockups. Open directly in a browser.
  .gitignore
  LICENSE
```

No `Dockerfile`, `tests/`, or `.github/workflows/`: containerization, an automated test suite, and CI are out of scope here.

## How to Start Building

1. Fork the repository. Open and click through `examples/worked-example-loandesk/mockup.html`, then read its `compilation.md`.
2. Start Engagement 1 (LoanDesk). Complete Phase 1 before touching implementation.
3. Work Phases 2 and 3, then move to Engagement 2. Repeat for all seven.
4. Keep each engagement inside its own scenario folder.
5. After Engagement 7, run Phase 4 (Portfolio Packaging).

---

## Definition of Done

- [ ] All seven engagements completed through Phases 1 to 3
- [ ] `compilation.md` complete for each engagement, all seven sections, diagrams rendering as Mermaid
- [ ] A genuinely clickable, standalone mockup for each engagement
- [ ] Cross-engagement reflection completed
- [ ] All seven folders public and understandable cold, with no extra instructions needed
- [ ] Portfolio site updated, resume and LinkedIn material written
- [ ] `LEARNING_LOG.md` complete, `PRESENTATION.md` complete
- [ ] Loom video or live walkthrough for each mentor-selected engagement
- [ ] Mentor added as collaborator, live call scheduled and completed

---

## Review and Presentation

1. **Written.** `PRESENTATION.md`: repository link, mockup path, and a short note per engagement, plus portfolio and resume material.
2. **Video.** A Loom walkthrough for at least the two mentor-selected engagements.
3. **Live.** Your mentor picks two of the seven at random. Present problem, solution, implementation in under five minutes each, then answer client-style questions without notes. You won't know which two in advance.

---

## Bonus Practice Activities

**Daily speaking practice with Gemini Live**, if communication has been flagged. Ten minutes a day:

> You are my speaking coach. Each day I will tell you which engagement I worked on, what I accomplished, and what my goal for today is on The Consultancy project. Listen to me speak for about ten minutes, then give me clear, honest feedback on my clarity, pace, and confidence, and one specific thing to improve tomorrow.

**Self-recorded review.** Record yourself presenting one engagement. Watch it back before your live call. Do it again after engagement 3 or 4 and compare.

---

## Interview Gap-Check Questions

1. Pick any engagement. Walk through your build and run cost estimate. What assumptions does it depend on, and how does it change at ten times the usage?
2. LoanDesk: what happens the moment an application fails the affordability rule?
3. LabLine: what specifically stops a result reaching a patient before doctor review?
4. ClauseTrack: what happens if your AI summary is wrong? What stops it becoming the thing someone relies on?
5. ClaimGate: could a claim ever be auto-rejected with no human seeing it? What prevents that?
6. ColdChain: how does your simulator decide to report a breach, and how does the liability report trace back to it?
7. GrantBoard: how does your recusal mechanism actually stop a connected committee member from scoring?
8. PayRun: what happens if someone tries to edit a closed pay period?
9. Pick one engagement where you corrected your AI coding agent. What was wrong, how did you notice, what changed in your next spec?
10. This is a mockup. Pick any engagement: what would need to change before it handled real users and real money or medical data?
11. Which domain took longest to scope correctly, and why? What would you do differently?
12. Given a two-sentence client problem, what's the first thing you do before writing any requirement?
13. Show me your portfolio page, as if I'm a client deciding whether to hire you, in under two minutes.
14. Open any `compilation.md` cold. Find the ship-readiness note in ten seconds. Open any mockup file with no setup. What did writing it this way make possible?

If a resource can't answer these comfortably, or can't clear a mentor-selected live presentation, they're assigned a decimal variant: same structure, seven fresh domains, built again until the gap closes.
