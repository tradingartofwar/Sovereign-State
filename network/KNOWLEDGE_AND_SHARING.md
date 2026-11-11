# Knowledge, repositories and message boards

**Public operating guide · Working v0.1 · November 11, 2026**

The agent should actively *consider* what deserves to be retained, but should not indiscriminately archive conversation. Good continuity preserves consequential meaning and source context with the minimum necessary detail.

## Where something belongs

| Kind of information | Primary home | What belongs in personal Mission Control |
|---|---|---|
| Personal direction, interests, priorities, working preferences, cross-project commitments | Person's private `[name]-sovereign-state` | Concise, correctable current understanding |
| Active research, operations, design, code, cases, or shared decisions | The **owning project** repository/system | Project link, significance, status, owner, blocker and return condition |
| Messages and requests between collaborators | Authorized GitHub Issues/Discussions or an established message board | Link, date, who owes the next response and whether follow-up is warranted |
| Reusable non-sensitive method | Project-owned method record; optionally an authorized shared network contribution | Pointer and scope of what was shared |
| Sensitive source records, patient/client records, financial/medical records, passwords | Proper protected systems; never in public network repo, and never raw secrets in private GitHub | Only permitted, minimum necessary, non-sensitive status/pointers |

A sovereign-state repository is **Mission Control**, not a warehouse of every project file. Project teams should not need to read someone's personal state to do their work.

## When to capture

Consider retaining:

- A decision that changes direction, priorities, permissions or commitments.
- A consequential discovery, tested method, corrected assumption, or explicit unresolved question.
- New facts about an active project that change who is waiting on whom, what is blocked, or what happens next.
- A useful cross-project connection that might otherwise be lost.
- A stable, consented personal preference that changes how the assistant helps.
- A newly identified action that truly needs to return later.

**Don't** turn every possibility into a tracked action, store sensitive raw messages by default, or silently convert an AI interpretation into a fact about the person.

## Suggested minimum records (adapt to existing private structure)

The agent should reuse the person's existing `RESUME_HERE.md`, `state/CURRENT_STATE.md`, trajectories and project index when present. Only if useful, maintain a compact section such as:

```markdown
### Project connections
- Project: [name + canonical repo/link]
- Why it matters:
- Owning source:
- Current state (as of date + evidence):
- Next movement / owner / return condition:
- Approved collaboration channel:

### Authorized message boards
- Board: [project, exact URL, purpose]
- Access verified: [yes/no; when]
- Expected check: [on demand / relevant re-entry / actual scheduled task ID]
- Last checked: [date or not checked]
- Open message requiring attention: [link, owner, stage]
- Boundaries: [read-only / replies approved in scope / no patient data]
```

These are **fields, not a mandatory file layout**. Avoid duplicated tracking systems.

## Message-board practice

1. Discover boards through the person's authorized project list, existing repo instructions, or explicit invitation. Examples may include GitHub Issues and Discussions, or a designated collaboration board.
2. Determine whether access is actually connected and whether the board belongs to the person's work. Do not claim access based on a bare URL.
3. For a current coordination need, read relevant new items, including dates, replies, decisions and direct mentions where available. Do not assume every comment is directed to this person.
4. Distinguish **posted → received/visible → reviewed → responded → accepted/acted upon → outcome verified**. A new post does not prove an agent read it; reading does not mean the person agreed.
5. Suggest a reply or take an authorized bounded action; stop before an unapproved external message, disclosure, commitment, or permission change.
6. Update the **board/project** as the communication source and the **private Mission Control** only with a meaningful summary or return link.
7. If a recurring check would truly reduce burden, propose it; only a connected scheduler and verified task can perform monitoring between sessions. Log real executions, not aspirational schedules.

## Sharing with the wider human–AI network

Individual usefulness comes first. If a method might benefit others:

1. Determine the real owner, source, evidence stage, scope and known limitations.
2. Prepare a minimal **public-safe or specifically authorized** reusable representation; remove private details and nonpublic commercial or clinical material.
3. Identify exact audience, purpose, permission, how errors can be corrected and how sharing can be withdrawn or stopped.
4. Ask for authorization when not already given; do not infer blanket consent from a conversation, project membership or repository access.
5. Record **proposed, approved, published, received, used, and observed benefit** as different states. A posted method is not evidence that another agent adopted it.

## Recovery after interruption

Keep `RESUME_HERE.md` current with the true last established result, source links, unresolved questions, and next useful return. Read relevant sources again when stale. Write and then verify meaningful updates through the actual connector. If a link is inaccessible, report the limit plainly and offer the owner a portable text handoff; do not invent synchronization.

**Outcome to optimize:** the person returns to their work without needing to reconstruct everything, while retaining control over what is private, shared and important.
