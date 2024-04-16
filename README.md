#grafana-allow

config files to run grafana-alloy container for this node to collect

discovery.docker.s3
local.file_match.logs
loki.relabel.journal
loki.relabel.s3_docker
loki.source.docker.s3_docker
loki.source.file.s3_logs
loki.source.journal.s3_read
loki.source.syslog.local
loki.write.default
otelcol.auth.basic.grafana_cloud_tempo
otelcol.exporter.logging.default
otelcol.exporter.loki.default
otelcol.exporter.otlp.default
otelcol.exporter.otlphttp.default
otelcol.exporter.prometheus.default
otelcol.processor.attributes.default
otelcol.processor.batch.default
otelcol.receiver.otlp.default
prometheus.exporter.kafka.s3
prometheus.exporter.self.agent
prometheus.exporter.unix.s3
prometheus.remote_write.default
prometheus.scrape.s3_agent
prometheus.scrape.s3_unix
systems.k8s_services.dev
systems.k8s_services.prod

