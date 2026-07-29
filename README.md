# Project 13: The Consultancy

| Field | Detail |
|---|---|
| Project Number | 13 |
| Project Name | The Consultancy |
| Tier | Mid |
| Deadline | 10 working days (2 weeks) from your start date |
| Status | Active |
| Tags | Requirements Analysis, Feasibility and Cost Estimation, SRS, System Design, Database Design, Sequence Diagrams, AI-Assisted Mockup Building, Client Presentation, Interview Readiness, Portfolio Packaging, Resume and LinkedIn Writing |

---

## Overview

You are running seven short client engagements, one after another, each for a different company in a different industry. Each engagement gives you a real business problem. You are responsible for the entire lifecycle of the response: figuring out whether the idea is even worth building, writing the requirements, designing the system and the database, building a working mockup with an AI coding agent doing the typing, checking it against a test sheet, deciding how it would actually ship, and then presenting it back as if to the client who asked for it.

This project exists to build one thing above everything else: the habit of running a full lifecycle, quickly and correctly, on a problem you have never seen before, in an industry you do not already know, and then explaining it clearly and confidently out loud to someone who is not technical. That last part, presenting under real questioning, is deliberately trained seven times here, because it is the skill most resources from non-English-speaking backgrounds get the least practice on, and it does not improve without repetition.

What you build in each engagement is a working mockup, not a production product. Every screen and flow should genuinely work when you click through it: forms save, lists update, the one AI feature actually responds. What it does not need is hardened security, a real deployment pipeline, exhaustive test coverage, or a live hosted URL. Each mockup is a standalone HTML file that runs by opening it in a browser, sitting in its own folder in your repository. The point is not to prove the system could survive real production traffic or stay online. The point is to prove you can think through a full lifecycle correctly and produce something real enough to demo confidently, seven times, across seven different industries. This project is fully generic: it is written so it can be handed to any resource at this tier, with no assumption about which domain they already know.

Each engagement also produces one single document, not a folder full of separate files. Feasibility, requirements, design, and diagrams all live together in one place, in the order you would actually walk someone through them, with diagrams drawn directly in the document itself rather than in a separate diagramming tool. This keeps seven engagements from turning into forty scattered files.

By the end, you will have seven small, demoable mockups sitting in your own public GitHub repository, fully documented, with resume and LinkedIn material drawn directly from them.

---

## Covered Areas

| Category | Area |
|---|---|
| SDLC and Engineering Practices | Development Lifecycle |
| SDLC and Engineering Practices | Testing Discipline |
| Programming and Stack Fundamentals | API Construction |
| Programming and Stack Fundamentals | Database Design |
| AI-Driven Development and Automation | Coding Agents |
| AI-Driven Development and Automation | Multi-Tool Fluency |
| System Design and Architecture | Architecture and Tradeoffs |
| System Design and Architecture | Cost-Aware Design |
| Independent Operation and Delivery | Scoping and Requirements |
| Independent Operation and Delivery | Self-Management |
| Career Assets and Hireability | Business and ROI Fluency |
| Career Assets and Hireability | Portfolio Projects |
| Career Assets and Hireability | Resume, LinkedIn, and Upwork Readiness |

Communication and Client Readiness (Technical Explanation, Written Communication, Spoken English and Verbal Communication, Interview and Client Q&A) is trained through the Review and Presentation section below, on every one of the seven engagements, rather than as a separate piece of work. This project trains it more heavily than most, on purpose.

---

## What Is Tested

By the end of this project, you should be able to show, on request:

- A feasibility judgment and a cost estimate you can defend, for a problem you were not given a template for.
- One compiled document per engagement that a stakeholder who has never met you could read start to finish and understand what is being built, why, and how, with diagrams that render in place rather than living in a separate file.
- A system design and a database design that fit the actual problem, not a copy of an earlier project's schema with different table names.
- A diagram for the critical flow in each engagement, accurate enough that someone could implement from it.
- Correct use of an AI coding agent to build a real, clickable, standalone mockup from a spec you wrote, with you directing it rather than accepting whatever it produces first.
- A completed test sheet showing what you checked in each mockup and what you found.
- Seven mockups sitting in your own public GitHub repository, each openable directly as a file with no server or hosting required, plus a portfolio page and resume material built from them.
- Seven short, clear presentations of problem, solution, and implementation, with at least two defended live under real questioning.

