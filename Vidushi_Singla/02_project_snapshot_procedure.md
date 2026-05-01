# Project Snapshot Procedure

**Procedure Owner:** Project manager or assigned project lead  
**Intended Audience:** HAAG project managers, project leads, current researchers, new contributors, and future managers  
**Estimated Effort:** 30-45 minutes to create the first version; 5-10 minutes to update when project direction changes  
**Primary Artifact Produced:** `PROJECT_SNAPSHOT.md`

## Purpose

The Project Snapshot is a one-page overview that helps a new or returning contributor quickly understand a HAAG research project. It should answer the questions someone usually has before they can begin contributing:

- What is this project trying to accomplish?
- Why does the project matter?
- What is the current focus?
- What has already been tested or built?
- Where are the most important artifacts?
- Who should I ask for context or access?
- What should I read or do first?

The Snapshot is not meant to replace technical mentorship, the code repository, research papers, or detailed project documentation. It is the first stop before someone goes deeper.

## When to Use This Procedure

Use this procedure when:

- a HAAG research group is onboarding new contributors,
- a project has scattered context across multiple tools,
- a project is preparing for a new semester,
- a manager is handing off responsibilities,
- a project has changed direction and older context may confuse new members,
- or a team notices that new members repeatedly ask the same basic orientation questions.

## Required Sections

Every Project Snapshot should include the following sections.

| Section | Purpose |
| --- | --- |
| Last Updated | Shows whether the Snapshot is current. |
| Project Goal | Explains the project in plain language. |
| Why This Matters | Connects the work to research, HAAG goals, or stakeholder value. |
| Current Focus | Summarizes what the team is working on now. |
| Recent Progress | Lists the most important recent work or decisions. |
| Key Terms | Defines technical terms a newcomer will see often. |
| Key Artifacts | Links to the repository, tracker, notes, papers, Demo Log, and Artifact Hub. |
| People and Roles | Identifies who to contact for project direction, technical help, or access. |
| Starter Path | Gives the first 3-5 steps a new contributor should take. |
| Open Questions / Next Steps | Shows what is currently unresolved or upcoming. |

## Step-by-Step Instructions

### Step 1: Create the file

Create a Markdown file named:

```text
PROJECT_SNAPSHOT.md
```

Place it in the project's existing GitHub repository, wiki, shared drive folder, or official project workspace.

### Step 2: Write the project goal in plain language

Write 2-4 sentences explaining what the project is trying to do. Avoid assuming the reader already understands the technical area.

Example structure:

```markdown
## Project Goal

This project aims to [main goal] by [general method or approach]. The team is currently focused on [current direction]. The goal is to produce [expected research, tool, benchmark, paper, or deliverable].
```

### Step 3: Add the current focus

List the main workstreams currently active in the project. Keep this short. The Snapshot should help people orient, not replace the tracker.

Example:

```markdown
## Current Focus

- Comparing candidate methods against baseline approaches.
- Improving implementation speed and reliability.
- Documenting experiment results for future publication.
- Identifying the next benchmark or dataset to test.
```

### Step 4: Add key artifacts

Link to the most important materials. Do not include every file the project has ever created. Include only the artifacts a newcomer would reasonably need.

Recommended links:

- code repository,
- experiment or task tracker,
- Demo Log,
- Artifact Hub,
- meeting notes or summary folder,
- key papers or background reading,
- final presentation or project overview slides,
- access request instructions.

### Step 5: Add a starter path

The starter path should tell a new contributor exactly what to do first.

Example:

```markdown
## Starter Path for New Contributors

1. Read this Project Snapshot.
2. Read the last three Demo Log entries.
3. Open the Artifact Hub and confirm you can access the repository and tracker.
4. Review the current focus and open questions.
5. Ask the project lead or manager which starter task is highest priority this week.
```

### Step 6: Assign an owner

At the bottom of the Snapshot, list the owner and backup owner.

Example:

```markdown
## Maintenance

Primary owner: [Name / Role]  
Backup owner: [Name / Role]  
Review cadence: Start of semester, after major project-direction changes, and during manager handoff.
```

## Update Triggers

Update the Project Snapshot when:

- the project goal changes,
- the current focus changes,
- a new major artifact is created,
- the project lead or manager changes,
- a new contributor points out missing context,
- the team begins a new semester,
- or the project enters a new stage such as benchmarking, paper writing, deployment, or handoff.

## Integration into HAAG Structure

To make the Snapshot part of the team's normal workflow:

1. Link it from the project's Artifact Hub.
2. Pin it in the project Slack channel or include it in the project welcome message.
3. Ask new contributors to read it before their first onboarding conversation.
4. Review it during manager handoff.
5. Check it at the start of each semester.
6. Treat it as the first-stop orientation artifact for the project.

## Definition of Done

The Project Snapshot is complete when:

- it is understandable without outside explanation,
- it explains the project goal and current focus,
- it links to the main artifacts,
- it names the right people or roles to contact,
- it gives a clear starter path,
- it has a last updated date,
- and it can be read in under five minutes.

## Template

```markdown
# [Project Name] Project Snapshot

Last updated: [Date]  
Primary owner: [Name / Role]  
Backup owner: [Name / Role]

## Project Goal

[Explain the project in plain language.]

## Why This Matters

[Explain why the work matters to HAAG, the research group, or the broader project goal.]

## Current Focus

- [Current focus 1]
- [Current focus 2]
- [Current focus 3]

## Recent Progress

- [Recent update 1]
- [Recent update 2]
- [Recent update 3]

## Key Terms

| Term | Plain-Language Meaning |
| --- | --- |
| [Term] | [Definition] |

## Key Artifacts

| Artifact | Link | Purpose |
| --- | --- | --- |
| Artifact Hub | [ADD LINK] | One place to find project materials. |
| Demo Log | [ADD LINK] | Recent project updates and decisions. |
| Repository | [ADD LINK] | Code and implementation. |
| Tracker | [ADD LINK] | Tasks, experiments, or benchmarks. |

## People and Roles

| Role | Person / Contact | Ask Them About |
| --- | --- | --- |
| Project Lead | [ADD NAME] | Project direction and priorities. |
| Manager | [ADD NAME] | Onboarding, trackers, and coordination. |
| Technical Contact | [ADD NAME] | Code, experiments, or implementation. |

## Starter Path for New Contributors

1. Read this Project Snapshot.
2. Read the last three Demo Log entries.
3. Open the Artifact Hub and confirm access to key links.
4. Review the current focus and open questions.
5. Ask the project lead or manager which starter task is highest priority.

## Open Questions / Next Steps

- [Question or next step 1]
- [Question or next step 2]
- [Question or next step 3]

## Maintenance

Primary owner: [Name / Role]  
Backup owner: [Name / Role]  
Review cadence: [Start of semester / after major updates / manager handoff]
```
