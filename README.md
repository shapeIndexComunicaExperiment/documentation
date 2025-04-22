# Supplemental material for the paper Traveling with a Map: Optimizing the Search Space of Link Traversal Queries Using RDF Data Shapes

This repository provides a guide to the complementary material available.


## Additional Analysis of the Subsumption Algorithm

Detailed analysis of the $subsums_{\mathrm{graph\ star}}$ time complexity and the complete resolution algorithm can be found [here](https://anonymous.4open.science/r/time-complexity-9E73/README.md).


## Open Source Software
- [Comunica SPARQL Query Engine with Shape-Index Support](https://anonymous.4open.science/r/comunica-feature-link-traversal-AE1C)
- [Query-Shape Subsumption Solver](https://anonymous.4open.science/r/query-shape-detection-ED87/)
- [Shape-Index Generator](https://anonymous.4open.science/r/rdf-dataset-fragmenter_js-08B9)
- [Benchmark Data and Query Templates](https://github.com/SolidBench/SolidBench.js)

## Analysis of results
The [analysis repository](https://anonymous.4open.science/r/analysis-85DE/) generates the figures for the paper 
*Traveling with a Map: Optimizing the Search Space of Link Traversal Queries Using RDF Data Shapes*, along with additional figures.

## Results 
The official results of the paper are presented in the [results repository](https://anonymous.4open.science/r/results-E86D)

## Experiments

Multiple experiment repositories have been created to facilitate their execution in multiple machines.
The queries used are the same across all experiments and are available in their respective `./queries` folder.
The following line provides a brief description of the experiment and a link to the git repository.

- [Analysis of query-shape subsumption algorithm](https://anonymous.4open.science/r/query-shape-detection-ED87)


- [Oracle of source selection](https://anonymous.4open.science/r/source-selection-oracle-3231)


- [Shape index and state-of-the-art approach comparison](https://anonymous.4open.science/r/standard-experiment-16E0)


- [Shape index approach in a network with no shape index](https://anonymous.4open.science/r/shape-index-0-percent-dataset-0318)
- [Shape index approach in a network where 20% of the datasets expose a shape index](https://anonymous.4open.science/r/shape-index-20-percent-dataset-4352)
- [Shape index approach in a network where 50% of the datasets expose a shape index](https://anonymous.4open.science/r/shape-index-50-percent-dataset-C2A8)
- [Shape index approach in a network where 80% of the datasets expose a shape index](https://anonymous.4open.science/r/shape-index-80-percent-dataset-EDFD)


- [Shape index approach in a network where 20% of the shape index entries are closed shapes](https://anonymous.4open.science/r/shape-index-20-percent-entries-03F0)
- [Shape index approach in a network where 50% of the shape index entries are closed shapes](https://anonymous.4open.science/r/shape-index-50-percent-entries-C1FC)
- [Shape index approach in a network where 80% of the shape index entries are closed shapes](https://anonymous.4open.science/r/shape-index-80-percent-entries-A9D7)


- [Shape index approach in a network where the datasets use shape with only information from the internal data model](https://anonymous.4open.science/r/shape-inner-dataset-experiment-74FC)

- [Shape index approach in a network where the datasets use shape with minimal information](https://anonymous.4open.science/r/shape-minimal-description-experiment-15B5)