## What Is Learned

- How to judge, quickly, whether an idea is worth building, and how to put a real number on what it would cost to build and to run.
- How to turn a short, informal problem statement into a proper SRS, including the requirements the client did not think to state.
- How to design a system and a database for a domain you do not already know, by asking the right questions about the domain's rules before you draw anything.
- How to write a sequence diagram that actually captures a critical flow, not just a happy path box diagram, using a diagram-as-code syntax you can embed directly in a markdown document.
- How to direct an AI coding agent as the implementer of a working mockup: writing a spec it can build from, reviewing what it produces, and catching what it gets wrong.
- How to build a mockup as a single self-contained file that anyone can open and use immediately, with no server, no build step, and no account to sign up for.
- The difference between what a mockup needs to prove and what a production system needs to prove, and why confusing the two wastes your limited time.
- How to compile a feasibility note, requirements, design, and diagrams into one coherent document instead of scattering them across many files, and why that single-document habit matters when someone else has to actually read your work.
- How to package finished work into something a stranger can immediately understand: a demo-ready repository, a live link, and a resume line.
- How to explain the same piece of work seven different ways to seven different audiences, and hold your own under real, unscripted questioning each time.

## What Is Practiced

- Running the full development lifecycle, in order, seven times, on unfamiliar problems, on a tight timeline.
- Feasibility and cost analysis as a real deliverable, not a throwaway paragraph.
- Requirements analysis on a domain you have to learn quickly, including recognizing what you do not know and asking for it.
- System design, database design, and sequence diagramming as fast, repeatable habits rather than one-off exercises.
- Directing AI-assisted mockup building: prompting from a spec, reviewing output critically, and taking ownership of what gets shipped.
- Writing and running a real test sheet, focused on what a demo needs to survive rather than what a production system needs to survive.
- Presenting the same project structure, problem, solution, implementation, seven times, sharpening the delivery each time.
- Answering interview-style, client-style questions live, with no script, immediately after each build.
- Packaging finished work for the outside world: a public repository, a live demo link, and resume and LinkedIn writing.

---

## Prerequisites

Before starting, you should already have completed Project 1 (or an equivalent) and have working experience with the following. If any of these feel shaky, ask your AI Instructor for a short, fast revision before you start, rather than during an engagement.

- Building a REST API and a relational database from a written specification
- Directing an AI coding agent such as Claude Code to implement a feature from a plan you wrote
- Basic familiarity with git branching and commits
- Comfort reading an unfamiliar problem statement and asking clarifying questions before building

### Setting up your AI Instructor and troubleshooting partner

The same two skills from your earlier projects are included in this repository, in the `skills/` folder. Add both to your Claude project before you start.

- **Learning agent** (`skills/teach-me/SKILL.md`). Say "teach me" followed by a topic, and it walks you through it one step at a time, has you do the work yourself, and asks you for a confidence score at the end. Save that score and reflection in `LEARNING_LOG.md`.
- **Troubleshooting agent** (`skills/troubleshoot/SKILL.md`). Describe what has broken and it guides you to the cause instead of handing you the fix.

For this project specifically, your AI Instructor also plays a third role: a stand-in domain expert. When you start an engagement in an industry you do not know, ask it to explain the domain's basic rules and vocabulary before you write requirements against it. Treat that explanation as a starting point to verify, not as ground truth to copy blindly, the same way you would treat a client's first explanation of their own business.

---

## How to Learn This

Work through the concepts below before your first engagement. You will not have time to learn these mid-cycle once the seven engagements are underway.

