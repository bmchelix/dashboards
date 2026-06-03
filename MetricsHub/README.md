# MetricsHub Dashboards for BMC Helix / Grafana

This directory contains a collection of BMC Helix dashboards designed for infrastructures monitored by **MetricsHub®**.

The dashboards provide visibility into hardware health, system performance and storage systems:

- **Hardware Main** – Global infrastructure overview
- **Hardware Site** – Site or datacenter-level view
- **Hardware Host** – Detailed host-level hardware monitoring
- **Storage System** – Storage capacity, health, and performance monitoring
- **System Performance Metrics** – Operating system performance metrics
- **System Performance Metrics - Overview** – Fleet-wide performance overview

## What is MetricsHub?

MetricsHub® is an OpenTelemetry-native infrastructure monitoring solution that collects health, performance, and sustainability metrics from servers, storage systems, network devices, operating systems, databases, and other IT infrastructure components.

It uses a remote collection architecture and supports a wide range of technologies through built-in connectors. MetricsHub normalizes collected data according to OpenTelemetry semantic conventions and exports telemetry to observability platforms such as BMC Helix.

For more information, visit:

- https://metricshub.com

## How Data Is Collected

MetricsHub collects metrics remotely using standard monitoring and management protocols, including:

- SNMP
- SSH
- HTTP / REST APIs
- IPMI
- WMI / WinRM
- WBEM
- JDBC / SQL
- JMX

The collected metrics are transformed into OpenTelemetry-compliant telemetry and exported to the target observability platform.

## Requirements

These dashboards are intended for environments monitored by MetricsHub and require MetricsHub-collected metrics to be available in BMC Helix or another OpenTelemetry-compatible backend.
