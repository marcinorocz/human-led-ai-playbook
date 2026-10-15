# Small tasks, bounded human demand

Inspired by [Kamil Matysik's Claude Agent OS](https://github.com/KamilMatysikAI/claude-agent-os).
Reviewed: 2026-10-15. This is a human-protocol analysis, not a runtime audit or integration.

## What the project contributes

Claude Agent OS describes a file-based system in which a CEO role plans and specialist roles execute. Its README makes human work explicit: short tasks, a small first step, and decisions with recommendations. It also describes evidence required for completion, respect for permission refusals, and reading the owner's latest note before acting or closing work.

These are useful design ideas for making collaboration understandable and reducing the effort of getting started. Implementation belongs with the project's maintainers.

## Source and evidence boundary

Sources consulted:
- The author's article supplied by a reader, beginning “1 490 zadań w 56 dni”. A canonical article URL was not supplied.
- [Repository README](https://github.com/KamilMatysikAI/claude-agent-os/blob/master/README.md), blob `4c486b56155591c782f58d0a82b3966cb3837de4`.

The article reports 1,490 completed agent tasks, 368 completed human tasks, 262 decisions, and 178 open human tasks over 56 days. These are the author's reported figures, not independently reproduced results. Task counts alone do not establish quality, net time saved, or health outcomes. We do not infer the author's mental state from the backlog.

## What we adopt, and what we add

| Source idea | Human-first adaptation |
| --- | --- |
| Short human tasks with a 1–3 minute starting step | Offer an easy start when useful. Treat the duration as an estimate, not a promise or a quota. |
| Waiting for a human becomes an explicit task | Record the dependency once. A recorded request is not automatically an accepted commitment or a new deadline. |
| Decisions include a recommendation | Include evidence, consequences, human effort, and the option to defer, decline, or request another proposal. |
| Completion requires evidence | Show evidence that matches the claimed outcome. A file existing is not proof that the outcome is correct. |
| The latest owner note matters | Read it before acting and before closing. Respect a later pause, scope change, or request to recheck within the applicable instruction hierarchy. |
| Permission refusal means stop | Stop the denied action. Do not switch tools, accounts, or infrastructure to bypass the refusal. Report the minimum needed to resolve it. |
| Repeated agent failure becomes visible | Report a bounded exception with attempts and a recommendation. Do not automatically transfer troubleshooting labor to the human. |

## Our addition: a shared human attention budget

A system can generate individually small requests faster than a person can reasonably handle them. Fifteen minutes per task is a size limit, not a limit on total demand.

Set an optional, person-chosen budget across all projects for review time and decisions. Include reading, context switching, corrections, and follow-up in the estimate. A per-project limit does not protect someone who owns many projects.

When the agreed capacity is full:
1. Consolidate duplicates and related requests.
2. Keep new requests pending rather than marking them accepted or overdue.
3. Pause or slow work that predictably produces more human requests.
4. Present the trade-off at the next agreed review window: reduce scope, delegate with permission, defer, or stop.
5. Keep genuinely time-sensitive obligations visible with their actual consequences, without inventing urgency or implying that a break erased an external deadline.

Already-authorized independent work may continue only within the agreed scope, cost, and pause rules. Never assume that an empty calendar slot is available capacity.

## A practical example

Five projects each generate a “quick” review. Instead of delivering five notifications and assigning five deadlines, the coordinator groups the requests, estimates the combined effort, and proposes the single decision that matters now. The others remain pending. If the person has already said stop, preserve a handoff instead of asking another question.

A pending human decision is a coordination state, not a personal defect.

## Scope

These additions are our proposed protocol practices; they are not claims about controls already implemented in Claude Agent OS. They do not diagnose overload, replace consent, or require health tracking.

See the [human protocol](../playbooks/human-led-ai.md), [task brief](../templates/task-brief.md), and [decision card](../templates/decision-card.md).
Author and contact: [Marcin Orocz — orocz.com/ai](https://orocz.com/ai).