| Topic | Learn With Your AI Instructor | Official Documentation | Optional Video Reference |
|---|---|---|---|
| Feasibility analysis and build versus run cost | Ask it to walk you through a worked cost estimate for a small system, covering both build effort and ongoing run cost including AI token spend | Your chosen cloud provider's pricing calculator, and your chosen AI provider's pricing page | Search for a short explainer on rough order of magnitude estimation |
| Writing an SRS from a short problem statement | Ask it to show you the gap between a one-paragraph client ask and a full SRS, and what questions closed that gap | IEEE SRS structure as a reference, adapted to a lighter format for this project | Optional |
| System design for an unfamiliar domain | Ask it to interview you the way you should interview a client, extracting entities, rules, and edge cases from a vague brief | Your chosen backend framework's architecture guidance | Optional |
| Database design for a new domain | Ask it to review your schema sketch and challenge assumptions before you build it | Your chosen database's official documentation | A short video on normalization if the concept is new |
| Sequence diagrams as diagram-as-code | Ask it to walk through writing a Mermaid sequence diagram for a login flow, then hand it a harder flow to critique your attempt | Mermaid's official sequence diagram syntax documentation | A short demo of reading a sequence diagram |
| Directing an AI coding agent to build a mockup | Ask it to explain what a good implementation spec looks like versus a vague one, and why the difference matters for output quality | Your chosen coding agent's official documentation on writing effective prompts or specs | Optional |
| Building a single-file HTML mockup | Ask it to explain how to keep HTML, CSS, and JavaScript in one file with fixture data instead of a real backend, and when that stops being enough | MDN's guides on HTML, CSS, and JavaScript basics | Optional |
| Mockup versus production test scope | Ask it to explain what a demo-critical test sheet should cover that a full regression suite would also cover, and what it can safely skip | Your chosen test framework's documentation, read for reference only | Optional |
| Writing resume and LinkedIn material from a project | Ask it to turn a project summary into two or three outcome-focused resume bullets, then critique your own draft against them | Your resume or LinkedIn's own writing guidance | Optional |

Structured paid courses are not required at the moment. If you are still stuck after trying the options above, speak with your mentor before looking for a course.

### Work manually first, then let AI accelerate the rest

For every engagement, sketch the entities, the schema, and the critical flow by hand or talked through out loud with your AI Instructor, before you generate any of it or hand a spec to your coding agent. Once you understand what you are building and why, using a coding agent to accelerate the actual mockup build is expected and encouraged, since that mirrors how this work is done professionally under real client timelines. What matters is that you can explain every decision afterward, in your own words, without notes, on all seven engagements, not just the ones still fresh in memory.

---

## Electives: Underlying Skills You Will Also Learn

Pick the options that match your chosen approach. You do not need to use the same approach across all seven engagements, but switching every time will cost you time you do not have on a one-day cycle, so choose once and stay consistent unless a mentor tells you otherwise.

**Frontend, for the mockup itself**
- Plain HTML, CSS, and JavaScript in a single file, with fixture data held in a JavaScript array or object standing in for a database. This is the default and the fastest path for this project. Official documentation: MDN Web Docs
- A frontend framework such as React, if you are more fluent in it than in plain HTML and CSS, as long as you produce a static export that still opens and runs as a self-contained set of files with no server needed

**Diagramming**
- Mermaid, written as code blocks directly inside your compiled document. GitHub, and most markdown viewers, render these automatically, so a diagram opens the moment someone reads your document, with no separate diagramming tool involved. Official documentation: mermaid.js.org

---

## Recommended Stack

For the mockup, the recommended and fastest approach is a single self-contained HTML file per engagement: inline CSS, inline JavaScript, and a small amount of fixture data standing in for a real backend and database. This is not a downgrade from building a real application. It is the correct tool for what this project is testing, which is your requirements, design, and presentation thinking, not your ability to stand up infrastructure. If you strongly prefer a frontend framework, that is acceptable as long as the result still runs by opening a file with no server, no build step, and no account required from whoever is reviewing it. Diagram everything in Mermaid inside your compiled document rather than in a separate tool.

---

## The Exact Brief

