---
title: Deploying and maintaining STAC infrastructure for large-scale applications
theme: black
---

# Deploying and maintaining STAC infrastructure for large-scale applications

November 19th, 2024

---

## Overview

- Growth of geospatial data and management challenges
- STAC as a community-driven solution
- Real-world implementations and lessons learned

Note: These notes will only be visible to the presenter

---

## The Challenge

- Exponential growth in geospatial data volume
- Increasing complexity in data management
- Need for standardized metadata
- Demand for scalable solutions

---

## STAC Overview

- SpatioTemporal Asset Catalog
- Community-driven specification
- Standardized metadata format
- RESTful API design

---

## Case Study 1: LandsatLook 2.0

- USGS Platform for Landsat data access
- Dynamic tiling implementation
- High-volume metadata access patterns

----

### Dynamic Tiling Deep Dive

- Real-time tile generation
- Metadata access requirements
- Performance optimization strategies

```python
import titiler
```

Note: Add specific performance metrics here

---

## Case Study 2: Microsoft Planetary Computer

- Large-scale geospatial data platform
- Birth of pgstac
- Database innovation

----

### pgstac Evolution

- Why traditional solutions weren't enough
- Key architectural decisions
- Performance characteristics

---

## Case Study 3: Amazon Sustainability Data Initiative

- Global sustainability data platform
- stactools ecosystem
- Event-driven architecture

----

### ASDI Implementation

- stactools-packages
- stactools-pipelines
- Event-based metadata generation

---

## Key Takeaways

- Scalability considerations
- Implementation strategies
- Operational benefits
- Future directions

---

## Thank You

Questions?

Contact Information:
[Your contact details]
