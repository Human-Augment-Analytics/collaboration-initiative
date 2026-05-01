# Management & Leadership Final Report

**Initiative Title:** Project Context Transfer Package for HAAG Research Groups  
**Student:** Vidushi Singla  
**Role:** Management & Leadership Manager, Vector Quantization Research Project  
**Program Context:** Georgia Tech HAAG  
**Term:** Spring 2026

## Initiative Scope

My initiative focuses on improving onboarding, continuity, and context transfer across HAAG research groups. Many HAAG projects are technically complex, fast-moving, and distributed across Slack conversations, meeting notes, GitHub repositories, experiment trackers, papers, and informal explanations. When a new or returning contributor joins a project, they often need to reconstruct the project from scattered information before they can understand the goal, recent progress, current priorities, and where they should begin. This creates friction for the new contributor and repeated explanation work for current members.

To address this, I designed a reusable **Project Context Transfer Package** that any HAAG research group can adopt. The package has three lightweight components: a **Project Snapshot**, a **Demo Log**, and an **Artifact Hub**. The Project Snapshot gives a one-page overview of the project. The Demo Log captures meaningful project updates, decisions, experiments, and next steps in plain language. The Artifact Hub serves as a single index for important links such as repositories, trackers, notes, papers, and presentations. I used the Vector Quantization group as the pilot/example because that project clearly showed the need for better context transfer, but the procedures are written so future HAAG research groups can reproduce the process.

## Evidence of Alignment with HAAG Goals

This initiative aligns with HAAG's goals because it supports applied research education, leadership and project management development, cross-disciplinary collaboration, and research acceleration. HAAG research groups rely on students, managers, researchers, computational advisors, and faculty working together across semesters. That structure creates an important management challenge: project knowledge must survive member turnover and remain understandable to people who were not present for earlier conversations.

The Vector Quantization group made this need visible. The group is working on a technically dense research problem: making large-scale embedding search faster and cheaper through vector quantization while preserving retrieval quality. The project includes method comparisons such as PQ, OPQ, SQ, SAQ, and RabitQ; codebook and bit-allocation work; GPU and CPU benchmarking; retrieval-quality tradeoffs; theory discussions; and publication planning. The team had real technical progress, but the context was distributed across multiple places. A newcomer could see individual artifacts, but still not understand the full project story: what has already been tested, why certain decisions were made, which links matter most, and what the current priority is.

This initiative was also informed by observations from management work: preparing weekly trackers, reading meeting updates, reviewing Slack-style project discussions, and translating technical updates into management-facing summaries. These observations showed that the issue was not a lack of information. The issue was that information was not packaged in a way that helped someone ramp up quickly. The final presentation for this initiative also captured an important continuity signal: only 2 of 13 contributors from the previous semester returned. While not every departure can be attributed to onboarding, the pattern reinforced the need for better project memory, clearer starting points, and more repeatable context transfer.

The initiative also complements existing HAAG-wide recruitment and outreach work. Recruitment events, email templates, and surveys can help students learn that HAAG exists and understand what projects are available. My initiative begins after that point: once a student is interested in or assigned to a research group, the Context Transfer Package helps them understand the specific project and become useful faster.

## Procedures Generated

I generated three procedures. Together, they explain how a HAAG research group can create and maintain a lightweight context-transfer system without adding unnecessary bureaucracy.

| Procedure | Purpose | Primary Audience | Link |
| --- | --- | --- | --- |
| Project Snapshot Procedure | Explains how to create and maintain a one-page project overview for new and returning contributors. | Project managers, project leads, current researchers, new contributors. | [ADD LINK: 02_project_snapshot_procedure.md] |
| Demo Log Procedure | Explains how to capture meaningful project updates, experiments, decisions, blockers, and next steps in a running plain-language log. | Project managers, project leads, researchers contributing updates. | [ADD LINK: 03_demo_log_procedure.md] |
| Artifact Hub Procedure | Explains how to maintain one index of important project materials without duplicating content across tools. | Project managers, project leads, current researchers, new contributors, future managers. | [ADD LINK: 04_artifact_hub_procedure.md] |

I also created a short pilot feedback form that can be used to test whether the package is actually useful to a new or less-familiar contributor.

| Supporting File | Purpose | Link |
| --- | --- | --- |
| Pilot Feedback Form | Measures whether a participant can understand the project goal, find key artifacts, identify a recent update, and name a starter next step after reviewing the materials. | [ADD LINK: 05_pilot_feedback_form.md] |

## Purpose of the Project Snapshot Procedure

The Project Snapshot Procedure creates a repeatable way for any HAAG research group to summarize its current project context in one page. The Snapshot is meant to answer the questions a new contributor usually has first: What is the project trying to do? What is the current focus? Who is involved? What should I read first? Where are the important artifacts? What is one reasonable way to begin contributing?

This procedure is intentionally lightweight. It does not require a full onboarding course, a long wiki, or a manager spending hours rewriting technical history. A first version can be created in about 30-45 minutes and then updated when the project direction changes. The Snapshot becomes the first document a new contributor reads and the first link a current member can share when someone asks for context.

