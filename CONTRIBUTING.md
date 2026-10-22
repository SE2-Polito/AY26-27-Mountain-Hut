# Contributing and requesting clarification

This repository contains the shared requirements for the Mountain Hut course project. All 16 student teams use the same published stories and clarification process. Teaching staff act as the product owner and maintain the specification.

## Where to start

Read the [story index](README.md) and the relevant files in [stories](stories/). The index lists stories by decreasing business value. This order expresses business priority.

Use the requirements version or baseline assigned by teaching staff. Include its tag or commit identifier in a clarification request when available.

Keep implementation code, technical tasks and team-specific bugs in your team's project repository. Use this repository for questions about the shared requirements, inconsistencies and proposed corrections.

## Before opening an issue

1. Read the story, its Notes and its Clarifications section.
2. Search both open and closed issues using the story ID and relevant keywords.
3. If an existing issue covers your question, add any missing information there rather than opening a duplicate.

Ask questions here when the answer could affect how teams interpret, implement or test a requirement. A question raised by one team may help every team.

## Opening a clarification request

Choose **New issue**, then **Requirement clarification**.

- Use a title such as `[Clarification] MH-06: Meaning of the 48-hour change window`.
- Identify your team and the primary story ID. Mention related stories when needed.
- Quote the exact wording that is unclear and describe the question precisely.
- Include a short example if it helps distinguish possible interpretations.
- Optionally propose an interpretation.

Open one issue per distinct question. A single question involving several related stories can stay in one issue.

Keep questions about requirements separate from preferences about frameworks, architecture or tools. Raise implementation constraints here only when they affect the meaning or feasibility of a shared requirement.

## Discussion and decisions

Students may offer interpretations and examples. Teaching staff make the final requirements decision. An unanswered question or a suggested interpretation does not establish a requirement.

Teaching staff use this process:

1. Review the question and ask for additional context if necessary.
2. Post an explicit decision, including the affected story IDs.
3. Update the story's Clarifications section with the decision and a link to the issue. Update other affected wording when necessary.
4. Link the corresponding commit or pull request in the issue, then close it.

The published story files contain the current agreed requirements. Issue threads provide the reasoning and discussion history. If an issue answer and a story disagree, flag the inconsistency for staff to reconcile.

For a duplicate, staff link the existing issue and close the duplicate. For a request that needs no specification change, staff explain why before closing it. If a closed issue leaves part of the question unresolved, add a comment explaining what remains unclear.

While waiting for a decision, continue work that does not depend on the answer. Record any provisional assumption in the issue and in your team's work so it can be reviewed when staff respond.

## Changes during a sprint

A clarification explains an existing requirement. A scope change adds, removes or materially changes required behaviour. Staff should identify scope changes explicitly and announce which teams, sprint or requirements baseline they affect, including any effect on assessment or deadlines.

Do not infer a new assignment from an unresolved issue or a proposed change. Follow the baseline and subsequent updates explicitly assigned by teaching staff.

Check the shared repository regularly during the sprint. Staff decisions apply consistently across teams. If a requirements answer reaches you through another channel, ask for it to be recorded here so everyone can find it.

## Working together

Keep discussions respectful and specific. Discuss the requirement and its consequences, and avoid posting other teams' solution code in this shared repository.
