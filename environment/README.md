# Environment ads505fp.yml

Conda is used to manage the environment for this project. 
[https://anaconda.org/anaconda/conda](https://anaconda.org/anaconda/conda)

## Install Environment
Use conda to create the `ads505fp` environment. 

```bash 
conda env create --file environment/ads505fp.yml 
```
Use the command as is if installing from the root directory. Otherwise, enter the correct path. 
## Activate Environment

```bash
conda activate ads505fp
``` 

## Update Environment

```bash
conda env update --file <path to environment.yml> --prune
```

## Clean up and Prune Unused Packages

To clean up unused packages and cache after installing or updating environment:
```bash 
conda clean --all
```