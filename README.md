# bootstrap-otel-auth-app

A repo that demonstrates setting up an app with authentication / authorization (authn/z) and an OTEL exporter for important observability data to be consumed by Prometheus, Loki, Jaeger, et. al., visualized on a set of Grafana dashboards.

# Manual Steps for Now

1. Install kind
2. kind create cluster (todo)
3. Use localtest.me
4. for kustomize, also have noop gcp overlays
5. kustomize examples: https://github.com/kubernetes-sigs/kustomize/tree/master/examples/ldap/base
6. kustomize apply nginx ingress
7. kustomize apply oauth2-proxy
8. kustomize apply keycloak / dex
9. kustomize apply simple React app to demo redirects to login / logout / etc.
10. OTEL setup
