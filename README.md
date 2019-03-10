# prometheus-thanos-helm-chart

This chart is a fork from stable/prometheus helm chart.

Last sync: 2019-03-10

Additions

- optional thanos sidecar server-deployment.yaml
- thanos-sidecar-configmap-s3.yaml
- thanos-sidecar-secret-tls.yaml
- thanos-sidecar-service-cluster.yaml
- thanos-sidecar-service-grpc.yaml
- thanos-sidecar-service-http.yaml
- updated values.yaml with thanos options
- README with thanos options


Note: this chart is developed and used in an AWS environment, with grpc over TLS and no gossip cluster.

Related charts:
- https://github.com/arthur-c/thanos-helm-chart
