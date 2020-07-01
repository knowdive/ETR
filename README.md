# ETR
KR2020 Conference Paper - Data and processes 

## Process

Use the .xml process to run ETR full pipeline. 

Use [RapidMiner](https://rapidminer.com/) + the [Text Proecessing](https://marketplace.rapidminer.com/UpdateServer/faces/product_details.xhtml?productId=rmx_text) extension to run the process.

## Files

Each file encodes the portion of the reference KB used in the experiments (i.e., Schema.org, SUMO, OpenCyc and DBpedia)


## Usage

```
import ETR.v00
import (schema.xlsx | SUMO.xlsx | opencyc.xlsx | DBpedia.xlsx) 
select the types to be recognized (filter domain predicate or use "select attributes" operator)
# returns prediction accuracy + confusion matrix 
```

## Contributing

If you found this resources helpful, please consider citing:

[Entity Type Recognition – dealing with the Diversity of Knowledge] - Principles of Knowledge Representation and Reasoning: Proceedings of the Seventeenth International Conference, KR 2020

