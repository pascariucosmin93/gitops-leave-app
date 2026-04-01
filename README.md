# gitops-leave-app

GitOps repository for the Employee Leave Management platform.

## Structure

```text
k8s/chart/
  Chart.yaml
  values.yaml
  templates/
```

## Versioning

- `versions.image`: `x.x.x`
- `versions.promote`: `x.x`

The chart deploys backend and frontend using the image tags configured in `values.yaml`.
