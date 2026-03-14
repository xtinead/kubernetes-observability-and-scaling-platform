# CloudWatch Monitoring

This directory documents the AWS-native monitoring model used alongside Prometheus and Grafana.

## Purpose

CloudWatch provides infrastructure-level visibility for AWS resources supporting the Kubernetes platform.

## Monitoring Scope

CloudWatch is used for:

- infrastructure metrics
- logs and events
- alarm generation
- AWS-native operational visibility

## Why CloudWatch Is Included

Prometheus focuses on in-cluster metrics.

CloudWatch complements that by providing:

- visibility into AWS-managed components
- alarm-based operational awareness
- infrastructure event monitoring
- cloud-native integration with AWS resources

## Alerting Model

CloudWatch alarms are used to identify conditions such as:

- infrastructure stress
- abnormal resource behavior
- operational thresholds being exceeded

CloudWatch alerts are then surfaced to platform engineers for response.