# Release Checklist

Use this checklist to ensure consistent, auditable releases with minimal risk.

## Pre-Release Checklist

- [ ] All CI builds passing on release branch
- [ ] Security scans completed with no critical issues
- [ ] Release window scheduled and communicated to stakeholders
- [ ] Rollback plan documented and reviewed
- [ ] Smoke tests prepared and validated in staging
- [ ] Release Manager assigned and available
- [ ] Quality Lead has signed off on release readiness
- [ ] Customer Success Lead notified of customer-impacting changes
- [ ] Release notes drafted and reviewed
- [ ] Database migrations tested (if applicable)
- [ ] Feature flags configured appropriately
- [ ] Monitoring and alerting verified

## Post-Release Checklist

- [ ] Deployment completed successfully
- [ ] Smoke tests executed and passing in production
- [ ] Key metrics monitored for anomalies (first 30 minutes)
- [ ] Stakeholders notified of successful deployment
- [ ] Release notes published
- [ ] Any incidents or rollbacks documented
- [ ] Post-release verification completed
- [ ] Results documented in release log
- [ ] Retrospective scheduled if issues occurred
- [ ] Customer Success Lead confirmed no critical customer issues

## Rollback Criteria

Rollback if any of the following occur:
- Critical functionality is broken
- Security vulnerability introduced
- Data integrity issues detected
- Error rates exceed baseline by >20%
- Customer-impacting performance degradation
