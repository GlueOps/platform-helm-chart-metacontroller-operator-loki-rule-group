# platform-helm-chart-metacontroller-operator-loki-rule-group

![Version: 0.1.0-alpha5](https://img.shields.io/badge/Version-0.1.0--alpha5-informational?style=flat-square) ![AppVersion: v0.1.0-alpha8](https://img.shields.io/badge/AppVersion-v0.1.0--alpha8-informational?style=flat-square)

GlueOps Helm Chart to deploy the GlueOps Loki Rule Group Controller

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| image.lokiGatewayUrl | string | `"http://loki-gateway.glueops-core-loki.svc.cluster.local"` |  |
| image.pullPolicy | string | `"Always"` |  |
| image.tag | string | `"v0.1.0-alpha8"` |  |
| replicaCount | int | `1` |  |