## Purpose of the Demo Log Procedure

The Demo Log Procedure creates a running project memory. Many research decisions happen in meetings, Slack threads, experiment updates, or informal conversations. Over time, those decisions become hard to reconstruct. The Demo Log turns meaningful updates into short entries that explain what changed, why it matters, where the evidence lives, and what should happen next.

The Demo Log is not a meeting transcript or an experiment tracker. It is a plain-language bridge between technical artifacts and project understanding. It helps new contributors read the most recent entries and understand the current direction without needing to ask someone to retell the last several weeks of project history.

## Purpose of the Artifact Hub Procedure

The Artifact Hub Procedure creates a single index for important project materials. HAAG research groups often use several tools at once: GitHub, Slack, Teams, project trackers, meeting notes, papers, datasets, slides, and reports. The Hub does not replace those tools. It simply points people to the right source of truth.

This is important because scattered links create avoidable friction. A new contributor should not need to search Slack history or ask multiple people to find the repository, benchmark tracker, meeting notes, reference papers, or final presentation. The Artifact Hub provides a clear starting point and helps managers maintain continuity when teams change across semesters.

## How the Procedures Integrate into HAAG Workflows

The procedures are designed to fit into work HAAG teams are already doing. They do not require a new recurring meeting or a separate administrative process. The Project Snapshot, Demo Log, and Artifact Hub should live in the project's existing GitHub repository, wiki, shared drive folder, or other official project workspace. The project manager or project lead should own the first version, and a backup owner should be named so the materials do not become stale when roles change.

The package can be integrated into the normal project workflow in four simple ways. First, the Artifact Hub link should be pinned in the project Slack channel or included in the project welcome message. Second, new contributors should be asked to read the Project Snapshot and the last few Demo Log entries before requesting a full onboarding conversation. Third, managers should check once per week or after each research meeting whether any meaningful project update should be added to the Demo Log. Fourth, the Snapshot and Hub should be reviewed at the start of each semester or when there is a major change in direction.

This structure creates a practical enforcement mechanism without making the process heavy. The expectation is not that every message becomes documentation. The expectation is that meaningful context is captured once, linked clearly, and reused whenever new members need it.

## Pilot Plan

The first pilot should be small. A project manager can select one new contributor, returning contributor, or current member who is less familiar with the latest project direction. The participant should review the Project Snapshot, Demo Log, and Artifact Hub for 20-30 minutes and then complete the pilot feedback form.

The pilot should measure four practical outcomes: whether the participant can explain the project goal in plain language, whether they can find the key artifacts, whether they can identify one recent meaningful update, and whether they can name a reasonable starter task or question for the project lead. The feedback should then be used to simplify unclear sections, remove unnecessary details, and add missing links.

The pilot does not need to prove that the package solves every onboarding problem. Its purpose is to test whether the materials reduce the first layer of confusion and make project context easier to find.

## Sustainability and Maintenance

The long-term success of this initiative depends on keeping the package short and easy to update. If the documents become too detailed, they will become stale. If the documents are too vague, they will not help new contributors. The procedures therefore emphasize short updates, clear ownership, and links to source materials rather than duplication.

Each project should assign one primary owner and one backup owner. In most groups, the manager can own the upkeep because this fits naturally with weekly tracking and operations work. The project lead or a senior researcher should help validate technical accuracy. The Snapshot should be reviewed when project direction changes. The Demo Log should be updated only when meaningful updates occur. The Artifact Hub should be updated whenever a core link changes or a new artifact becomes important.

This approach makes the initiative realistic for HAAG because it asks for small, repeatable actions rather than a large process redesign.

## Project Management Reflection

This initiative taught me that leadership in a research environment is often about reducing friction in systems that already exist. At the beginning, I considered broader onboarding ideas such as a buddy ramp-up process and a more structured demo protocol. Those ideas could be useful, but they required more coordination, more management buy-in, and more ongoing effort than was realistic for one semester.

As I worked more closely with the Vector Quantization project, the more immediate problem became clearer. The team did not need more information. It needed a better way to package and transfer the information it already had. That shift changed the initiative from a large process redesign into a smaller, more practical system: a Project Snapshot, Demo Log, and Artifact Hub.

The biggest management lesson was scope discipline. A good intervention is not always the biggest possible solution. It is the smallest useful solution that people can actually adopt. In a fast-moving research group, a lightweight process that gets used is more valuable than a perfect process that no one maintains.

## Final Takeaway

HAAG research groups produce a large amount of useful knowledge, but that knowledge can become difficult to access when it is spread across tools, meetings, Slack threads, and informal explanations. The Project Context Transfer Package gives teams a simple way to preserve project memory, reduce repeated onboarding effort, and help new contributors begin with more confidence.

The Vector Quantization group served as the example, but the procedures are intentionally reusable. Any HAAG research group can create a Project Snapshot, maintain a Demo Log, and organize an Artifact Hub with limited additional effort. The result is a more sustainable way to transfer context across semesters, contributors, and project stages.
