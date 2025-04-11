# Supplemental material for the paper Traveling with a Map: Optimizing the Search Space of Link Traversal Queries Using RDF Data Shapes

This repository provides a guide to the Supplementary material available.

## Open Source Software
- [Comunica SPARQL Query Engine with Shape-Index Support](https://github.com/constraintAutomaton/comunica-feature-link-traversal/tree/feature/shapeIndex)
- [Query-Shape Subsumption Solver](https://github.com/constraintAutomaton/query-shape-detection/)
- [Shape-Index Generator](https://github.com/constraintAutomaton/rdf-dataset-fragmenter.js/tree/feature/shape-index-fragmentation-strategy)
- [Benchmark and Query Template](https://github.com/SolidBench/SolidBench.js)

## Analysis of results
The [analysis repository](https://github.com/shapeIndexComunicaExperiment/analysis) generates the figures for the paper 
*Traveling with a Map: Optimizing the Search Space of Link Traversal Queries Using RDF Data Shapes*, along with additional figures.


## Results 
The official results of the paper are presented in the [results repository](https://github.com/shapeIndexComunicaExperiment/results)

## Experiments

Multiple experiment repositories have been created to facilitate their execution in multiple machines.
The queries used are the same across all experiments and are available in their respective `./queries` folder.
The following line provides a brief description of the experiment and a link to the git repository.

- [Analysis of query-shape subsumption algorithm](https://github.com/shapeIndexComunicaExperiment/ltqp-shape-alignment-analysis)


- [Oracle of source selection](https://github.com/shapeIndexComunicaExperiment/source-selection-oracle)


- [Shape index and state-of-the-art approach comparison](https://github.com/shapeIndexComunicaExperiment/standard-experiment)


- [Shape index approach in a network with no shape index](https://github.com/shapeIndexComunicaExperiment/shape-index-0-percent-dataset)
- [Shape index approach in a network where 20% of the datasets expose a shape index](https://github.com/shapeIndexComunicaExperiment/shape-index-20-percent-dataset)
- [Shape index approach in a network where 50% of the datasets expose a shape index](https://github.com/shapeIndexComunicaExperiment/shape-index-50-percent-dataset)
- [Shape index approach in a network where 80% of the datasets expose a shape index](https://github.com/shapeIndexComunicaExperiment/shape-index-80-percent-dataset)


- [Shape index approach in a network where 20% of the shape index entries are closed shapes](https://github.com/shapeIndexComunicaExperiment/shape-index-20-percent-entries)
- [Shape index approach in a network where 50% of the shape index entries are closed shapes](https://github.com/shapeIndexComunicaExperiment/shape-index-50-percent-entries)
- [Shape index approach in a network where 80% of the shape index entries are closed shapes](https://github.com/shapeIndexComunicaExperiment/shape-index-80-percent-entries)


- [Shape index approach in a network where the datasets use shape with only information from the internal data model](https://github.com/shapeIndexComunicaExperiment/shape-inner-dataset-experiment)

- [Shape index approach in a network where the datasets use shape with minimal information](https://github.com/shapeIndexComunicaExperiment/shape-minimal-description-experiment)