Run seven client engagements. Each one is a short, standalone consulting cycle: understand the problem, judge whether it is worth building, design it, build a working mockup with an AI coding agent, check it against a test sheet, decide how it would ship, and present it back. A closing phase then turns all seven into a public portfolio.

### The Seven Engagements

**Engagement 1: LoanDesk (Financial Services)**

A small microfinance lender wants to stop originating loans over email and spreadsheets. Mock up a loan origination system: an application intake form, a document checklist the applicant must satisfy before review, eligibility and affordability rules that decide whether an application can proceed, an amortization schedule generated for any approved loan amount, term, and interest rate, a two-step approval flow (a reviewer recommends, a separate approver decides), and an audit trail showing who did what to each application and when. Your requirements analysis must surface the affordability rule yourself. The client will only tell you "we do not want to lend to people who cannot pay it back" if asked the right question.

**Engagement 2: LabLine (Healthcare)**

A diagnostic lab wants to move result delivery off phone calls and PDF email attachments. Mock up a lab result portal: test orders linked to a patient, result entry against each test's normal reference range with automatic flagging when a result falls outside it, a doctor review and release step before a patient can see anything, patient consent captured before any result is shared, and a critical-value alert that fires immediately when a result is dangerously abnormal, separate from the normal release flow. Get the release gate right in your design, even in mockup form. A result that reaches a patient before a doctor has seen it is the single worst failure mode in this engagement, and your design should make that failure structurally difficult, not just documented as a rule.

**Engagement 3: ClauseTrack (Legal)**

A small legal team wants to stop tracking contracts in a shared folder of Word documents. Mock up a contract lifecycle tool: a clause library that clauses can be pulled from, version history on every contract so nothing is silently overwritten, an approval chain before a contract is considered final, renewal and obligation deadline tracking that surfaces what is coming due, and an AI feature that summarizes a contract's key terms in plain language, with the summary always shown alongside the source clause it came from rather than presented as authoritative on its own. Decide, and be ready to defend, exactly what your AI summary feature is and is not allowed to be relied on for.

**Engagement 4: ClaimGate (Insurance)**

A motor insurer wants to speed up first notice of loss without approving anything automatically. Mock up a claim intake and triage system: an incident report form, photo evidence upload, automatic validation that the claimed policy is active and covers the claimed event, a set of fraud red-flag rules that score and surface suspicious claims for human attention rather than rejecting them outright, assessor assignment, and a settlement calculation based on policy limits and any applicable deductible. The fraud rules are a scoring signal for a human, not an automatic decision. Your design should make it obvious that a flagged claim still requires a person to act on it.

**Engagement 5: ColdChain (Logistics)**

A pharmaceutical distributor needs to prove its shipments stayed within a safe temperature range the entire way. Mock up a cold chain monitoring system: shipment registration with a required temperature range, a simulated temperature feed you generate yourself (no real hardware is available for this engagement, so build a realistic simulator that can be told to behave normally or to drift out of range on command), automatic breach detection against the shipment's required range, a custody handover chain recording who held the shipment at each leg of the journey, and a liability report that can be generated for any shipment showing its full temperature history and who held it when a breach occurred. Design your breach detection to be explainable. A liability report a court could not follow is not a working feature.

**Engagement 6: GrantBoard (Education)**

A scholarship foundation wants to stop running applications through a shared inbox. Mock up a scholarship application system: application windows that open and close on a schedule, document verification against a required checklist, a weighted scoring rubric that committee members apply consistently, a recusal mechanism so a committee member connected to an applicant is excluded from scoring that application, and award letters and an appeals process for rejected applicants. Your design should make the scoring rubric visible and consistent enough that two different committee members would reach comparable scores on the same application.

**Engagement 7: PayRun (HR and Finance)**

A small company wants to stop running payroll by hand in a spreadsheet. Mock up a payroll system: employee salary structures, attendance import, a tax calculation against a stated tax slab table, generated payslips, a disbursement export file, and a month-end lock that prevents changes to a payroll period once it has been finalized. Get the tax calculation and the month-end lock right in your design, even in mockup form. A payroll system that lets someone quietly edit a closed pay period is the single worst failure mode in this engagement.

