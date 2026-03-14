# Horizontal Pod Autoscaling (HPA)

This directory documents the autoscaling model used for Kubernetes workloads in the platform.

## Purpose

Horizontal Pod Autoscaling is used to adjust pod replica counts automatically based on observed workload metrics.

## Scaling Model

The HPA controller evaluates metrics such as:

- CPU utilization
- memory usage
- workload demand

Based on these metrics, Kubernetes increases or decreases the number of running pods.

## Why HPA Is Used

HPA helps ensure that workloads:

- remain responsive under load
- scale efficiently
- avoid unnecessary overprovisioning
- recover from traffic spikes more gracefully

## Operational Considerations

HPA configuration requires careful tuning of:

- minimum replicas
- maximum replicas
- scaling thresholds
- stabilization behavior

Autoscaling is most effective when paired with observability and load validation.