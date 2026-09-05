# Seeded-Container Pilot Review

Use this framework when evidence returns from a bootstrap in which GPT can draw selectively from an existing container, conversation history, or other user-authorized context.

This is a public design document. Never place participant names, raw container material, credentials, private repository contents, screenshots containing private information, or participant-specific notes here. Preserve only generalized findings.

## Working hypothesis

A seeded-container bootstrap can convert existing context into person-owned, durable, correctable state:

1. GPT observes user-authorized source context.
2. GPT proposes an attention map: one to three trajectories that presently demand the person's attention.
3. The person confirms, rejects, or corrects the interpretation.
4. GPT writes only confirmed, source-safe state to the person's private Git repository.
5. The state expands over time through ordinary work and correction.
6. A dashboard may provide perception when the state is mature enough and the person wants it.
7. A calendar may provide temporal return when genuine dates exist.
8. A relationship channel may carry an approved, bounded representation when a real recipient and purpose exist.

This is a hypothesis to test, not permission to import everything or require every capability.

## Design observations

### Conversion, not collection

The valuable operation is not moving a container into Git. It is converting latent context into an explicit state the person can inspect, correct, own, and carry forward.

A useful bootstrap should reduce cognitive burden. A large unfiltered data dump fails even if it is technically complete.

### Attention is the organizing principle

The initial trajectories should reflect what most demands the person's attention, not an arbitrary quota or a list of everything known. One is enough to begin. Three may be a useful starting limit, but it is a pacing device, not a definition of the person.

### Two bootstrap extremes

A participant with little usable prior context may need a help-first path: solve the immediate problem, then preserve continuity.

A participant with a rich seeded container may move quickly: selectively interpret existing context, confirm the important trajectories, and establish durable state.

The public system should support both without making the first participant feel behind or the second repeat what GPT already knows.

### State, projections, and relationships have different jobs

- The private repository provides durable, inspectable, versioned memory and correction.
- A dashboard provides present-tense perception across living trajectories.
- A calendar provides temporal return.
- A relationship channel carries only an authorized representation for a declared purpose and recipient.

These are separate capabilities. None should be a mandatory rung on one ladder.

A dashboard should not appear merely because a numeric threshold was reached. It should appear when the state is coherent enough that a visual surface will lower burden and support decisions.

### The repository is not the person or the agent

The private repository is one component of a human–AI operating configuration. The person, GPT runtime, tools, durable state, projections, relationship channels, and protected source systems remain distinguishable.

This prevents loss of one runtime or interface from being confused with loss of the person's state, and prevents a stored representation from being treated as the person.

### Personal, organizational, and relationship truth must remain separate

The person's private repository owns the person's state.

An organizational system owns shared operational truth.

A relationship representation carries only what its purpose, audience, and authorization permit.

A dashboard may combine authorized projections from more than one source, but convenience must not silently turn the personal repository into a shadow organizational database, the organizational system into an owner of the person's life, or a relationship channel into blanket access.

### Authority without unauthorized action

The intended sequence is:

> observe → interpret → propose → human authorizes or corrects → implement → verify → preserve provenance and correctability

Access to context or a repository is not authority to decide what matters, expose private material, or make consequential commitments.

### The trusted helper needs an exit condition

Assisted setup succeeds when the participant can understand what exists, correct GPT, resume after interruption, and continue without the helper operating the system for them.

### A public bootstrap should absorb repeated prompting

If every seeded participant needs a long custom activation prompt, the doctrine is incomplete. Repeated instructions discovered through pilots should move into the public bootstrap so future activation becomes shorter, safer, and easier to understand.

### This may become a federated network

Person-owned sovereign-state repositories can act as independent nodes. They may share deliberately authorized projections without surrendering ownership of their underlying state. Interoperability should preserve consent, provenance, reversibility, clear source ownership, and provider substitutability.

## Version 0.2 design disposition

Generalized evidence from assisted setup, live state maintenance, dashboard correction, runtime interruption, and one bounded relationship implementation supports these changes for further testing:

- keep help-first and selective seeded import paths;
- begin with one to three trajectories rather than requiring three;
- make the private repository explicit state machinery rather than the person or complete agent;
- make dashboard, calendar, and relationship channels independent optional capabilities;
- use qualitative usefulness gates instead of numeric dashboard readiness;
- preserve a human-readable resume point across devices, conversations, and compatible runtimes;
- define a trusted-helper access review and exit;
- require purpose-specific, source-safe, inspectable, correctable, expiring, and revocable relationship representations;
- verify real permissions and return paths with harmless tests;
- carry recurring instructions in public doctrine and acceptance tests rather than private custom prompts.

These are design revisions prepared for the next pilot. They are not proof that the system fits every person, ability, device, or environment.

## Questions for returned pilot evidence

1. Did GPT use authorized source context without making the participant repeat it?
2. Did GPT distinguish source material from established, confirmed state?
3. Did its proposed attention map feel accurate, useful, and non-imposing?
4. Did the participant have a clear opportunity to confirm, reject, and correct the interpretation?
5. Did GPT select useful state rather than over-importing?
6. Did it preserve personal, organizational, and relationship boundaries?
7. Did direct GitHub access work without requiring a command line or gh CLI?
8. Could the system resume after a device, conversation, or compatible runtime change?
9. Did updates preserve provenance and make correction easy?
10. Did dashboard readiness depend on coherence and usefulness rather than trajectory count?
11. Did calendar entries preserve their real meanings?
12. If a relationship channel was used, could the person inspect, correct, expire, and withdraw the exact representation?
13. Could the participant explain the repository's purpose and continue without the setup helper?
14. Did the process reduce cognitive burden?

## Evidence discipline

For each generalized finding, label the claim:

- Observation: directly seen in the pilot.
- Participant report: stated by the participant.
- Inference: our interpretation of the evidence.
- Design implication: a possible change suggested by the evidence.
- Confirmed correction: an interpretation the participant explicitly changed.

Keep these categories separate. Do not convert an inference into participant truth.

Do not store raw participant data in this public repository. Record only the smallest generalized description needed to improve the public system.

## Further evidence needed

Test whether:

- one living trajectory is enough to establish useful continuity;
- a nontechnical person can resume on another device or in a fresh compatible GPT;
- the participant can distinguish the repository, runtime, dashboard, and relationship channel;
- helper access is actually reduced after setup;
- optional capabilities remain independent in practice;
- a relationship representation can move through approval, use, correction, expiry, and withdrawal without exposing private state;
- the participant can continue without a long custom activation prompt.

A later pilot may disconfirm any current revision. Preserve that result. The goal is a system that responds to evidence, not one that merely confirms its authors' expectations.
