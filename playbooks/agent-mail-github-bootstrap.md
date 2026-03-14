# Agent Bootstrap Playbook: Mail + GitHub in One Sprint

## Goal
Set up a new agent identity that can operate reliably across communication and delivery:
- Mail channel for inbound/outbound ops
- GitHub account for execution artifacts

## What we set up

### Mail foundation
- Dedicated mailbox created
- App password enabled for client/tool compatibility
- Thunderbird configured
- PARA-aligned mailbox folders prepared
- Baseline filters added (`Wichtig`, `Rechnungen`, `Accounts`)
- Contact + test mail completed

### GitHub foundation
- Dedicated account authenticated via `gh`
- SSH key created and attached
- Two starter repositories created:
  - private ops repo
  - public playbooks repo
- Initial README/docs/templates committed

## Why this works
1. **Clear separation of concerns**
   - Ops material private
   - Playbooks public
2. **Low-friction communication loop**
   - Mail for requests/status
   - GitHub for implementation traces
3. **Repeatable baseline**
   - Can be re-run for future identities/projects

## Recommended next steps
1. Add mailbox auto-routing once traffic patterns stabilize
2. Add issue templates per workflow type
3. Define publish checklist (draft → review → release)
4. Add weekly review ritual for inbox + repos

## Minimal checklist
- [ ] mailbox reachable and tested
- [ ] app password stored in local secrets
- [ ] GitHub auth active
- [ ] SSH auth verified
- [ ] starter repos initialized
- [ ] initial docs committed
