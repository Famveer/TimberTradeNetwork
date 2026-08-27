# TimberTradeNetwork

This repository contains timber transportation data for the IPE wood species from 2010 to 2020.  [Paper](https://fmorenovr.github.io/documents/articles/journals/2025_NATSUSTAIN.pdf).

# Requirements

- **Python**>=3.12

# Installation
```
  pip install -r requirements.txt
```

# Data

The `transports.csv` columns account for:

- 'id_wood': id of the IPE species. It matches the column 'id_wood' in the file `species.csv`.
- 'node_src' and 'node_dest': id of the enterprise of origin and destination of the wood. They match the column "id_emp" in the file `nodes.csv`. 
- 'vol': volume of timber transported in cubic meters.
- 'id_product': id of the product type. It matches the column "id_product" in the file `products.csv`.
- 'date': the transportation date.


### Experiment

* The Notebook `notebooks/TTN.ipynb` contains a code to build the _Timber Trade Network_ and to compute the _k most likely supply chains_ of a given enterprise.

# Citation

```
@article{nonato2025assessing,
  title={Assessing timber trade networks and supply chains in Brazil},
  author={Nonato, Luis Gustavo and Russo, Victor and Costa, Bernardo and Moreno-Vera, Felipe and Toledo, Guilherme and de Jesus, Osni Brito and Vieira, Robson and Lentini, Marco and Poco, Jorge},
  journal={Nature Sustainability},
  volume={8},
  number={2},
  pages={215--220},
  year={2025},
  publisher={Nature Publishing Group UK London}
}
```

# Contact us  
For any issue please kindly email to `felipe [dot] moreno [at] fgv [dot] br` or `gnonato [at] icmc [dot] usp [dot] br`

