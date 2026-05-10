---
layout: default
title: Flight Path Analysis
---

# Flight Path Analysis – Airspace Restrictions

This project analyses historic commercial flight data to understand how airspace restrictions introduced in February 2022 affected Europe–Asia flight routes.

## Objectives
- Examine whether flight routes were redistributed following restrictions
- Identify routes that collapsed or persisted
- Assess structural changes at route level

## Approach
- Built a Python-based ETL pipeline to process approximately 15 million flight records
- Engineered route-level features to summarise activity before and after restrictions
- Applied K-means clustering to identify common route patterns
- Created geographic visualisations to support interpretation

## Tools
- Python (pandas, NumPy, scikit-learn)
- matplotlib
- GeoPandas

## Outcome
The analysis identified clear structural changes in Europe–Asia flight routes following the restrictions, including complete loss of some routes and persistence of others due to geopolitical and airspace considerations.