### The Standard Deliverable Set, Every Engagement

Every engagement produces exactly two things, regardless of domain: one compiled document, and one standalone mockup. This consistency is deliberate: by the seventh engagement, the shape of the work should feel familiar even though the domain does not, and a reviewer should be able to open exactly two things per engagement to see everything.

**One compiled document, `compilation.md`**, written as a single markdown file in this order:

1. **Feasibility note**, including a stated build cost estimate (your time, priced as if billed) and a run cost estimate (hosting, database, and AI token cost at a stated usage assumption), with your reasoning shown, not just a final number.
2. **SRS**, covering functional requirements, the domain rules you had to surface yourself, and explicit out-of-scope items.
3. **System and database design**, covering the components, the schema and its relationships, and the key tradeoffs you chose between, with the schema relationships and the engagement's critical flow drawn as Mermaid diagrams directly in this section.
4. **Agent direction log**, a short record of what you asked your AI coding agent to build, what it got right, and what you had to correct.
5. **Test sheet**, listing what you checked in the mockup, the result, and any issue found and its status. This is scoped to what a confident demo needs to survive, not to production-grade coverage.
6. **Ship-readiness note**, one paragraph on what would need to be added to take the mockup to a real production system. This is a written judgment, not a built pipeline.
7. **Retrospective**, what went well, what you would do differently, and how this engagement compared to the one before it.

**One standalone mockup**, a single self-contained file (or a small folder if your approach genuinely requires more than one file) that opens directly in a browser with no server, no build step, and no hosting. Every screen and flow in it must genuinely work when clicked through: forms save to in-memory or local storage, lists update, the one AI feature responds, even though nothing here is a real backend.

### Quality Bar

- The feasibility section of every `compilation.md` must include a real, reasoned number, not a placeholder.
- Every SRS section must contain at least one requirement that came from a domain rule you had to ask about or research, not one that was stated outright in the brief above.
- Every diagram lives inside `compilation.md` as Mermaid, not as a separate file in a separate tool.
- Every mockup must be genuinely clickable through its core flow, and must open with nothing more than a browser. A screen that only looks right but does nothing when used does not meet this bar. A mockup that needs a server, an account, or a build step to run does not meet this bar.
- Every engagement must be presentable on its own, in under five minutes, to someone who has not read this brief.

---

## Requirements and Scope

**In scope:**
- All seven engagements listed above, each carried through the full lifecycle
- One compiled document per engagement (`compilation.md`), covering feasibility, SRS, system and database design with Mermaid diagrams, the agent direction log, the test sheet, the ship-readiness note, and the retrospective, in that order
- A working, clickable, standalone mockup for each engagement, opening with no server, no build step, and no hosting
- A final cross-engagement reflection
- Seven live presentations, or a mentor-selected subset presented live with the rest presented in writing, at your mentor's discretion
- A final portfolio packaging phase covering all seven engagements: a clean public repository, a portfolio page, and resume and LinkedIn material

**Out of scope for this project:**
- Full production hardening, security review, or compliance certification of any engagement. Domain rules such as consent, audit trails, and human-in-the-loop gates are required as functional mockup features. A full compliance audit is not
- Real integration with any external system (a real payment processor, a real lab instrument, real hardware sensors). Simulate anything a real integration would provide
- A real CI/CD pipeline, automated regression suite, or production deployment infrastructure for any of the seven. The written ship-readiness note replaces this
- Live hosting of any mockup. A mockup that only runs by opening a file is the expected and correct outcome, not a shortcut
- A single shared codebase across all seven engagements. Each is its own small system, though you may reuse your own boilerplate

**Definition of done, in plain language:** for each of the seven engagements, someone unfamiliar with the problem can open one `compilation.md` and understand what was built, why, and how, open the one mockup file and see it genuinely work with nothing more than a browser, and watch or hear you present the problem, your solution, and your implementation without notes. By the end, all seven live in your own public GitHub with a portfolio page and resume material pointing at them.

---

## Project Phases

