# GISML (Geographic Information System Markup Language)

This standard defines an encoding to describe how geographic information is to be presented. It includes querying, transformation and styling of the geographic information. It is designed to facilitate the presentation and interaction with geographic data across a wide range of applications, from web mapping to spatial analytics.

## Why GISML?

Geographic information systems (GIS) are a cornerstone of modern data visualization and analysis, but the diversity of tools and formats often creates challenges for interoperability and customization. GISML addresses these issues by providing a unified, human-readable format that:

- Enables consistent styling and visualization of geographic layers.
- Supports integration with most commont geographic data sources.
- Simplifies querying and transforming geographic information.

With GISML, developers and GIS practitioners can efficiently create rich visualizations of geographic information for analysis.

# Standard

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in
this document are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

## 1. Purpose

This document specifies an encoding format for the description of the presentation of geographic data. It is designed to be used in browsers or server-side applications for the analysis of geographic information.

## 2. Format

The GISML specification uses XML as the encoding format with a schema [definition](schema.xsd).
