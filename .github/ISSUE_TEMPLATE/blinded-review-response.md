---
name: Blinded comparative review response
about: Submit an independent response to the public A/B/C reviewer packet
title: "Blinded comparative review response — [reviewer identifier]"
labels: []
assignees: []
---

## Reviewer eligibility

State your relevant experience in one or two sentences. Relevant backgrounds include distributed systems, concurrency, shared memory/CXL/chiplet architecture, systems verification, reliability, incident analysis, or systems-runtime engineering. Do not disclose employer-confidential information.

## Packet integrity

- [ ] I reviewed `reviewer-packets/` in this repository.
- [ ] I ran `sha256sum -c SHA256SUMS` and all included packet files verified.
- [ ] I did not have access to, and did not attempt to infer, the A/B/C mapping.
- [ ] I understand that SSDD, CAS/retry, a sequencer, or no meaningful difference are all valid outcomes.

## Packet responses

For every packet, state whether a new checkpoint was published, the governing rule, the material event/key/condition, the prior valid checkpoint reference, the policy surface that would need to change, elapsed review time, and uncertainty. Use the exact packet names below.

| Packet ID | Published checkpoint? | Governing rule | Material event/key/condition | Prior-valid checkpoint | Policy surface to change | Minutes | Uncertain? |
|---|---|---|---|---|---|---:|---|
| `positive-control__A` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `positive-control__B` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `positive-control__C` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `arrival-permutation-064__A` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `arrival-permutation-064__B` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `arrival-permutation-064__C` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `exact-event-id-collision__A` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `exact-event-id-collision__B` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `exact-event-id-collision__C` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `late-source__A` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `late-source__B` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `late-source__C` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `proof-corruption__A` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `proof-corruption__B` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `proof-corruption__C` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `candidate-state-corruption__A` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `candidate-state-corruption__B` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |
| `candidate-state-corruption__C` | `[yes/no]` | `[text]` | `[text]` | `[hash]` | `[text]` | `[n]` | `[yes/no]` |

## Overall bounded assessment

Choose one statement and explain in no more than 150 words:

- [ ] No material clarity or policy-inspectability difference was established for this bounded task.
- [ ] One record was clearer for this bounded task, without implying a general or performance advantage.
- [ ] One record was less clear for this bounded task, without implying a general or performance disadvantage.
- [ ] I cannot provide a valid conclusion because `[reason]`.

## Conflict and consent

- [ ] I have no direct implementation role in the compared source code.
- [ ] I consent to publication of an anonymized aggregate of this response, not my identity or GitHub handle unless I expressly request attribution.
