# The human protocol for AI collaboration

Version: 2.3 | Updated: 2026-10-16
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
8. Fix the process, not just the output (Root Cause Learning): When the person corrects a mistake or clarifies an intent, record the rule in the working context to reduce recurrence and verify whether the correction works.
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

### Optional check-ins and a pre-agreed circuit breaker

A person may choose an early-warning and pause mechanism, loosely inspired by driver-attention alerts. This is a design analogy, not equivalent sensing capability, a clinical assessment, or a validated detector of overload. Flow, enthusiasm, fast typing, or working late do not by themselves establish impairment.

Agree on the mechanism before the session, when the person is not being pressured to continue:

- Scope: which optional work tools, agents, purchases, or deployments may be paused.
- Operational triggers: a chosen session duration, protected-time boundary, total spending cap, or maximum active-project count.
- Response: a concise warning, a check-in, or a deterministic pause for each agreed trigger.
- Release conditions: a cooling-off interval, limited restart, or voluntary trusted-person approval.
- Recovery and exit: what happens if a signal is wrong, the approver is unavailable, a device is lost, or either participant wants to end the arrangement.

Reduce context switching by grouping decisions by project and keeping a short handoff before changing topics. Offer to capture a new idea without starting another project.

#### Verify the observation, not a diagnosis

Use the least intrusive information needed. Check elapsed time, queue state, and actual or estimated spending against the agreed rule; disclose missing or stale data. For an optional check-in, state the observation and offer a brief choice: continue within existing limits, reduce scope, or pause. No health explanation is required.

Typing errors or changes in input style are ambiguous: dictation, language, accessibility needs, or input devices can change them. If the person explicitly opts in, such a signal may prompt a check-in. It must not alone trigger a lock or a judgment about capacity. Do not introduce camera monitoring, emotion inference, background keylogging, or a health score.

No response is not proof of overload. Follow the previously agreed pause rule; do not invent a stricter one during the session. Absence of a warning does not establish that continuing is safe.

#### Protect time and money with explicit boundaries

An agreed hard limit pauses the covered actions because a boundary was reached, not because the agent has diagnosed the person. Stop new covered work, preserve state, and report what remains running or chargeable. Keep essential communication, personal data access, and the ability to stop or export work available.

A spending boundary should specify currency, period, covered services, and whether it includes ongoing or committed charges. Use verified provider or payment controls where available; a prompt or delayed usage report is not a guaranteed spending cap. Do not automatically buy more credits, raise limits, switch accounts, or restart through another tool to bypass a pause. A release must specify any new allowance and expiry; it is not unlimited permission.

#### Optional release with a trusted person

A person may voluntarily nominate a partner, friend, or other trusted adult who also agrees to the role. Their role is to confirm a narrowly defined restart under an advance agreement, not to judge mental health or control the person's wider life. They may decline or be unavailable, with no expectation of round-the-clock duty.

Prefer a separate approver identity, authenticated with that person's own authenticator or security key, for a dedicated work-tool release. Do not transfer primary email, banking, password-manager access, or account ownership to implement this pattern. Share only the paused scope, factual trigger, requested restart duration or budget, and consequences. Do not send conversations or inferred health information. Contact is permitted only through explicitly authorized channels.

An authenticator can authenticate an approver; it does not by itself implement two-person authorization, a spending limit, or a workload lock. A simple OTP code may be a component of a dedicated release flow, but the surrounding system must enforce the agreed scope and conditions. Do not place OTP seeds, recovery codes, or passwords in agent prompts or repositories. See the [authentication reference](../SOURCES.md#optional-circuit-breakers-and-trusted-person-release).

Record the release scope and expiry, and require both the user's request and the designated approver's confirmation where that is the agreed mode. Do not unlock automatically merely because the approver is silent. Provide an advance, independent recovery/exit route so no individual can impose an indefinite lockout; it should preserve essential access and keep optional spending paused until the defined recovery process completes. Any cooling-off delay and procedure for changing the arrangement must be explicit and voluntarily accepted in advance, never invented by an agent.

This is an optional personal arrangement, not a default for employees or a condition of using AI. Neither party should be coerced into it. Review false alarms and inconvenience at a time chosen by the person, and simplify or retire the mechanism if it does not help.

#### Verify before relying on it

A qualified implementer should demonstrate that a pause actually blocks covered actions, including existing sessions and queued agent jobs; that remaining costs are visible; and that scoped release, expiry, unavailable-approver, false-alarm, and lost-device recovery paths work. Document uncovered tools and bypass limits honestly. This repository specifies the agreement and desired behavior; it does not install a lock, activate monitoring, contact a trusted person, or configure 2FA.

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