Each of the seven engagements runs through the same three build phases, compressed into roughly one working day, followed by a shared closing phase once all seven are done. Seven days of engagements plus a closing phase fills the ten working day project timeline.

### Phase 1: Requirements and Planning (per engagement)

Substeps:
- Read the engagement's brief and identify what domain rules are implied but not stated outright
- Use your AI Instructor as a stand-in domain expert to fill gaps, and verify what it tells you rather than accepting it uncritically
- Start `compilation.md` and write its feasibility section, including your cost estimate and reasoning
- Write the SRS section
- Sketch the system design, the database schema, and the critical-flow diagram by hand before generating anything, then write the system and database design section with the schema and the critical flow as Mermaid diagrams

Artifact produced, per engagement, in `docs/scenario-N-name/`:
- `compilation.md`, feasibility through system and database design sections complete

### Phase 2: Mockup Build (per engagement)

Substeps:
- Write an implementation spec clear enough to hand to a coding agent
- Direct your coding agent through the build, reviewing its output at each meaningful step rather than only at the end
- Correct what it gets wrong, and note what you corrected
- Confirm the mockup opens and runs with nothing more than a browser, no server, build step, or hosting involved

Artifacts produced, per engagement:
- The standalone mockup file (or small folder) in `src/scenario-N-name/`
- The agent direction log, added as its own section in `compilation.md`

### Phase 3: Check and Present (per engagement)

Substeps:
- Run through the mockup end to end and write the test sheet section
- Write the ship-readiness note section
- Write the retrospective section, closing out `compilation.md` for this engagement
- Prepare and give a short problem, solution, implementation walkthrough, live if this is one of your mentor-selected engagements

Artifact produced, per engagement:
- `compilation.md`, all seven sections complete: feasibility, SRS, system and database design, agent direction log, test sheet, ship-readiness note, retrospective

### Phase 4: Portfolio Packaging (after all seven engagements)

This phase runs once, after all seven engagements are complete, not per engagement.

Substeps:
- Write the cross-engagement reflection: what got faster or better across the seven cycles, which domain was hardest to scope correctly and why, and what pattern you now use for the first hour of any new client engagement
- Confirm each engagement's folder is public, its `compilation.md` opens cleanly on GitHub with diagrams rendering, and its mockup can be understood by a stranger in under two minutes
- Add all seven, or your strongest three to five, to your portfolio site from Project 0, linking each entry to its folder in this repository
- Write two or three outcome-focused resume bullets and a LinkedIn project entry drawing on this project as a whole
- Confirm every live link still works before submitting

Artifacts produced:
- `docs/reflection.md` (top level, not inside a scenario folder)
- Updated portfolio site (external to this repository, linked from `PRESENTATION.md`)
- Resume and LinkedIn material (linked or pasted into `PRESENTATION.md`)

---

## Artifact and Folder Guide

| Artifact | Format | Location |
|---|---|---|
| Compiled document (feasibility, SRS, design with Mermaid diagrams, agent log, test sheet, ship-readiness note, retrospective) | Markdown | `docs/scenario-N-name/compilation.md` |
| Standalone mockup | Self-contained HTML, or a small static file set | `src/scenario-N-name/` |
| Cross-engagement reflection | Markdown | `docs/reflection.md` |
| Learning log | Markdown | `LEARNING_LOG.md` |
| Submission, including portfolio and resume material | Markdown | `PRESENTATION.md` |
| Screenshots and other evidence | Images or links | `proof/scenario-N-name/` |

The seven scenario names, in order, are `scenario-1-loandesk`, `scenario-2-labline`, `scenario-3-clausetrack`, `scenario-4-claimgate`, `scenario-5-coldchain`, `scenario-6-grantboard`, `scenario-7-payrun`. Empty starter folders for each already exist in the repository. Each engagement's whole compiled record is exactly two things: one `compilation.md` and one mockup file. A reviewer never needs to open more than that per engagement.

---

## How this works

