# Data files

The actual data is not under version control (large files). 

## How to get the data

It assumed that you are running in an environment where the `kaggle` script is available (i.e. you have run `pipenv install` and `pipenv shell`).

``` bash
> cd PetFinder/data
> kaggle competitions download -c petfinder-adoption-prediction
> unzip *.zip  # Run from this `data` folder
```
