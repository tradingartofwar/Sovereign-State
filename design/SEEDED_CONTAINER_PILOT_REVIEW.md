# Seeded-Container Pilot Review

Use this framework when evidence returns from a bootstrap in which GPT can draw selectively from an existing container, conversation history, or other user-authorized context.

This is a public design document. Never place participant names, raw container material, credentials, private repository contents, screenshots containing private information, or participant-specific notes here. Preserve only generalized findings.

## Working hypothesis

A seeded-container bootstrap can convert existing context into person-owned, durable, correctable state:

1. GPT observes user-authorized source context.
2. GPT proposes an attention map: the few trajectories that presently demand the person's attention.
3. The person confirms, rejects, or corrects the interpretation.
4. GPT writes only confirmed, source-safe state to the person's private Git repository.
5. The state expands over time through ordinary work and correction.
6. A dashboard provides perception when the state is mature enough.
7. A calendar provides an honest path of return to appointments, deadlines, plans, reviews, routines, and possibilities.

This is a hypothesis to test, not permission to import everything.

## Design observations to examine

### Conversion, not collection

The valuable operation is not moving a container into Git. It is converting latent context into an explicit state the person can inspect, correct, own, and carry forward.

A useful bootstrap should reduce cognitive burden. A large unfiltered data dump fails even if it is technically complete.

### Attention is the organizing principle

The initial trajectories should reflect what most demands the person's attention, not an arbitrary quota or a list of everything known. Three may be a useful starting size, but it is a pacing device, not a definition of the person.

### Two bootstrap extremes

A participant with little usable prior context may need a help-first path: solve the immediate problem, then preserve continuity.

A participant with a rich seeded container may move quickly: selectively interpret existing context, confirm the important trajectories, and establish durable state.

The public system should support both without making the first participant feel behind or the second repeat what GPT already knows.

### Git, dashboard, and calendar have different jobs

- Git provides durable, inspectable, versioned memory and correction.
- The dashboard provides present-tense perception across living trajectories.
- The calendar provides temporal return.

A dashboard should not appear merely because a numeric threshold was reached. It should appear when the state is coherent enough that a visual surface will lower burden and support decisions.

### Personal and organizational truth must remain separate

The person's private repository owns the person's state.

An organizational system owns shared operational truth.

A dashboard may combine authorized projections from both, but convenience must not silently turn the personal repository into a shadow organizational database or the organizational system into an owner of the person's life.

### Authority without unauthorized action

The intended sequence is:

> observe → interpret → propose → human authorizes or corrects → implement → Git preserves provenance and correctability

Access to context or a repository is not authority to decide what matters, expose private material, or make consequential commitments.

### The trusted helper needs an exit condition

Assisted setup succeeds when the participant can understand what exists, correct GPT, resume after interruption, and continue without the helper operating the system for them.

### A public bootstrap should absorb repeated prompting

If every seeded participant needs a long custom activation prompt, the doctrine is incomplete. Repeated instructions discovered through pilots should move into the public bootstrap so future activation becomes shorter, safer, and easier to understand.

### This may become a federated network

Person-owned sovereign-state repositories can act as independent nodes. They may share deliberately authorized projections without surrendering ownership of their underlying state. Interoperability should preserve consent, provenance, reversibility, and clear source ownership.

## Questions for returned pilot evidence

Review the pilot with these questions:

1. Did GPT use the authorized source context, or unnecessarily ask the participant to repeat it?
2. Did GPT distinguish source material from established, confirmed state?
3. Did its proposed attention map feel accurate, useful, and non-imposing?
4. Did the participant have a clear opportunity to confirm, reject, and correct the interpretation?
5. Did GPT select useful state, or over-import and create a data dump?
6. Did it preserve the boundary between personal state and organizational or shared operational truth?
7. Did direct GitHub writing work without requiring a command line or `gh` CLI?
8. Did updates preserve provenance and make correction easy?
9. Did dashboard readiness depend on coherence and usefulness rather than trajectory count alone?
10. Did calendar entries preserve their real meanings rather than treating every date as a fixed commitment?
11. Could the participant explain the private repository's purpose and continue without the setup helper?
12. Did the process reduce cognitive burden?

## Evidence discipline

For each generalized finding, label the claim:

- **Observation:** directly seen in the pilot.
- **Participant report:** stated by the participant.
- **Inference:** our interpretation of the evidence.
- **Design implication:** a possible change suggested by the evidence.
- **Confirmed correction:** an interpretation the participant explicitly changed.

Keep these categories separate. Do not convert an inference into participant truth.

Do not store raw participant data in this public repository. Record only the smallest generalized description needed to improve the public system.

## Candidate changes after evidence

Consider these only after pilot evidence supports them:

- add an explicit seeded-container or import path to the bootstrap;
- define the personal-versus-organizational source boundary;
- add a trusted-helper exit test;
- replace numeric dashboard readiness with a qualitative rubric;
- shorten the activation prompt by moving repeated instructions into doctrine;
- add acceptance tests for selective import, correction, provenance, and participant independence.

A pilot can also disconfirm these ideas. Preserve that result. The goal is a system that responds to evidence, not one that merely confirms its authors' expectations.