- Fork the project repository that has been shared with you.
- Work through the seven engagements in order, inside your fork.
- As you finish each engagement, commit your work and save your proof into that engagement's `proof/` subfolder.
- Keep `LEARNING_LOG.md` updated as you go, one entry per skill, produced with your teach-me skill.
- After all seven, complete the Portfolio Packaging phase.
- When everything is done, fill in `PRESENTATION.md` with every link, artifact, and proof of learning across all seven engagements, plus your portfolio and resume material.
- Add your mentor as a collaborator on your fork.
- Schedule a call and present your work.

## Repository structure

```
project-13-the-consultancy/
  README.md              This brief. Read it, do not edit it.
  PRESENTATION.md         Your submission. All links, artifacts, and proof go here.
  LEARNING_LOG.md         One short wrap up per skill you learn.
  skills/
    teach-me/SKILL.md       Your learning agent (provided).
    troubleshoot/SKILL.md   Your troubleshooting agent (provided).
  proof/
    scenario-1-loandesk/    Screenshots and other evidence for this engagement.
    scenario-2-labline/
    scenario-3-clausetrack/
    scenario-4-claimgate/
    scenario-5-coldchain/
    scenario-6-grantboard/
    scenario-7-payrun/
  docs/
    project-brief.md        Internal tracking metadata for mentors, not resource facing content.
    reflection.md            Your final cross-engagement reflection, completed last.
    scenario-1-loandesk/
      compilation.md         Everything for this engagement: feasibility, SRS, design, diagrams, agent log, test sheet, ship-readiness note, retrospective.
    scenario-2-labline/
      compilation.md
    scenario-3-clausetrack/
      compilation.md
    scenario-4-claimgate/
      compilation.md
    scenario-5-coldchain/
      compilation.md
    scenario-6-grantboard/
      compilation.md
    scenario-7-payrun/
      compilation.md
  src/
    scenario-1-loandesk/     Your standalone mockup for this engagement. Opens directly in a browser.
    scenario-2-labline/
    scenario-3-clausetrack/
    scenario-4-claimgate/
    scenario-5-coldchain/
    scenario-6-grantboard/
    scenario-7-payrun/
  .gitignore
  LICENSE
```

Note: this project's scaffold does not include a `Dockerfile`, `tests/`, or `.github/workflows/` folders used by other projects in this library, since a real automated test suite, CI pipeline, and containerized deployment are explicitly out of scope here. If your chosen approach generates them anyway, that is fine, but they are not assessed.

## How to Start Building

1. Fork the project repository into your own account.
2. Read this brief in full before starting Engagement 1.
3. Work through the relevant items in How to Learn This using your teach-me skill, and log each one in `LEARNING_LOG.md`.
4. Start Engagement 1 (LoanDesk). Complete its Phase 1 before touching implementation.
5. Work through Phases 2 and 3 for LoanDesk, then move to Engagement 2. Repeat for all seven.
6. Keep each engagement inside its own scenario folder. Do not let one engagement's code, docs, or proof bleed into another's.
7. If something breaks, use your troubleshoot skill before asking your mentor.
8. After the seventh engagement, complete Phase 4 (Portfolio Packaging).

---

## Definition of Done

- [ ] All seven engagements completed through Phases 1 to 3
- [ ] `compilation.md` completed for each engagement, all seven sections present, with diagrams rendering as Mermaid
- [ ] A genuinely clickable, standalone mockup for each engagement, opening with nothing more than a browser
- [ ] Cross-engagement reflection completed at `docs/reflection.md`
- [ ] All seven engagement folders are public and can be understood by a stranger opening `compilation.md` and the mockup file, with no separate instructions needed
- [ ] Portfolio site updated with this project's engagements
- [ ] Resume and LinkedIn material written and included in `PRESENTATION.md`
- [ ] `LEARNING_LOG.md` has an entry for every area in Covered Areas
- [ ] `PRESENTATION.md` completed with every link, artifact, and proof of learning across all seven engagements
- [ ] Loom video or live walkthrough recorded for each engagement your mentor selects
- [ ] Mentor added as a collaborator on your fork
- [ ] Live presentation call scheduled and completed

---

## Review and Presentation

