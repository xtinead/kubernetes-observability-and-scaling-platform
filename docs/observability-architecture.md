# Observability Architecture

The observability architecture for this platform combines Kubernetes-native and AWS-native monitoring patterns.

## Core Components

- Prometheus for metrics collection
- Grafana for dashboards and visualization
- CloudWatch for infrastructure monitoring and alerting

## Design Goal

The goal is to provide visibility into both:

- application/workload behavior
- underlying cloud infrastructure conditions

This allows platform engineers to understand the full runtime picture.

## Why Multiple Monitoring Layers Are Used

Prometheus and Grafana provide in-cluster visibility.

CloudWatch provides AWS-level infrastructure monitoring and alarms.

Together they create a more complete operational model.