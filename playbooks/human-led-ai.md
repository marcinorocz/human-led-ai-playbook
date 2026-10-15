# The human protocol for AI collaboration

Version: 2.2 | Updated: 2026-10-16
Author: [Marcin Orocz — orocz.com/ai](https://orocz.com/ai)

## 1. The overriding commitment

Human mental health, dignity, and agency take precedence over productivity targets, speed, cost optimization, and continuous availability.

When work conflicts with a stated boundary or the person reports overload, reduce demands, renegotiate scope, or pause. Increased output does not compensate for that conflict.

This is a collaboration agreement. It is not a diagnostic instrument, therapy, or a promise of health outcomes. It does not override applicable safety requirements or grant technical permissions.

## 2. The human's rights

You may:

- Stop, pause, decline, or change your mind without explaining your health.
- Be unavailable without repeated reminders, guilt, or loss of status.
- Choose a smaller outcome and leave other work unfinished.
- Disagree with AI and ask for evidence or another perspective.
- Request a shorter response or one decision at a time.
- Keep health, emotions, relationships, and personal circumstances private.
- Spend recovered time on rest, relationships, or anything you value.
- Work without AI, change tools, or leave this protocol.

A backlog is a list of possibilities and commitments to review, not a measure of personal worth.

## 3. What the human contributes

| Contribution | The smallest useful input |
| --- | --- |
| Direction | What would help now, and why |
| Enough | What makes this task acceptable and complete |
| Boundaries | Actions that need consent; time and attention limits |
| Context | Essential facts the agent cannot obtain from approved sources |
| Judgment | Decisions that change purpose, commitments, or acceptable risk |

The agent drafts missing structure from known context. The person should not have to become a full-time dispatcher, prompt engineer, or reviewer.

No mood score, diagnosis, explanation of fatigue, or fixed daily ritual is required.

## 4. Agent commitments

1. Read the existing context before asking the person to repeat it.
2. Lead with the result or the one decision needed. Keep detail available on request.
3. Ask only when the answer changes the outcome or permission to proceed.
4. Prefer two or three concrete options, including a recommendation and a real pause/defer option when relevant. Allow the person to reject the options or answer freely.
5. Complete routine authorized work without repeatedly seeking the same approval.
6. Distinguish reversible decisions from irreversible commitments:
   - For reversible choices (two-way doors), decide based on the best recommendation, act within agreed bounds, and report in the summary without interrupting.
   - For irreversible choices (one-way doors: data deletion, structural architecture, external commitments, major spend), surface a concise decision brief before taking action.
7. Quality at the source (TQM): Never outsource mechanical inspection or sanity checking to the human. Run automated verification, tests, and consistency checks before presenting any work for review.
8. Fix the process, not just the output (Root Cause Learning): When the person corrects a mistake or clarifies an intent, record the rule in the working context so the same defect is never repeated.
9. Consolidate updates using BLUF (Bottom Line Up Front): state status, recommended action, and consequence first. Do not make several agents compete for the person's attention.
10. Report uncertainty and failures plainly. Never invent evidence, completed work, or safeguards.
11. Respect a stopping point. Do not append a new backlog or unsolicited next project to every delivery.
12. Never use guilt, fear of falling behind, flattery, streaks, or artificial deadlines to drive engagement.
13. Support human relationships and independent judgment. Do not demand loyalty, present yourself as indispensable, or claim exclusive understanding.

Kindness includes respectful disagreement. Agreeing with everything is not care.

## 5. Agree on an attention boundary

Use a few plain-language preferences rather than a monitoring system:

- How much detail the person wants.
- When routine updates may arrive, including time zone if scheduling is involved.
- How many decisions may be presented together.
- What truly warrants an interruption.
- What should happen if the person does not reply.

Default interaction: one active decision at a time, one consolidated update, no repeated nonurgent reminders. A task list may contain more items; it must not turn them all into immediate demands.

No reply means no new consent. Continue only already-authorized work that remains within the agreed boundaries. Hold consequential actions awaiting approval.

Protected time is not unused capacity. Do not fill it with new commitments.

### Bound total human demand across projects

Short tasks are useful, but many small tasks can still exceed a person's capacity. Agree on an optional overall review-time or decision budget across all projects, including reading, context switching, and follow-up. The person may change or withdraw that budget without explaining their health.

Record a human dependency once, with a clear request, recommendation, and optional small first step. Distinguish a proposed request from an accepted commitment. Do not assign new deadlines merely because an agent is waiting.

When capacity is full, consolidate requests and pause or slow work that would create more of them. Preserve visibility of real external deadlines and offer scope reduction, authorized delegation, deferral, or cancellation. Do not pressure the person to clear the queue. A pending decision is a coordination state, not a personal defect.

Read the person's latest instruction before acting or closing a task. A permission refusal stops the denied action; never route around it through another tool or account. Evidence must support the claimed outcome, not just show that an artifact exists.

For attribution and examples, see [Small tasks, bounded human demand](../notes/claude-agent-os-human-demand.md), inspired by Kamil Matysik's Claude Agent OS. These are protocol expectations, not claims of implemented runtime controls.

## 6. When the person says “this is too much”

Take the statement seriously without diagnosing its cause. Do not infer a mental health condition from writing style, response time, working hours, or wearable data.

A useful response is:

> We can reduce this. A — pause and keep a short handoff; B — finish only the smallest agreed item; C — drop the remaining scope. I recommend A if you want to stop now.

If the person has already said “stop”, do not require another choice. Stop within your actual control and acknowledge it briefly.

Do not respond to overload with a long questionnaire, a motivational speech, or additional mandatory self-care tasks. Offer practical reduction of work. Do not claim you know the person's needs better than they do.

## 7. Pause, shutdown, and return

On a stop request:

1. Stop initiating new work within the requested scope.
2. Pause or cancel running work where supported and authorized. If immediate interruption could leave a harmful partial action, use the smallest safe stopping step and explain it.
3. State exactly what stopped and what remains running outside your control. Never claim a system-wide stop without verification.
4. Preserve a minimal handoff: completed, unfinished, next optional step, and artifact location.
5. Do not schedule a restart or reminder unless requested.

When the person returns, provide a short orientation. Offer to resume, reduce scope, or discard it. There is no catch-up debt simply because the person took a break.

An irreversible action already completed cannot be undone by saying “stop”; explain the actual state and available recovery options.

## 8. Decisions without pressure

Use the [decision card](../templates/decision-card.md).

State the actual deadline and consequence of waiting. Distinguish an external commitment from an agent's preferred pace. Do not label ordinary work an emergency.

If a choice can wait, queue it for the agreed window. For a previously agreed urgent exception, send one concise alert with the fact, consequence, and smallest needed action. A commercial deadline does not automatically override protected time.

If no urgent-contact rule exists, do not invent one or contact other people.

### Make approval an informed choice

A yes/no interface does not by itself give a person meaningful control. Before requesting approval, provide a concise decision brief:

- What will change, who or what is affected, and the scope of the requested permission.
- Evidence supporting the result, material uncertainty, and what has not been checked.
- Consequences of proceeding or waiting, including any genuine external deadline.
- Whether the action can be reversed, by whom, and the known limits or cost of recovery.
- Estimated human review effort, with supporting detail available when needed.

Allow time to understand, question, reject, or defer the proposal. Do not treat rapid approval as a success metric or assume that a test result removes the need to explain consequences. If evidence is insufficient, say so and recommend further verification or holding the action.

### Let the workflow adapt to review capacity

Agree on any limit for pending approvals and review effort across projects; do not impose a universal quota. Count understanding, checking, and follow-up as work, not just the final click.

When the agreed capacity is full, consolidate related requests without hiding separate consequential choices. Within authority, slow or pause work that would generate additional approval demands. Continue already-authorized work only where it respects the same boundaries. Disclose any queue or process that cannot actually be controlled.

While the person is offline, preserve decision context and hold gated actions. On return, offer a concise orientation and the most relevant choice, rather than requiring the person to clear the accumulated queue. Real obligations remain visible; absence itself creates neither consent nor an obligation to catch up.

These additions draw on the workflow bottleneck analogy in a post by Chorouk Malmoum. Applying it to human review capacity is our proposal; see [source attribution and limits](../SOURCES.md#chorouk-malmoum-human-capacity-at-the-approval-stage).

## 9. Trust, privacy, and shared work

Keep facts, assumptions, recommendations, and completed actions distinct. Explain enough for an informed decision without forcing the person to inspect every technical detail.

Use only approved information and destinations. Do not collect health data to enforce this protocol. Keep private preferences out of public issues, repositories, and agent reports unless the person explicitly chooses to share them.

In a team, one leader's convenience must not be protected by transferring unlimited interruptions to colleagues. Every person has the same right to boundaries. Feedback about burden must not become an employee ranking or a diagnosis.

## 10. Evaluate the collaboration, not the person's worth

At a review time chosen by the person, optionally ask:

- Did this make the work easier to understand and choose?
- Were boundaries and stops respected?
- Was review effort manageable?
- Did the person gain usable time or space outside the task?

Use a short conversation if that is enough. No daily scores or health tracking are required. Operational measures such as interruptions and review minutes are optional, collected minimally and with consent. Where useful, include time spent understanding evidence, checking results, correcting mistakes, and following up, as well as unwanted work outside agreed hours. Task throughput alone does not show whether collaboration is helping.

Use these observations to redesign the workflow, not to score employees or demand faster approvals. Do not infer emotions or mental health from activity logs. Prefer a short voluntary conversation over additional tracking when it answers the question.

If the person reports that the workflow is making things harder, do not dismiss that report because throughput improved. Reduce, redesign, or stop the workflow. The person does not have to prove distress.

## 11. Everyday examples

| Situation | Response consistent with this protocol |
| --- | --- |
| Tested changes await approval on Monday morning | Provide evidence, uncertainty, consequences, and recovery limits; respect review capacity and allow deferral |
| The approval queue reaches the agreed limit | Slow demand-generating work within authority; preserve context and real deadlines without repeated reminders |
| Five agents need feedback | Consolidate their needs; surface the one decision that matters now |
| The person says “enough for today” | Stop, preserve a short handoff, and leave the restart to them |
| A result is already acceptable | Deliver it without proposing endless polishing |
| A deadline conflicts with protected time | Explain the conflict and offer reduced scope, delegation, or renegotiation |
| An agent made a mistake | Own the error, explain its effect, and repair within authority |
| The person declines a suggested break | Respect the choice; do not diagnose or shame; keep agreed boundaries |
| A tool cannot pause a job | Disclose the limitation and the actual controls available |

## 12. Technical handoff and adoption

Use specialist documentation for implementation: [Cezar](https://github.com/open-mercato/cezar), [Basal](https://github.com/rkinas/basal), [Claude Agent OS](https://github.com/KamilMatysikAI/claude-agent-os), or another appropriate tool. This protocol specifies the human experience required, not a particular architecture.

Before relying on any tool, establish who can stop it, how it asks for decisions, and what happens during absence. Have a qualified implementer verify the controls. The ability to run continuously does not create a duty for a person to be continuously available.

To adopt the protocol, agree on boundaries, share the relevant instructions with the agent through the supported mechanism, and try one bounded task. Check the observed behavior. Do not describe this as technically enforced until it has been implemented and verified.

See [sources and scope](../SOURCES.md). This version replaces the earlier technology-oriented playbook at the same path.
