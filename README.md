# hacklytics-2020
## A submission to the Hacklytics data science hackathon
A description of the project

## Conda
### Setting up environment
1. Install conda
2. Run `conda env create -f environment.yml`
3. Activate the environment with the command `conda activate hacklytics`

### Updating environment
1. Activate the environment with the command `conda activate hacklytics`
2. Run `conda env update -f environment.yml`

### Installing new packages and exporting environment
1. Run `conda activate hacklytics`
2. To install new packages, run `conda install [PACKAGENAME]`
3. To export conda config `conda env export --from-history > environment.yml`