Once your Definition of Done checklist is complete, submit your work in three formats:

1. **Written.** `PRESENTATION.md` is your submission file. For each of the seven engagements, include the repository link, the path to that engagement's mockup file, and a short note on what was built and what it cost to estimate and to build. Include your portfolio page link and resume material. Pull your skill notes from `LEARNING_LOG.md`.
2. **Video.** Record a short Loom walkthrough for at least the two engagements your mentor selects, explaining problem, solution, and implementation as you demonstrate them.
3. **Live.** Schedule a call with your mentor. On the call, your mentor will pick two of the seven engagements at random or by their own choice. For each one, present problem, solution, and implementation in under five minutes, then answer client-style follow-up questions without notes. Be ready on all seven; you will not know in advance which two are picked.

---

## Bonus Practice Activities

These are optional unless your mentor points you toward one specifically.

**Daily speaking practice with Gemini Live.** If communication has been flagged as an area to work on, use Gemini's interactive live mode for ten minutes a day while working through the engagements. Set it up as your instructor with an instruction along these lines:

> You are my speaking coach. Each day I will tell you which engagement I worked on, what I accomplished, and what my goal for today is on The Consultancy project. Listen to me speak for about ten minutes, then give me clear, honest feedback on my clarity, pace, and confidence, and one specific thing to improve tomorrow.

Follow this simple daily agenda: what you did yesterday, what you accomplished, and what your goal is for today.

**Self recorded review.** Record yourself on camera presenting one engagement's problem, solution, and implementation, using any recording app you have available. Watch it back before your live call and note filler words, pacing issues, and any explanation that was not as clear as you thought it would be. Do this again after your third or fourth engagement and compare the two recordings.

---

## Interview Gap-Check Questions

These questions are drawn from across all seven engagements. You should be able to answer any of them comfortably, on any engagement, without preparation time.

1. Pick any engagement. Walk through how you arrived at your build and run cost estimate. What assumptions did that number depend on, and how would it change if usage were ten times higher?
2. For LoanDesk: what happens, in your mockup, the moment an application fails the affordability rule? Who is notified, and what can and cannot happen to that application afterward?
3. For LabLine: walk through exactly what stops a result from reaching a patient before a doctor has reviewed it. Where in your design is that gate enforced?
4. For ClauseTrack: your AI feature summarizes a contract clause. What happens if that summary is wrong? What did you design to make sure a wrong summary cannot silently become the thing someone relies on?
5. For ClaimGate: a claim scores high on your fraud rules. What actually happens next in your system? Could a claim ever be auto-rejected without a human seeing it, and if not, what prevents that?
6. For ColdChain: your temperature feed is simulated. Explain exactly how your simulator decides to report a breach, and how a liability report traces back to that decision.
7. For GrantBoard: how does your recusal mechanism actually stop a connected committee member from scoring an application? What would happen if that check were missing?
8. For PayRun: walk through exactly what your month-end lock prevents, and what happens if someone tries to edit a closed pay period anyway.
9. Pick one engagement where you had to correct something your AI coding agent got wrong. What was wrong, how did you notice, and what did you change in your next spec to prevent it happening again?
10. This is a mockup, not a production system. Pick any engagement and explain, specifically, what would need to change before it could handle real users and real money or real medical data.
11. Across all seven engagements, which domain took the longest to scope correctly, and what specifically made it hard? What would you do differently if you started that one again today?
12. If a client only gives you a two-sentence problem description, what is the first thing you do before writing any requirement? Show how you actually applied that on one of these seven engagements.
13. Show me your portfolio page. Walk me through it as if I am a client deciding whether to hire you, in under two minutes.
14. Open any one `compilation.md` cold, without me telling you which section to go to. Find the ship-readiness note in under ten seconds. What about writing it as one ordered document made that possible?
15. Open any one mockup file directly, with no setup. What would have had to be true about how you built it for that to just work?

If a resource cannot answer these comfortably, or cannot clear the live presentation for a mentor-selected engagement, they are assigned a decimal variant of this project: the same structure, seven fresh domains, built again until the gap closes.
