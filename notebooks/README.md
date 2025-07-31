You will find all lecture notes here that are mostly written in Jupyter Notebook where you will find example python scripts that you may later use in your homeworks and final projects.
# Run on your laptop (required for grad students) or [Google Colab]([https://mybinder.org/](https://colab.research.google.com/))
## Install conda environment
```bash
cd ..
conda env create -f environment.yml
conda activate MARN-3060
python -m ipykernel install --user --name MARN-3060 --display-name "Python (MARN-3060)"
conda env list
```
## Run jupyternotebook
on your laptop: 
```bash
jupyter lab
```
on Google Colab:\
You need a google account\
The easiest way is to go File -> Open Notebook -> GitHub -> enter "https://github.com/ShuwenTan-PO/MARN-3060"
