Instrument the backend with OpenTelemetry.

Include in the telemetry:

- service name
- environment
- deployed version


Add an OpenTelemetry Collector.

Create "observability/" directory with Docker Compose for:

- OpenTelemetry Collector
- Prometheus
- Loki
- Tempo
- Grafana

Keep this as a separate Compose project from the application stack
