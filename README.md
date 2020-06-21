# ETR
KR2020 Conference Paper - Data and processes 

## Process

Use the .xml process to run ETR full pipeline. 

Use [RapidMiner](https://rapidminer.com/) + the [Text Proecessing](https://marketplace.rapidminer.com/UpdateServer/faces/product_details.xhtml?productId=rmx_text) extension to run the process.

## Files

Each file encode the portion of the reference KGB used in the experiments (i.e., Schema.org, SUMO, OpenCyc and DBpedia)


## Usage

```
import ETR.v00
import (schema.xlsx | SUMO.xlsx | opencyc.xlsx | DBpedia.xlsx) # returns prediction accuracy + confusion matrix 
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
