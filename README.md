# dheeraj-helm-repository

dheerajhelm-repository/
├── Chart.yaml          # Metadata about the chart (name, version, etc.)type are application and liberary
├── values.yaml         # The default values for templates
├── charts/             # Sub-charts this chart depends on (optional) kept the dependacy of other project if any.
├── templates/          # All the Kubernetes manifest templates
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── configmap.yaml
│   └── _helpers.tpl    # Template helpers (like functions/macros)
└── README.md           # (optional) description or usage


helm lint /path_of_chart  #to check Syntex
helm template   # create template for deployment accroding to set the values in value.yaml
helm instll my-helm --dry-run #preview the action while installing the helm chart
