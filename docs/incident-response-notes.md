# Incident Response Notes

This document summarizes how observability and monitoring support incident response in the platform.

## Key Operational Questions

During an incident, operators should be able to answer:

- Are workloads healthy?
- Are pods under resource pressure?
- Is scaling occurring?
- Are infrastructure alarms firing?
- What changed recently?

## Monitoring Tools Used

- Grafana for workload and cluster visibility
- Prometheus for metrics history
- CloudWatch for infrastructure alerts

## Why This Matters

Effective observability reduces time to detection and improves troubleshooting during runtime issues.