# 1. What You Will Learn

Close any gap below before Day 1, or in the first hour of it. You should already be comfortable building a small application from a written spec.

## Skills and Tools

| What | Why you need it | How to learn it |
|---|---|---|
| The Software Development Lifecycle (SDLC) | You run it, deliberately, five times over this project | `teach-me` skill |
| AI-driven SDLC and spec-driven development | How AI fits into each stage, and why you write the spec before the agent writes code. Your proof of this is `docs/ai-pipeline.md` | `teach-me` skill, then [guide/03-ai-pipeline.md](03-ai-pipeline.md) |
| Requirements writing (SRS, acceptance criteria) | Every engagement starts with one | `teach-me` skill |
| Entity relationship modelling | A schema per engagement | `teach-me` skill |
| Diagramming | You need a schema diagram and a flow diagram per engagement, plus one pipeline diagram | `teach-me` skill. Any tool is fine, see the note below |
| Testing | A test sheet and a regression case per engagement | `teach-me` skill |
| Cost estimation | Every feasibility note needs real build and run figures | `teach-me` skill, plus the public pricing page of an AI or token provider of your choice and a hosting provider of your choice |
| Directing a coding agent | The agent builds, you direct | Anthropic Academy, Claude Code in Action |
| AI context management | Your agent is only as good as the context you give it | `teach-me` skill, then [guide/03-ai-pipeline.md](03-ai-pipeline.md) |
| Loom | Your walkthrough video | [loom.com](https://www.loom.com) |

**On diagrams:** you do not need Mermaid. Use whatever tool you already reach for, as long as the result is clear and drops straight into your document: text that renders inline (Mermaid is one option among several) or an image (PNG or SVG) saved in your repository and embedded with a normal markdown image link. Nobody reviewing your work should need to open a separate app to see it.

**On cost estimation:** this is not AWS-specific. Check the public pricing page of whichever AI or token provider and hosting provider you would actually use for that engagement, and show your figures and your reasoning. AWS is one option, not a requirement.

**Your funnel:** once you have learned the SDLC and how AI fits into it, turn what you learned into your own pipeline diagram in `docs/ai-pipeline.md` (guide 3), before you touch Engagement 1. That diagram is your funnel: the actual path you follow, stage by stage, for all five engagements, not a one-off exercise.

## Certifications (optional, free, external)

- Anthropic Academy: Claude Code in Action
- AWS Skill Builder: AWS Cloud Practitioner Essentials
- EF SET English test, if English has been flagged

TSS does not issue certificates. External ones carry more weight with clients. If you complete one while working on this project, list it in `SUBMISSION.md` with a verification link.

## The Two Skills Included

Both are in `.claude/skills/` and load automatically in Claude Code. With another tool, paste the `SKILL.md` into its instructions.

- **teach-me:** say "teach me" plus a topic. It teaches one skill hands-on, then asks you to log it.
- **troubleshoot:** describe what broke. It guides you to the cause without handing you the fix.

## Your AI as Domain Expert

You will not know these five industries. Before writing requirements, ask your AI assistant how the industry actually works, then check what it tells you against a real source. Never take it on faith.

## Log As You Go

Every skill or domain you pick up goes in `LEARNING_LOG.md` with a confidence score from one to three. Your reviewer compares it with what your work shows.
