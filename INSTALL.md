# Environment Setup

Use the python environment manager of your choice. These instructions will use the `conda` command,
installed via `miniconda`. Most commands will install packages from the `conda-forge` channel.


### Create and activate the virtual environment
```shell script
(base) conda create -n teaching python=3.7
(base) conda activate teaching
```

### Install open-source packages 

#### General tooling
```shell script
(teaching) conda install -c conda-forge ipython
(teaching) conda install -c conda-forge jupyter
(teaching) conda install -c conda-forge jupytext
```

#### Data analysis 
```shell script
(teaching) conda install -c conda-forge geopandas
(teaching) conda install -c conda-forge seaborn
```

#### Database 
```shell script
(teaching) conda install -c conda-forge pyscopg2
(teaching) conda install -c conda-forge geoalchemy2
```

#### Excel 
```shell script
(teaching) conda install -c conda-forge xlrd
(teaching) conda install -c conda-forge xlsxwriter
```

# IDE Setup
After building your `conda` environment, create a new project in PyCharm from this
repo's parent folder. Open the IDE settings and point the project interpreter to 
the one you just created.