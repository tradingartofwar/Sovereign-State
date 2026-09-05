# Privacy and Security

## Public repository

This public bootstrap contains universal doctrine and fictional or redacted examples only. Never write participant state here.

## Private repository

The person's sovereign-state repository should be private, but private GitHub is not a vault for every kind of sensitive material.

Store the minimum state needed for continuity. Prefer bounded summaries and source references over copying source contents.

The repository is durable state machinery, not a complete representation of the person or the human–AI relationship.

## Never store in Git

- passwords;
- authentication codes;
- recovery codes;
- passkey material;
- access tokens or private keys;
- account, insurance, claim, or government identifiers;
- raw medical, legal, financial, employment, or educational records;
- private correspondence or portal contents;
- unnecessary home addresses, phone numbers, or personal identifiers;
- information the person has not authorized the system to preserve.

Use an appropriate password manager, encrypted source system, provider portal, or other protected location for sensitive source material. Git may store a source-safe pointer and the operational meaning needed for continuity.

A resume file must remain useful without containing secrets.

## Relationship representations

A relationship channel should receive only the smallest representation needed for its declared purpose. Follow [Relationship Boundaries](RELATIONSHIP_BOUNDARIES.md).

- Sharing one message, date, request, or status does not authorize access to the whole repository or calendar.
- Keep private state, shared-domain truth, and relationship representations distinct.
- Verify actual permissions instead of assuming a folder name or interface creates isolation.
- Record source, freshness, authorization, expiry, and correction or withdrawal paths.
- Superseded, expired, paused, or withdrawn representations must not appear current.
- Test a new channel with harmless information before relying on it.

## Permissions

- Use the minimum repository and connector access that supports the person's intended workflow.
- The person completes authentication screens themselves.
- GPT never asks the person to disclose authentication secrets in chat.
- Adding collaborators, making a repository public, connecting another service, creating a relationship channel, or expanding permissions requires explicit human authorization.
- Deletion and destructive history changes require explicit confirmation and exact target verification.
- Review temporary helper access when setup ends.

## Recovery and portability

Recovery should not depend on one device, one conversation, one GPT runtime, or one helper. Preserve nonsecret continuity in the private repository and keep account-recovery material outside Git and chat.
