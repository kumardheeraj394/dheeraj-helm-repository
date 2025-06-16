# dheeraj-helm-repository

dheerajhelm-repository/
├── Chart.yaml          # Metadata about the chart (name, version, etc.)
├── values.yaml         # The default values for templates
├── charts/             # Sub-charts this chart depends on (optional)
├── templates/          # All the Kubernetes manifest templates
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── configmap.yaml
│   └── _helpers.tpl    # Template helpers (like functions/macros)
└── README.md           # (optional) description or usage
