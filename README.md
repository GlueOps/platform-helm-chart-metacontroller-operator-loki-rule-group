# platform-helm-chart-metacontroller-operator-loki-rule-group

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![AppVersion: v0.1.0](https://img.shields.io/badge/AppVersion-v0.1.0-informational?style=flat-square)

GlueOps Helm Chart to deploy the GlueOps Loki Rule Group Controller

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| appName | string | `"loki-alert-rule-group-controller"` |  |
| appNamespace | string | `"nil"` |  |
| image.lokiGatewayUrl | string | `"nil"` |  |
| image.pullPolicy | string | `"nil"` |  |
| replicaCount | int | `1` |  |
