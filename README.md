# AIOps Observability Portfolio

Hands-on AIOps observability lab built on a Synology NAS using Docker, Grafana, Prometheus, Loki, and OpenTelemetry.

## Project Structure
- **compose/** → Docker Compose files
- **grafana/** → Provisioning (dashboards, datasources, alerting)
- **otel/** → OpenTelemetry Collector configs
- **scripts/** → Custom scripts (Python automation, integrations)
- **docs/** → Architecture, runbooks, ROI analysis
- **media/** → Screenshots, videos

## Quickstart
```bash
docker compose -f compose/base.yml up -d
Grafana → http://localhost:3000

Prometheus → http://localhost:9090

