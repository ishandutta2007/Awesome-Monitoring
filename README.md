# Awesome-Monitoring

## Top Monitoring Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Infrastructure Monitoring, APM, Observability, Metrics, Logs, Traces & Alerting*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Monitoring & Observability**. These systems collect metrics, logs, traces, and events from applications and infrastructure, then provide dashboards, alerting, and root-cause analysis to keep systems reliable.



**Examples** include Datadog, New Relic, Dynatrace, Grafana Cloud, LogicMonitor, Splunk Observability, AppSignal, Honeycomb, Sentry, and Elastic Cloud (the category leaders).



**Open-source emphasis**: Monitoring has one of the strongest open-source ecosystems. **Prometheus**, **Grafana**, **OpenTelemetry**, **VictoriaMetrics**, **Zabbix**, **SigNoz**, and the open cores of Elastic, Sentry, and others power a large share of production observability stacks. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Datadog](https://www.datadoghq.com/)**  

  Full-stack observability platform covering infrastructure metrics, APM, logs, RUM, security monitoring, and AI-assisted insights.



- **[New Relic](https://newrelic.com/)**  

  Unified observability platform with APM, infrastructure monitoring, logs, browser/mobile monitoring, and AI-powered analytics.



- **[Dynatrace](https://www.dynatrace.com/)**  

  AI-driven observability and application performance monitoring platform with automatic discovery and causal analysis (Davis AI).



- **[Grafana Cloud](https://grafana.com/products/cloud/)**  

  Fully managed observability stack built on Grafana, Prometheus, Loki, Tempo, and related open-source projects.



- **[LogicMonitor](https://www.logicmonitor.com/)**  

  Hybrid infrastructure monitoring platform focused on automated discovery, metrics, and IT operations visibility.



- **[Splunk Observability](https://www.splunk.com/)**  

  Observability suite (metrics, APM, infrastructure, logs) integrated with the broader Splunk analytics platform.



- **[AppSignal](https://www.appsignal.com/)**  

  Application performance monitoring and error tracking platform popular with Ruby, Elixir, Node, and other developer teams.



- **[Honeycomb](https://www.honeycomb.io/)**  

  Observability platform optimized for high-cardinality event data, distributed tracing, and fast exploratory debugging.



- **[Sentry](https://sentry.io/)**  

  Error monitoring and performance platform focused on application exceptions, with growing tracing and metrics capabilities.



- **[Elastic Cloud / Elastic Observability](https://www.elastic.co/)**  

  Managed Elasticsearch, Kibana, APM, and logging stack for search-powered observability and security analytics.



## Open-Source GitHub Projects

- **[Prometheus](https://github.com/prometheus/prometheus)**  

  The de-facto open-source metrics collection and alerting system with a powerful query language (PromQL) and wide ecosystem of exporters.



- **[Grafana](https://github.com/grafana/grafana)**  

  Leading open-source visualization and dashboarding platform that works with Prometheus, Loki, Tempo, Elasticsearch, and many other data sources.



- **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector)**  

  Vendor-neutral open standard and collector for metrics, logs, and traces—now the foundation of most modern observability pipelines.



- **[VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics)**  

  High-performance, cost-efficient open-source time-series database and monitoring solution, often used as a Prometheus-compatible backend.



- **[Zabbix](https://github.com/zabbix/zabbix)**  

  Mature open-source monitoring solution for networks, servers, applications, and services with strong alerting and auto-discovery.



- **[SigNoz](https://github.com/SigNoz/signoz)**  

  Open-source alternative to Datadog/New Relic built on OpenTelemetry, providing metrics, traces, and logs in a single application.



- **[Grafana Loki](https://github.com/grafana/loki)**  

  Horizontally scalable, highly available open-source log aggregation system inspired by Prometheus.



- **[Grafana Tempo](https://github.com/grafana/tempo)**  

  Open-source, easy-to-operate distributed tracing backend from the Grafana ecosystem.



- **[Jaeger](https://github.com/jaegertracing/jaeger)**  

  Open-source distributed tracing system originally from Uber, widely used for microservices observability.



- **[Elastic Stack (Elasticsearch + Kibana + Beats/Agent)](https://github.com/elastic)**  

  Open-source search and analytics engine with strong logging, APM, and observability features (self-hosted or Elastic Cloud).



- **[Sentry (self-hosted)](https://github.com/getsentry/sentry)**  

  Open-source error tracking and performance monitoring platform that can be fully self-hosted.



- **[Netdata](https://github.com/netdata/netdata)**  

  Real-time, per-second performance monitoring with a focus on low overhead and beautiful visualizations.



- **[Checkmk / Nagios-compatible tools](https://github.com/)**  

  Classic open-source infrastructure monitoring solutions still used in many environments.



### Additional Strong Open-Source Options

- Building the classic **Prometheus + Grafana + Alertmanager** stack for metrics and alerting.

- Adding **Loki + Tempo + OpenTelemetry** for a complete Grafana-native observability pipeline.

- Choosing **SigNoz** or **VictoriaMetrics** when seeking a more unified or cost-efficient open alternative to commercial APM.

- Using **Zabbix** or **Netdata** for traditional infrastructure and host-level monitoring.

- Self-hosting **Sentry** and **Elastic Stack** for error and log-centric use cases.

- Accepting that AI-assisted root-cause analysis, global data retention at massive scale, and polished multi-product UIs still favor commercial platforms (Datadog, Dynatrace, New Relic, etc.).

- Focusing open-source efforts on data ownership, cost control, and avoiding vendor lock-in.



**Frameworks for building custom systems**: Instrument with OpenTelemetry → collect metrics in Prometheus/VictoriaMetrics, logs in Loki/Elastic, traces in Tempo/Jaeger → visualize and alert in Grafana or SigNoz → optionally forward selected data to a commercial platform for advanced analytics. Suitable for platform and SRE teams that want full control. Many organizations run hybrid stacks (open core + commercial SaaS).



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Monitoring systems collect sensitive operational and sometimes personal data. Self-hosted deployments require proper access control, retention policies, and security hardening. This list is not security or operational advice.



---

**Made for SREs, platform engineers, and developers who need reliable visibility into their systems.**

Let's keep observability powerful, affordable, and as open as practical.
