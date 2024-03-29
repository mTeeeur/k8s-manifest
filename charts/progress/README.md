# progress

![version: 1.0.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

A Helm chart for Kubernetes

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| progress.app.containerPort | int | `80` |  |
| progress.app.env.APP_MODE | string | `"debug"` |  |
| progress.app.env.APP_POSTGRES_DATABASE_NAME | string | `"blueprint"` |  |
| progress.app.env.APP_POSTGRES_HOST | string | `"localhost"` |  |
| progress.app.env.APP_POSTGRES_PASSWORD | string | `"password"` |  |
| progress.app.env.APP_POSTGRES_PORT | int | `5432` |  |
| progress.app.env.APP_POSTGRES_USER | string | `"user"` |  |
| progress.app.env.APP_S3_ACCESS_KEY_ID | string | `"<AWS_ACCESS_KEY_ID>"` |  |
| progress.app.env.APP_S3_BUCKET | string | `"<S3_BUCKET>"` |  |
| progress.app.env.APP_S3_SECRET_ACCESS_KEY | string | `"<AWS_SECRET>"` |  |
| progress.app.env.APP_TOKEN_CONFIG_CERTIFICATE_DIR_PATH | string | `"/rsa"` |  |
| progress.app.env.APP_TOKEN_CONFIG_CERTIFICATE_FILE_NAME | string | `"rsa.crt"` |  |
| progress.app.env.APP_TOKEN_CONFIG_PRIVATE_KEY_FILE_NAME | string | `"rsa.key"` |  |
| progress.app.env.APP_USER_SERVICE_GRPC_HOST | string | `"user"` |  |
| progress.app.env.APP_USER_SERVICE_GRPC_PORT | int | `9180` |  |
| progress.app.env.APP_USER_SERVICE_HTTP_HOST | string | `"localhost"` |  |
| progress.app.env.APP_USER_SERVICE_HTTP_PORT | int | `9080` |  |
| progress.app.env.GIT_ACCESS_TOKEN | string | `"<YOUR_GIT_ACCESS_TOKEN>"` |  |
| progress.app.env.GIT_USERNAME | string | `"<YOUR_GIT_USERNAME>"` |  |
| progress.app.livenessProbe | string | `"/"` |  |
| progress.app.readinessProbe | string | `"/"` |  |
| progress.autoscaling.enabled | bool | `false` |  |
| progress.autoscaling.maxReplicas | int | `100` |  |
| progress.autoscaling.minReplicas | int | `1` |  |
| progress.autoscaling.targetCPUUtilizationPercentage | int | `80` |  |
| progress.forceRedeploy | bool | `false` |  |
| progress.fullnameOverride | string | `"progress"` |  |
| progress.image.pullPolicy | string | `"Always"` |  |
| progress.image.repository | string | `"ghcr.io/unitedcollab/progress"` |  |
| progress.image.tag | string | `"test"` |  |
| progress.nameOverride | string | `"progress"` |  |
| progress.node_port.nodePort | string | `nil` |  |
| progress.replicaCount | int | `1` |  |
| progress.service.port | int | `80` |  |
| progress.service.targetPort | int | `80` |  |
| progress.service.type | string | `"ClusterIP"` |  |
| progress.serviceAccount.annotations | object | `{}` |  |
| progress.serviceAccount.create | bool | `true` |  |
| progress.serviceAccount.name | string | `""` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.10.0](https://github.com/norwoodj/helm-docs/releases/v1.10.0)
