# sedai-slo
Sedai uses time sliced SLOs. We divide the timeseries into equal-duration intervals, called “slices”. The length of the interval configurable with options of 1 or 5 minutes. For each slice, there is a single value for the timeseries, and the uptime condition (such as value < 1) is evaluated for each slice. If the condition is met, the slice is considered uptime.

This example walks you through deploying sedai slo crd 

## Prerequisites
Kubernetes cluster available

## Deploying sedai slo crd

```bash
kubectl apply --server-side -f ./setup
```

## Deploying SLO examples
```
```