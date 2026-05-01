# Artifact Hub Procedure

**Procedure Owner:** Project manager, project lead, or assigned documentation owner  
**Intended Audience:** HAAG project managers, project leads, current researchers, new contributors, and future managers  
**Estimated Effort:** 30 minutes to create the first version; 5 minutes when a new artifact is added or a link changes  
**Primary Artifact Produced:** `ARTIFACT_HUB.md`

## Purpose

The Artifact Hub is a single index of the most important materials for a HAAG research project. It helps contributors find the right source quickly without searching through Slack history, old messages, meeting chats, or scattered folders.

The Artifact Hub should not duplicate the contents of the repository, tracker, meeting notes, papers, or presentations. It should simply point people to the correct source of truth and explain what each artifact is for.

A new contributor should be able to open the Artifact Hub and find:

- the Project Snapshot,
- the Demo Log,
- the code repository,
- the task or experiment tracker,
- meeting notes or summaries,
- key papers or background reading,
- presentations or deliverables,
- and access/contact guidance.

## When to Use This Procedure

Use this procedure when:

- a project has important links spread across several tools,
- new members frequently ask where things are,
- the team is preparing for a new semester or manager handoff,
- project artifacts have accumulated over time,
- or the group needs a clearer onboarding path.

## Required Sections

Every Artifact Hub should include the following sections.

| Section | Purpose |
| --- | --- |
| Start Here | Links to the Project Snapshot and Demo Log. |
| Code and Implementation | Repository, setup notes, branches, and implementation references. |
| Experiments and Trackers | Benchmark trackers, task boards, datasets, outputs, and performance notes. |
| Meetings and Updates | Meeting notes, weekly summaries, or relevant update folders. |
| Papers and References | Background reading, core papers, method references, and technical notes. |
| Presentations and Deliverables | Final presentations, reports, demos, draft papers, or publication materials. |
| People and Access | Who to ask for access, project context, technical questions, or management questions. |
| Maintenance Notes | Owner, backup owner, last updated date, and update triggers. |

## Step-by-Step Instructions

### Step 1: Create the file

Create a Markdown file named:

```text
ARTIFACT_HUB.md
```

Place it in the project's existing GitHub repository, wiki, shared drive folder, or official project workspace.

### Step 2: Add the first two links

The top of the file should point to:

1. `PROJECT_SNAPSHOT.md`
2. `DEMO_LOG.md`

These are the first two documents a new contributor should read.

### Step 3: Add artifact categories

Create a table with the following columns:

| Category | Artifact | Link | Purpose | Owner / Refresh Trigger |
| --- | --- | --- | --- | --- |

### Step 4: Add only useful links

Do not add every historical file. Add links that are currently useful for onboarding, project continuity, or active work. If a link is outdated but still important historically, label it as historical.

### Step 5: Identify the source of truth

For each category, make clear which artifact is the source of truth. For example:

- the repository is the source of truth for code,
- the experiment tracker is the source of truth for benchmark results,
- the Demo Log is the source of truth for plain-language project history,
- the Project Snapshot is the source of truth for high-level orientation.

### Step 6: Add access instructions

If an artifact requires access, include whom to ask. Do not include private credentials, passwords, API keys, or sensitive information.

## Update Triggers

Update the Artifact Hub when:

- a new repository, tracker, folder, paper, or presentation is created,
- a link changes,
- an artifact becomes outdated,
- a new member cannot find something important,
- the project lead or manager changes,
- the project enters a new phase,
- or a new semester begins.

## Integration into HAAG Structure

To make the Artifact Hub part of the team's normal workflow:

1. Pin the Artifact Hub link in the project Slack channel.
2. Include the Hub link in new-member welcome messages.
3. Link it from the Project Snapshot.
4. Include it in manager handoff notes.
5. Review it at the start of each semester.
6. Ask the manager or assigned owner to update it whenever a new core artifact is created.

## Definition of Done

The Artifact Hub is complete when:

- the Project Snapshot and Demo Log are linked at the top,
- the repository, tracker, notes, papers, and presentation links are easy to find,
- each link has a short purpose statement,
- source-of-truth artifacts are clearly identified,
- ownership or access guidance is visible,
- outdated links are removed or marked historical,
- and a new contributor can find the main project materials without asking another person.

## Template

```markdown
# [Project Name] Artifact Hub

Last updated: [Date]  
Primary owner: [Name / Role]  
Backup owner: [Name / Role]

## Start Here

| Artifact | Link | Purpose |
| --- | --- | --- |
| Project Snapshot | [ADD LINK] | One-page overview of the project goal, current focus, people, and starter path. |
| Demo Log | [ADD LINK] | Plain-language history of meaningful updates, decisions, and next steps. |

## Project Materials

| Category | Artifact | Link | Purpose | Owner / Refresh Trigger |
| --- | --- | --- | --- | --- |
| Code and Implementation | [Repository] | [ADD LINK] | Source of truth for code. | Update when repository, branch, or setup changes. |
| Experiments and Trackers | [Tracker] | [ADD LINK] | Source of truth for tasks, experiments, or benchmark status. | Update when tracker changes. |
| Meetings and Updates | [Meeting Notes] | [ADD LINK] | Notes or summaries from project meetings. | Update after meetings or when notes location changes. |
| Papers and References | [Reading List] | [ADD LINK] | Background materials for new contributors. | Update when core references change. |
| Presentations and Deliverables | [Presentation / Report] | [ADD LINK] | Project summaries, demos, or final deliverables. | Update when new deliverables are created. |

## People and Access

| Need | Contact / Role | Notes |
| --- | --- | --- |
| Project direction | [Project lead] | Ask about priorities and research direction. |
| Onboarding and coordination | [Manager] | Ask about Snapshot, Demo Log, and tracker. |
| Repository access | [Technical owner] | Do not share private credentials in this file. |

## Maintenance Notes

Primary owner: [Name / Role]  
Backup owner: [Name / Role]  
Review cadence: [Start of semester / after major project changes / manager handoff]
```
