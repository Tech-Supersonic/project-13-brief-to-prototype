# Success Criteria: Project 13, Brief to Prototype

What "done" means and how you are scored. Check every box before you submit.

---

## 1. Definition of Done

Anything missing sends your submission back before a human sees it.

### Per engagement (all five)

- [ ] `context/scenario-N-name/spec.md` exists and was committed before the mockup
- [ ] `compilation.md` has all seven sections filled in, in order
- [ ] Build and run costs are real figures, with reasoning
- [ ] The SRS names at least one domain rule not stated in the brief, and says how you checked it
- [ ] At least two diagrams (a schema and a critical flow), in any tool, displaying inline with no separate app needed
- [ ] The agent direction log records at least one real correction
- [ ] The test sheet has at least six checks and one regression case tied to a real defect
- [ ] `mockup.html` opens from disk and is clickable through its core flow
- [ ] At least two screenshots in `proof/scenario-N-name/`

### Project level

- [ ] `CLAUDE.md` filled in with your own content, and updated during the project
- [ ] `docs/ai-pipeline.md` has all five parts, including a pipeline diagram (any tool) covering every stage and your marked folder tree
- [ ] `docs/reflection.md` compares Engagement 1 with Engagement 5
- [ ] `LEARNING_LOG.md` has at least five entries with confidence scores
- [ ] `SUBMISSION.md` is filled in
- [ ] A Loom of 8 minutes or less, covering all five engagements
- [ ] At least one commit per engagement, spread across the timeline
- [ ] No secrets and no real personal data anywhere

---

## 2. How You Are Scored

Scoring uses the same Rubric v5 that scored your interview: a whole number from 1 to 5 per category.

1. **AI check.** Confirms everything above is present and every link works, then drafts a score for each category with quoted evidence from your files.
2. **Human review.** A senior reviewer watches your Loom, clicks through your mockups, reads your AI pipeline, checks the AI draft, and runs the live review. **The reviewer's score is final.**
3. **Result.**

| Result | Meaning | Next |
|---|---|---|
| **Pass** | Categories 5, 6, 10 and 12 each meet the target in your training plan | Your rubric profile updates; next project |
| **Variant** | A main category is below target but closable | Variant 10.1: same structure, five fresh domains |
| **Not yet** | The gaps are not closing | An honest conversation about next steps |

If you were assigned this project outside a training plan, the target is **4** on each main category.

---

## 3. What Strong Looks Like

A 4 is the usual target.

| Category | A 3 | A 4 | A 5 |
|---|---|---|---|
| **5 System Design** | Correct for the happy path; costs given but thinly reasoned | Designs cover the rules and failure cases; costs reasoned with scale in mind; tradeoffs stated | Challenges a brief that does not hold up; cost reasoning changes a design; defends numbers under pushback |
| **6 AI Tooling and Workflow** | Uses the agent but mostly accepts first output; pipeline is generic | Specs written before builds; real corrections logged; pipeline matches what the fork shows; `CLAUDE.md` grows with lessons | Deliberate, well-reasoned pipeline with clear human checkpoints; context managed tightly; spec quality visibly improves across engagements |
| **10 Independent Operation** | Requirements restate the brief; rules found only with heavy prompting | A real, checked unstated rule per engagement; clear scope and out-of-scope | Surfaces rules an expert would expect; spots risks the client never raised; visibly faster by Engagement 5 |
| **12 Client and Communication** | Accurate but technical or hesitant; reacts to questions | Clear client language in under five minutes; handles pushback calmly | Polished and persuasive; turns pushback into a better recommendation |
| **2 SDLC** | Shallow test sheets | Real defects caught with regression cases | Tests written before building, and they shape the build |
| **14 Aptitude** | Learning log exists | Log confidence matches what the review shows | Fast, deliberate learning across five domains, clearly evidenced |
