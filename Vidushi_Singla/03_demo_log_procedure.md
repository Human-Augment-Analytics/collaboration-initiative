# Demo Log Procedure

**Procedure Owner:** Project manager, project lead, or assigned documentation owner  
**Intended Audience:** HAAG project managers, project leads, current researchers, new contributors, and future managers  
**Estimated Effort:** 15-20 minutes to create the first version; 5-10 minutes per meaningful update  
**Primary Artifact Produced:** `DEMO_LOG.md`

## Purpose

The Demo Log is a running plain-language project history. It records meaningful updates, experiments, decisions, blockers, and next steps so that future contributors can understand how the project is evolving.

The Demo Log is not a meeting transcript. It is not a replacement for a technical tracker, code repository, benchmark spreadsheet, or paper draft. It is a readable bridge between those materials and project understanding.

A new contributor should be able to read the most recent Demo Log entries and understand:

- what changed recently,
- why the change mattered,
- where the evidence or source material lives,
- and what the team is likely to do next.

## When to Use This Procedure

Use this procedure when:

- a project has meaningful updates spread across Slack, meetings, trackers, or code commits,
- project decisions are being made informally and may be hard to reconstruct later,
- a project has new members joining across semesters,
- the team is preparing for publication, handoff, or a presentation,
- or contributors repeatedly ask what happened recently and what the current direction is.

## What Counts as a Demo Log Entry

Add an entry when something happens that a future contributor would need to know. Examples include:

- a meaningful experiment result,
- a comparison across methods,
- a major bug fix,
- a change in technical direction,
- a decision about publication or deliverables,
- a blocker that affects next steps,
- a new dataset, implementation, or artifact,
- a theory discussion that changes interpretation of results,
- or a new question that changes the team's priorities.

Do not add entries for every minor message, routine check-in, or small administrative update. The Demo Log should stay useful and readable.

## Required Fields

Each Demo Log entry should include:

| Field | Purpose |
| --- | --- |
| Date | When the update happened or was discussed. |
| Category | Experiment, decision, blocker, publication, artifact, theory, or process. |
| Update | What changed, was tested, was created, or was decided. |
| Why It Matters | Why the update affects project direction or onboarding context. |
| Evidence / Link | Link to the source material, such as code, tracker, benchmark output, meeting note, Slack summary, paper, or presentation. |
| Next Step | What should happen next. |
| Owner | Person or role closest to the update or follow-up. |

## Step-by-Step Instructions

### Step 1: Create the file

Create a Markdown file named:

```text
DEMO_LOG.md
```

Place it in the same project workspace as the Project Snapshot and Artifact Hub.

### Step 2: Add the table header

Use this structure:

```markdown
# [Project Name] Demo Log

Last updated: [Date]  
Primary owner: [Name / Role]  
Backup owner: [Name / Role]

| Date | Category | Update | Why It Matters | Evidence / Link | Next Step | Owner |
| --- | --- | --- | --- | --- | --- | --- |
```

### Step 3: Add entries in reverse chronological order

Place the newest entry at the top so new contributors can quickly understand the current direction.

### Step 4: Write in plain language

Each entry should be understandable to someone who is new to the project. Avoid unexplained jargon. If a technical term is important, define it in the Project Snapshot or link to a background resource in the Artifact Hub.

### Step 5: Link to the source of truth

The Demo Log should summarize the update and link to the real artifact. Do not paste long experiment outputs, full meeting transcripts, or large code snippets into the log.

### Step 6: Keep entries short

A strong entry is usually 2-4 sentences across the table fields. If the update needs more detail, summarize the meaning and link to the detailed source.

## Update Triggers

Update the Demo Log when:

- a meaningful benchmark is completed,
- the team compares, selects, or eliminates a method,
- a major implementation issue is fixed,
- the project lead identifies a new priority,
- a theory discussion affects the direction of the work,
- publication planning changes,
- a new artifact is created,
- a new member asks a question that reveals missing context,
- or a semester handoff is approaching.

## Integration into HAAG Structure

To make the Demo Log part of the team's normal workflow:

1. Link the Demo Log from the Project Snapshot and Artifact Hub.
2. Pin the link in the project Slack channel or include it in the welcome message.
3. Add a quick Demo Log check to the manager's weekly or biweekly tracking routine.
4. After each research meeting or major Slack update, ask: "Did anything happen that a future contributor would need to know?"
5. If yes, add one entry within 5-10 minutes.
6. Ask new contributors to read the last three entries before requesting a full project explanation.
7. During manager handoff, include the Demo Log link as the project history source.

## Definition of Done

The Demo Log is complete when:

- recent meaningful updates are visible at the top,
- entries explain what changed and why it matters,
- each entry links to the source material when possible,
- each entry has a next step or follow-up status,
- ownership is clear,
- and a new contributor can understand recent project direction by reading the last few entries.

## Template

```markdown
# [Project Name] Demo Log

Last updated: [Date]  
Primary owner: [Name / Role]  
Backup owner: [Name / Role]

| Date | Category | Update | Why It Matters | Evidence / Link | Next Step | Owner |
| --- | --- | --- | --- | --- | --- | --- |
| [Date] | [Experiment / Decision / Blocker / Artifact / Theory / Process] | [Short summary of what happened.] | [Why this affects project direction or onboarding context.] | [ADD LINK] | [Next step or follow-up.] | [Name / Role] |
```
