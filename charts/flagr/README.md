
Flagr
===========

Open source feature flagging, A/B testing,and dynamic configuration microservice in Go.


## Configuration

The following table lists the configurable parameters of the Flagr chart and their default values.

| Parameter                | Description             | Default        |
| ------------------------ | ----------------------- | -------------- |
| `exteraEnv.PORT` |  | `18000` |
| `exteraEnv.FLAGR_LOGRUS_LEVEL` |  | `"info"` |
| `replicaCount` |  | `1` |
| `image.repository` |  | `"checkr/flagr"` |
| `image.pullPolicy` |  | `"IfNotPresent"` |
| `image.tag` |  | `""` |
| `imagePullSecrets` |  | `[]` |
| `nameOverride` |  | `""` |
| `fullnameOverride` |  | `""` |
| `serviceAccount.create` |  | `true` |
| `serviceAccount.annotations` |  | `{}` |
| `serviceAccount.name` |  | `""` |
| `podAnnotations` |  | `{}` |
| `podSecurityContext` |  | `{}` |
| `securityContext` |  | `{}` |
| `service.type` |  | `"ClusterIP"` |
| `service.port` |  | `80` |
| `ingress.enabled` |  | `false` |
| `ingress.annotations` |  | `{}` |
| `ingress.hosts` |  | `[{"host": "chart-example.local", "paths": []}]` |
| `ingress.tls` |  | `[]` |
| `resources.limits.cpu` |  | `"100m"` |
| `resources.limits.memory` |  | `"128Mi"` |
| `resources.requests.cpu` |  | `"50m"` |
| `resources.requests.memory` |  | `"40Mi"` |
| `autoscaling.enabled` |  | `false` |
| `autoscaling.minReplicas` |  | `1` |
| `autoscaling.maxReplicas` |  | `100` |
| `autoscaling.targetCPUUtilizationPercentage` |  | `80` |
| `nodeSelector` |  | `{}` |
| `tolerations` |  | `[]` |
| `affinity` |  | `{}` |



---
_Documentation generated by [Frigate](https://frigate.readthedocs.io)._

