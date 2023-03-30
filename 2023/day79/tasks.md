
iDay 79 - Prometheus 🔥

Now, the next step is to learn about the Prometheus.
It's an open-source system for monitoring services and alerts based on a time series data model. Prometheus collects data and metrics from different services and stores them according to a unique identifier—the metric name—and a time stamp.

Tasks:

---------------------------------------------------------------------------------------------------------------------------------------------------------

1. What is the Architecture of Prometheus Monitoring?
Ans: Prometheus is a monitoring tool for capturing and processing any time-series that contains only numbers. Along with metrics, individual identifiers, and timestamps, it collects, arranges, and stores them.
Open-source software called Prometheus “scrapes” metrics HTTP endpoints to gather metrics from targets. Platforms for infrastructure (like Kubernetes), applications, and services are all supported “targets” (e.g. database management systems). Prometheus is a flexible metrics collection and alerting tool that works with its companion Alertmanager service.

2. What are the Features of Prometheus?
Ans: Features of Prometheus
The key features of Prometheus are:

A multi-dimensional data model that uses metrics to identify time series data
Key/value pairs and names
A flexible query language to take advantage of this dimensionality is PromQL.
No dependency on distributed storage; individual server nodes are independent
A pull model over HTTP is used for time series collection.
An intermediary gateway is supported for pushing time series.
Targets are found using static configuration or service discovery
Support for a variety of graphing and dashboarding methods

3. What are the Components of Prometheus?
Ans : Prometheus Components
Prometheus has a number of parts that work together to monitor and report on the behavior, performance, and general health of the system. Metrics exposed in plaintext via HTTP endpoints by instrumented applications and services are scraped as the main source of data for data collection.

There are numerous components that make up the Prometheus ecosystem, most of which are optional:

Time series data is scraped and stored on the primary Prometheus server.
Instrumenting client libraries for application code
A push gateway that supports temporary jobs
Exporters with a specific purpose for products like Graphite, StatsD, HAProxy, etc.
A notification manager for alerts
Various support tools

4. What database is used by Prometheus?
Ans: Prometheus has a sophisticated local storage subsystem. For indexes, it uses LevelDB. For the bulk sample data, it has its own custom storage layer, which organizes sample data in chunks of constant size (1024 bytes payload). These chunks are then stored on disk in one file per time series.

5. What is the default data retention period in Prometheus?
Ans: the default date retention period in prometheus is 15 days.

---------------------------------------------------------------------------------------------------------------------------------------------------------

Ref: https://www.devopsschool.com/blog/top-50-prometheus-interview-questions-and-answers/
