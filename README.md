# TerraLink: Bridging Domains for Spatial Understanding

## Authors
- Federico Larrieu (federico.larrieu@colostate.edu)
- Eric Burton Samuel Martin (eric.burton.martin@colostate.edu)

## Abstract
The TerraLink framework introduces a solution for enhancing spatial understanding through the integration of heterogeneous geospatial datasets into a unified knowledge graph enabling intuitive, human-language-based querying. Key contributions include the development of a Spatial Resolution Mapping technique to optimize data integration processes and reduce computational inefficiencies, allowing for a customizable graph construction approach. Our knowledge graph demonstrates efficient performance in query processing and allows for the creation of custom motifs. The framework aims to advance environmental monitoring and urban planning by enabling detailed analyses of spatial interactions that affect water quality and other ecological factors.

## Table of Contents
- [Introduction](#introduction)
- [Problem Characterization](#problem-characterization)
- [Dominant Approaches](#dominant-approaches)
- [Methodology](#methodology)
- [Experimental Benchmarks](#experimental-benchmarks)
  - [Graph Construction and Enrichment](#graph-construction-and-enrichment)
  - [Relationship Type Distribution](#relationship-type-distribution)
  - [Degree Distribution](#degree-distribution)
  - [PageRank Benchmarking](#pagerank-benchmarking)
  - [Query Performance](#query-performance)
  - [Motif Discovery](#motif-discovery)
  - [Integration Execution Times](#integration-execution-times)
  - [Spatial Hierarchy Mapping](#spatial-hierarchy-mapping)
- [Challenges](#challenges)
- [Insights](#insights)
- [Future Prospects](#future-prospects)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)
- [References](#references)

## Introduction
Geospatial analytics allows us to observe natural phenomena or spatial interactions across domains. Whether it’s planning urban infrastructure or understanding the impacts of industrial activities on water quality, geospatial analytics plays a large role in many decision-making processes. This project proposes TerraLink, a system that leverages knowledge graphs to query data using intuitive spatial relationships, simplifying the integration and querying of diverse, heterogeneous geospatial datasets.

## Problem Characterization
The challenge addressed in this paper is conducting geospatial analysis across datasets from various domains, each in different formats and resolutions. This heterogeneity makes it difficult to derive meaningful insights without extensive preprocessing and integration efforts. TerraLink leverages modern big data technologies to address these challenges.

## Dominant Approaches
The paper discusses existing methods and their limitations, such as "Extending the YAGO2 Knowledge Graph with Precise Geospatial Knowledge" and "A Heterogeneous Geospatial Data Retrieval Method Using Knowledge Graph". TerraLink builds upon these methods by integrating multi-domain datasets using spatial geometry and queries.

## Methodology
The methodology involves data collection, preprocessing, utilizing big data frameworks, constructing a base knowledge graph, enriching the graph, and performing SQL queries. TerraLink uses hierarchical boundaries for the base spatial graph and integrates various datasets to enhance the knowledge graph.

## Experimental Benchmarks
### Graph Construction and Enrichment
The base graph comprised a substantial count of vertices and edges, which exponentially increased upon enrichment, signaling successful integration of additional datasets.

### Relationship Type Distribution
The enriched graph had a significantly higher proportion of many-to-many relationships compared to the base graph, indicating improved capability to model complex interactions between various geospatial entities.

### Degree Distribution
The enriched graph displayed a wider and more varied degree distribution, beneficial for graph traversals and allowing for a more in-depth discovery of spatial correlations.

### PageRank Benchmarking
PageRank scores highlighted significant nodes and unveiled issues such as namespace collisions, which were addressed to improve the knowledge graph's accuracy.

### Query Performance
Various SQL queries were executed through GraphFrames to test the querying potential of the graph.

### Motif Discovery
Motif discovery tests evaluated how recurring patterns within the knowledge graph can be used to reveal geospatial interconnections.

### Integration Execution Times
The time taken to integrate datasets varied, with more complex geometries taking longer. Spatial Hierarchy Mapping was introduced to optimize this process.

### Spatial Hierarchy Mapping
This technique reduced the number of edges and node connections created during integration, improving computational efficiency.

## Challenges
Challenges included addressing namespace collisions and optimizing the integration of datasets with complex geometries.

## Insights
The project revealed the importance of pre-computed knowledge graphs for efficient spatial querying and highlighted the potential of Spatial Hierarchy Mapping in reducing computational overhead.

## Future Prospects
Future directions for TerraLink include adding more diverse datasets, improving query functionalities, and incorporating novel spatial relationship types to broaden the scope of intuitive queries.

## Conclusion
TerraLink demonstrates the potential for integrating heterogeneous geospatial datasets into a comprehensive knowledge graph. The framework enhances spatial understanding, reduces computational inefficiencies, and supports advanced query performance, with practical implications for environmental monitoring and urban planning.

## Acknowledgments
Thanks to Dr. Shrideep Pallickara at Colorado State University for the amazing class and the GTA’s for their support. We also thank the Urban Sustain Project for supplying crucial datasets.

## References
Please refer to the paper for the full list of references.
