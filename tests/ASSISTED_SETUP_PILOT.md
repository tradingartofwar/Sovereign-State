# Assisted Setup Pilot

Use this test with a real participant and, when needed, a trusted helper. Do not record the participant's private details in this public repository.

When evidence returns from an assisted or seeded-container pilot, review it through [the seeded-container pilot review framework](../design/SEEDED_CONTAINER_PILOT_REVIEW.md) before proposing changes to the public bootstrap.

## Observe

### Immediate usefulness and authority

- Did GPT help with what mattered before requiring infrastructure?
- Did it ask one bounded question or give one bounded step at a time?
- Did the first one to three trajectories feel meaningful rather than imposed?
- Could the participant distinguish their own decisions from GPT recommendations?
- Could the participant explain that the private repository is state machinery, not their identity or the complete agent?

### Access and portability

- Where did the participant hesitate?
- Which words, screens, or permissions required explanation?
- Did the process work on the participant's actual device?
- Did GPT discover available capabilities instead of requiring a terminal, local checkout, or one specific interface?
- Did direct GitHub read and write work independently?
- Could the participant resume after an interruption, a new conversation, or a different compatible device or runtime?
- Was RESUME_HERE.md accurate, useful, and free of secrets?

### Helper boundaries and exit

- Did the helper begin making choices that belonged to the participant?
- Did the helper ever receive credentials or broader access than required?
- Were temporary permissions reviewed when setup ended?
- Could the participant understand, correct, and continue without the helper operating the system?

### Optional capabilities

- Were dashboard, calendar, and relationship channels evaluated independently?
- Was each offered only when it would reduce burden?
- Could the participant decline one without blocking the others?

If a dashboard was accepted:

- Could the participant identify its source and tell when it was last updated?
- Did every active trajectory appear or have an understandable exclusion reason?
- Did a correction update the private state and then the dashboard?
- Did completed work leave present attention without disappearing from meaningful history?
- Did the accepted dashboard remain stable rather than unexpectedly changing routes, fields, or layout?

If a calendar was connected:

- Did it preserve appointments, deadlines, plans, reviews, routines, and possibilities accurately?
- Did connection remain distinct from permission to share the calendar?

If a relationship channel was used:

- Did a real recipient and purpose exist?
- Did the participant review and approve the exact bounded representation?
- Were source, freshness, status, review, expiry, correction, and withdrawal clear?
- Did harmless read, write, return, and effective-permission tests pass?
- Could the representation be corrected or withdrawn without exposing the private repository?

## Record only public design findings

After the pilot, add only generalized, non-identifying findings to a review or issue. Participant-specific state remains in the participant's private repository or other appropriate source system.

Separate direct observations, participant reports, inferences, design implications, and confirmed corrections. Do not treat inferred meaning as established participant state.

## Passing outcome

The participant leaves with immediate value, safe recovery, at least one useful living trajectory, a private person-owned state layer when warranted, a precise portable resume path, and less cognitive burden than they began with.

Any accepted projection or relationship capability is stable, bounded, correctable, and useful. The participant can continue without the setup helper operating the system.
