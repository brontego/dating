# Dating Workflow

Use this workflow for weekly Dating updates and for any smaller in-week refresh that materially changes the live state.

## Goal

Keep dating supportive, bounded, and reality-based. The system should reduce improvisation and pressure, not create a second full-time admin job.

## Read First

1. `state/current_week.yaml`
2. `state/current_matches.yaml`
3. `deliverables/current/hinge_reboot.md`
4. `deliverables/current/opener_queue.md`
5. `deliverables/current/reply_drafts.md`
6. `deliverables/current/profile_edits.md`
7. `deliverables/current/screening_summary.md`
8. `state/subsystem_snapshot.yaml`

## Weekly Pass

1. Reconcile the real lane first.
   - Is there a real date on the calendar?
   - Are there active matches that need attention?
   - Is the main job this week opener generation, reply support, screening, or light pre-date maintenance?
2. Update live match state.
   - Add or remove real people from `state/current_matches.yaml`.
   - Record booked dates, planned times, and the next concrete action.
   - Do not keep fake inventory just to make the system look active.
3. Refresh the current-week stance.
   - Update `state/current_week.yaml` with the actual weekly focus, guardrails, and bounded cadence.
   - Keep the system small if a real date is already booked.
4. Refresh the active deliverables only where needed.
   - `deliverables/current/hinge_reboot.md`
   - `deliverables/current/opener_queue.md`
   - `deliverables/current/reply_drafts.md`
   - `deliverables/current/profile_edits.md`
   - `deliverables/current/screening_summary.md`
5. Update the snapshot last.
   - Refresh `state/subsystem_snapshot.yaml` only after the real state and current deliverables agree.

## Midweek Refresh Triggers

- a new match becomes real enough to track
- a first date gets booked, moved, or canceled
- the active job changes from openers to maintenance or logistics
- dating creates a real cross-system implication for budgeting, household, or oversystem timing

## Guardrails

- no checking without taking a real action
- no fake quota behavior just to make the system feel busy
- no overtexting before a first date
- no spending spiral because dating is active again
- no apartment or Mercer escalation unless another subsystem explicitly confirms the need
- no over-automating messages until they stop sounding like you

## Cross-System Rule

If Dating changes materially, rerun oversystem coordination so `life-oversystem` stays aligned with the current match/date reality.
