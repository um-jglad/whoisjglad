---
title: "SPH HPC Utilization Dashboard" 
date: 2025-07-15
url: "/projects/sph-hpc-usage/"
tags: ["react js", "react", "vibecode", "hpc", "university of michigan", "great lakes", "armis2"]
author: ["Jacob Gladfelter"]
description: "An R Shiny app for visualizing HPC resource utilization by SPH members on the University of Michigan Great Lakes and Armis2 clusters." 
summary: "This project provides a user-friendly interface for monitoring and analyzing HPC resource usage within the School of Public Health."
cover:
    image: "hpc-usage.png"
    alt: "Screen caputure of SPH HPC Utilization Dashboard"
    relative: true
editPost:
    URL: "https://hpc-usage.bio.sph.umich.edu/"
    Text: "SPH HPC Utilization Dashboard"

---

## [Web App](https://hpc-usage.bio.sph.umich.edu/) | [Source Code](https://github.com/umich-biostatistics/sph-hpc-billing-shiny) 

> [!NOTE]
> Internal repo only, VPN and authorization required for web app access.

---
## Summary

An interactive Shiny app to explore ARC / HPC usage (treated as cost $) by Fiscal Year, Funding Source, Cluster, Uniqname, and (optionally) Department / Affiliation — with an optional SSO + LDAP protected deployment stack.

---

## Features

### Sidebar filters

    FY, Funding Source, Cluster, (optional) Department / Affiliation, Uniqname
    Slider for Top-N Uniqnames
    Monthly aggregation selector (Funding Source / Cluster / Uniqname / Overall)

### Tabs / Visuals

    Overview: KPIs (Total Cost + Top 3 Funding Sources by cost) + Stacked FY bars + Cluster costs
    Uniqname: Top-N stacked horizontal bars by Funding Source
    Monthly: Line (overall) or grouped multi-series by selected aggregation
    Department: (If Affiliation present) horizontal stacked bars by Funding Source
    Data: Filterable DT table + CSV download (honors both sidebar filters & column filters)

---
