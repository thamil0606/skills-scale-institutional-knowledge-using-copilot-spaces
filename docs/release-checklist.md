# Release Checklist

This checklist supports safe, repeatable releases. Use it before promoting code to production.

- [ ] Confirm release scope and changelog are approved by Product Manager
- [ ] Verify all PRs are reviewed and merged into the release branch
- [ ] Run full test suite: unit, integration, and e2e where applicable
- [ ] Verify performance and load test targets (if applicable)
- [ ] Run security scans and address critical/high findings
- [ ] Confirm database migrations have been reviewed and have rollback plans
- [ ] Ensure monitoring and alerting dashboards are updated for new features
- [ ] Validate feature flags and toggle plans for gradual rollout
- [ ] Smoke test the release in staging environment
- [ ] Prepare rollback plan and ensure runbooks are accessible
- [ ] Communicate release window and impact to stakeholders
- [ ] Schedule post-release verification and retrospectives

Owner: DevOps / Release Manager
