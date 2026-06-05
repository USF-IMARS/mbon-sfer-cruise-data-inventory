# MBON+SFER Cruise Data Inventory


## Setup
1. open a terminal in IMaRS JupyterHub (or similar) environment.
<<<<<<< Updated upstream
2. `gh auth login` & follow the prompts to authenticate. Choose "https".
3. `git clone https://github.com/USF-IMaRS/mbon-sfer-cruise-data-inventory.git` to get the repository.
4. `cd mbon-sfer-cruise-data-inventory` to change directory into the repository.
5. `git status` to verify up-to-date.
6. Open files, run, & edit in JupyterHub.
=======
2. `gh auth login` & follow the prompts to authenticate.
3. `git clone https://github.com/USF-IMaRS/mbon-sfer-cruise-data-inventory.git` to get the repository.
4. `cd mbon-sfer-cruise-data-inventory` to change directory into the repository.
5. `git status` to verify up-to-date.
6. `find . -name '*.qmd' -exec jupytext --to ipynb {} \;` to generate `.ipynb` files from `.qmd` files.
7. Open `.ipynb` files, run, & edit in JupyterHub.


## Editing
This repository is set up for editing of `.ipynb` files for JupyterHub features, conversion of `.ipynb` files to `.qmd` files for pretty `git` commits, and `quarto` rendering of a website.
>>>>>>> Stashed changes
