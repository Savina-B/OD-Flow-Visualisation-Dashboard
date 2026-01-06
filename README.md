# OD-Flow-Visualisation-Dashboard

**Overview**
An interactive Dash app for exploring origin–destination (OD) trip flows using a map-based interface. Users can click a centroid to visualise associated flows and filter results by direction (P/A), time period, vehicle class, and purpose. The tool also supports basemap switching, layer opacity control, and optional boundary overlays.

**Key Features**

- Map-based OD flow visualisation triggered by clicking a centroid

- Filters: direction, time period, vehicle, purpose

- Zone boundary overlay toggle

- Basemap selector + opacity slider

- “Model run” selector pattern using a searchable DataTable (demo dataset in public version)

**Tech Stack**

- Python, Dash, Plotly, Dash Bootstrap Components, Dash Design Kit

- GeoPandas for boundary layers

- (Private version) Postgres-backed queries

**Anonymisation Notes**

- Branding and organisation references removed

- Internal dataset names replaced with generic placeholders

- Public version uses representative/synthetic data
- <img width="1024" height="535" alt="image" src="https://github.com/user-attachments/assets/b4d7f97a-b4bb-40ad-a1cc-44f57633a83d" />
