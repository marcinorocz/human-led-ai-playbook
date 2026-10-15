# Sources, scope, and technical references

## Project direction

The health-first commitment is an explicit project design decision led by Marcin Orocz. Mental health, dignity, and agency take precedence over productivity. This is a normative commitment, not a measured clinical finding.

Version 2.0 refocuses the project on the human protocol. It supersedes version 1.0's technology-oriented operating instructions; the earlier version remains in Git history.

## Original inspiration

Microsoft, *The Leadership Guide: Becoming Frontier with Microsoft 365 Copilot and Agents*, copyright 2025, consulted as the supplied PDF `-MSFT-E-Book-Guide-Leadership-EN_final1pdf.pdf`.

Relevant themes include human-led work (printed pp. 7–10), clear delegation (26–28), and organizational learning (33–34). The initial edition also drew on its governance and measurement sections. The present health-first hierarchy and pause protocol are this project's own proposals, not Microsoft guidance.

The source PDF is not redistributed. No official download URL has been verified for this edition. This project has no Microsoft affiliation or endorsement.

## Technical work: refer to specialist projects

| Project | Reference purpose |
| --- | --- |
| [Cezar](https://github.com/open-mercato/cezar) | Coding-agent orchestration and workflow implementation; consult its current documentation |
| [Basal](https://github.com/rkinas/basal) | Typed decisions and classification; consult its documentation and limitations |

Their documentation was consulted during the project's initial comparison. These links do not establish integration, endorsement, clinical suitability, or compliance with this protocol. Features, defaults, and limitations can change. Other tools may be more appropriate; evaluate them against the person's needs and boundaries.

We defer deployment, model selection, security engineering, benchmarking, and orchestration details to specialist maintainers and qualified implementers.

## Claude Agent OS: explicit human tasks and decisions

[Kamil Matysik's Claude Agent OS](https://github.com/KamilMatysikAI/claude-agent-os) is an additional reference for file-based coordination, short human tasks, recommended decisions, and evidence-based completion.

We consulted its README and the author's article supplied by a reader. The article's activity figures are self-reported and have not been independently reproduced. Our [analysis](notes/claude-agent-os-human-demand.md) records the consulted README blob and separates source practices from our additions: an overall human attention budget, pending requests versus accepted commitments, and slowing the inflow of human work.

These additions extend the human protocol to version 2.1. They do not establish an integration or certify the external project's controls.

## Chorouk Malmoum: human capacity at the approval stage

Source: a LinkedIn post by [Chorouk Malmoum](https://www.linkedin.com/in/chorouk-malmoum/), supplied in full by the project owner and consulted on 2026-10-16. A canonical post URL and publication date have not been verified; the link identifies the author, not the post.

The post uses a factory analogy to argue that accelerating coding alone can move the bottleneck to review, testing, or approval. It describes shared context, workflows, and guardrails as ingredients for work across the delivery lifecycle, and discusses Port.io.

Our version 2.2 additions apply that analogy to human attention: informed approval, bounded approval queues, protected offline time, and optional observation of review effort and interruptions. These are our design proposals, not claims made by the author or evidence of health benefits.

We have not evaluated Port.io or verified the post's claims about delivery speed or product capabilities. This reference does not imply affiliation, endorsement, integration, or certification. The supplied post and its images are not redistributed.

## Optional circuit breakers and trusted-person release

Version 2.3 adds a project-owner proposal prompted by a supplied X conversation with Kamil Matysik about context switching, input methods, and personal work boundaries. A canonical thread URL has not been verified. The conversation is anecdotal; it does not validate typing-based overload detection or health outcomes.

The driver-attention comparison is a design analogy only. Our proposed check-ins, operational time/spending limits, and voluntary trusted-person release are not claimed features of Claude Agent OS, Basal, or Cezar. Implementation and enforcement must be verified separately.

For the distinction between authentication and the surrounding authorization design, consult [NIST SP 800-63B-4: Authenticators](https://pages.nist.gov/800-63-4/sp800-63b/authenticators/), consulted on 2026-10-16. NIST states that manually entered OTP outputs are not phishing-resistant. NIST is cited for authentication properties, not as an endorsement of our trusted-person agreement or as evidence that it protects mental health. The release policy, privacy boundaries, and recovery requirements are this project's proposals.

## Evidence and limits

The protocol was prepared with AI assistance and expresses practices to evaluate. It has not been validated as a mental health intervention. Do not claim that it prevents burnout, diagnoses distress, or treats illness.

No productivity, accuracy, or return figures from the original guide are guarantees for this project. Future reports must distinguish observed behavior, voluntary feedback, hypotheses, and measured results.

Author and contact: [Marcin Orocz — orocz.com/ai](https://orocz.com/ai).
