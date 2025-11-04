# Assessment Component Metadata Records

## Overview

The Assessment Interoperability Framework (AIF) defines a **DCAT Application Profile** to describe both conceptual entities (e.g., *Benchmark*, *Metric*) and code entities (e.g., *Test*, *Algorithm*). These metadata records can be hosted anywhere on the Web.  
This repository provides a **generic and persistent location** for archiving such records, enabling their discovery and indexing by **[OSTrails Index](https://tools.ostrails.eu/fdp-index/search)**.

## Purpose

This repository serves as a submission endpoint for the **[FAIR Wizard authoring tool](https://ostrails-fair.fair-wizard.com/wizard/)**, a questionnaire-based knowledge model designed to collect and structure metadata for FAIR Assessment components, including:

- **[Test](/assessment-component-metadata-records/test/)**
- **[Metric](/assessment-component-metadata-records/metric/)**
- **[Benchmark](/assessment-component-metadata-records/benchmark/)**
- **[Algorithm](/assessment-component-metadata-records/algorithm/)**

Once metadata are completed through the FAIR Wizard, the resulting DCAT-based record can be automatically pushed into this repository for submission and indexing.

## Accessibility

This repository is published via **GitHub Pages**, supporting **RDF content negotiation**.   This allows both human users and machine agents to access and consume the resources stored here according to FAIR principles. You can explore the web interface and browse the available records at: [https://ostrails.github.io/assessment-component-metadata-records/](https://ostrails.github.io/assessment-component-metadata-records/)