# camunda-doc-argocd
.
├── charts
│   ├── camunda-doc-gen           # Frontend Helm Chart
│   │   ├── templates             # K8s manifest templates
│   │   ├── Chart.yaml
│   │   ├── values.yaml           # Default values
│   │   ├── values-dev.yaml       # Dev overrides
│   │   ├── values-staging.yaml   # Staging overrides
│   │   └── values-prod.yaml      # Prod overrides
│   └── camunda-doc-gen-backend   # Backend Helm Chart
│       ├── templates
│       ├── Chart.yaml
│       ├── values.yaml
│       ├── values-dev.yaml
│       ├── values-staging.yaml
│       └── values-prod.yaml
├── argocd-apps                   # ArgoCD Application Manifests
│   ├── dev.yaml
│   ├── staging.yaml
│   └── prod.yaml
└── README.md