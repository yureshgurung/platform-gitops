# Platform GitOps

```text
platform-gitops/
├── argocd/
│   ├── projects/
│   │   ├── platform.yaml
│   │   └── infrastructure.yaml
│   │
│   └── applications/
│       ├── metallb.yaml
│       ├── istio.yaml
│       ├── monitoring.yaml
│       └── logging.yaml
│
├── namespaces/
│   ├── istio-system.yaml
│   ├── istio-ingress.yaml
│   ├── monitoring.yaml
│   └── metallb-system.yaml
│
├── metallb/
│   ├── ipaddresspool.yaml
│   └── l2advertisement.yaml
│
├── istio/
│   ├── gateway.yaml
│   ├── gatewayclass.yaml
│   └── authorization-policy.yaml
│
├── monitoring/
│   ├── prometheus/
│   ├── grafana/
│   ├── loki/
│   ├── alloy/
│   └── tempo/
│
└── README.md
