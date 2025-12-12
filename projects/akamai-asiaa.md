---
layout: project
type: project
image: img/akamai-asiaa/MallariS_Midpoint2.jpg
title: "Enhancing Real-Time Monitoring of Radio Telescope Power Metrics with Grafana"
date: 2025
published: true
labels:
  - Software Engineering
summary: "Custom Grafana dashboards for monitoring antenna signal health and power usage for off-grid radio telescope"
---
## Project Overview
The Academia Sinica Institute of Astronomy and Astrophysics (ASIAA) utilizes the Bustling Universe Radio Software Telescope in Taiwan (BURSTT) Array for fast radio burst research. To expand BURSTT’s observational reach, ASIAA maintains a remote, off-grid outrigger site in Pahala, Hawai‘i, which relies entirely on independent power sources. ASIAA engineers currently employ Grafana, an open-source visualization interface, alongside Prometheus and InfluxDB databases for real-time tracking of system operations.  This project enhances the existing monitoring infrastructure by developing and integrating custom Grafana dashboard panels to track signal power and antenna health at the Pahala site. The panels integrate new data sources and advanced metric visualizations while ensuring compatibility with the existing databases for real-time data logging. The system was engineered to support future expansion of the site from 8 to 64 antennas, offering per-antenna power consumption tracking and performance visualization through detailed graphs and maps. To ensure prompt intervention, thresholds were defined for power anomalies that automatically trigger real-time Slack alerts. By extending Grafana’s typical functionalities, the dashboard enables real-time detection of antenna power issues, clear visualization of key metrics, and timely alerts for rapid response. Ultimately, the new dashboard enhances the telescope’s operational reliability by minimizing downtime and mitigating system failures. This ensures consistent scientific data collection and long-term performance in its challenging remote environment.

## Project Presentation
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vScfCad8j8AuSP3psLAmH5OLMusYYUIzLoGrtxmqeOxwELw0PdMu5UqEJaK_o434oCu-UT8a13-5XAO/pubembed?start=false&loop=true&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>