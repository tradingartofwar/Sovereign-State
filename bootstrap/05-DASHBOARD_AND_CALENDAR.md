# Step 5 — Offer the Dashboard and Calendar When Ready

The dashboard is a projection of living state, not the source of truth. Do not build an attractive empty shell.

Before building or materially changing a dashboard, read [Dashboard Integrity](../doctrine/DASHBOARD_INTEGRITY.md).

## Dashboard readiness gate

GPT may offer the dashboard when all of these are established:

- the private repository exists;
- direct GitHub reading and writing are verified;
- human/AI authority and privacy boundaries are present;
- at least three meaningful trajectories are active;
- each trajectory has current reality, next movement, owner, and a return date or trigger;
- at least one real date, appointment, deadline, routine, or review window exists;
- at least one later update or correction has been processed successfully;
- the authoritative source for the dashboard is named;
- active trajectories can be reconciled as visible or explicitly excluded.

Record the evidence in `state/BOOTSTRAP_STATE.md`. Do not infer readiness from file count alone.

## The offer

Say:

> We now have enough living information to make a dashboard genuinely useful. I can create a private dashboard showing what matters now, your active projects and interests, what you are waiting for, and a calendar of appointments, deadlines, routines, and return dates. Would you like me to build it?

Build only after the person accepts.

## First dashboard

Keep the first version small:

- Today
- Coming up
- Calendar
- Active trajectories
- Waiting on
- Projects and interests
- Possibilities
- Recently changed
- Source and honest “as of” date
- A simple explanation of how to tell GPT what changed

Once the person accepts the dashboard, preserve its route, field names, and basic layout. Propose material display changes instead of silently replacing the accepted view.

## Source-to-projection check

For every dashboard update:

1. update the authoritative private state;
2. generate or update the dashboard from that state;
3. confirm that every active trajectory is visible or explicitly excluded;
4. keep reported, inferred, stale, and unverified information distinguishable;
5. retire established completions from present attention while preserving meaningful history;
6. verify that corrections appear in the accepted dashboard.

A manual dashboard-only edit is not durable state. A display problem must not alter or endanger the source.

## Calendar meanings

Do not convert every date into an appointment. Preserve these distinctions:

| Layer | Meaning |
| --- | --- |
| Appointment | A fixed external event |
| Deadline | Something must happen by a date |
| Planned action | The person intends to act |
| Review date | GPT should bring the trajectory back |
| Routine | A recurring activity |
| Possibility | A tentative or unconfirmed date |

The initial calendar may be generated from the private repository. A real calendar service may be connected later with separate permission.

When a calendar service is connected:

- the calendar service owns actual scheduled events;
- the sovereign-state repository owns trajectories, deadlines, and return paths;
- the dashboard combines them as a correctable projection.
