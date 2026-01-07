# Release Checklist (Template)

Use this checklist for each release. The Release Manager should confirm each item before the release window.

Pre-release (must be completed before deployment)
- [ ] All feature acceptance criteria met and PRs merged
- [ ] CI pipelines green, security scans passed
- [ ] Release notes drafted and reviewed
- [ ] Database migrations planned and reviewed
- [ ] Rollback/runbook documented and tested
- [ ] Stakeholders notified of release timing and impact
- [ ] Support/on-call briefed with known risks and expected behavior
- [ ] QA Lead has signed off on release gating

Deployment steps
- [ ] Backup/snapshot taken (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Validate staging smoke results and approve production promotion
- [ ] Deploy to production via automated pipeline
- [ ] Run post-deploy verifications and smoke tests
- [ ] Monitor metrics for X minutes (team-defined) and confirm stability

Post-release
- [ ] Announce release to stakeholders and update documentation
- [ ] Log any post-release issues and assign owners
- [ ] Schedule a short retrospective if release had incidents or major migrations

Notes
- Replace "X minutes" with your org's verification window (e.g., 15, 30, 60 minutes).
- Fill in the Release Manager and QA Lead names for traceability.
