# RPY

<!-- badges: start -->
<!-- badges: end -->

Author: [Rishika Mohanta](https://neurorishika.github.io/)
Latest Build Date: 2023-07-21 22:12:37

## About the Project

Project description is being updated. Please check back later.

## READ CAREFULLY

This is a [Poetry](https://python-poetry.org/)-enabled python project. Poetry installs a virtual environment in the project directory and all packages are installed in this virtual environment. This means that you do not need to install any packages in your system. The virtual environment is automatically activated when you run the project through Poetry. 

If you use [VS Code](https://code.visualstudio.com/), you can set the Python interpreter to the Poetry virtual environment `.venv` in the project directory for script execution and debugging and use the Poetry virtual environment `.venv` for the Jupyter kernel.

To run the project, make sure you have Poetry installed and run the following commands in the project directory:

```
poetry run python utils/update.py
poetry run python utils/build.py
```

To run the Jupyter notebook, run the following command in the project directory:

```
poetry run jupyter notebook
```

## Project Organization

The project is organized as follows:
```
.DS_Store\n.gitignore\nLICENSE\nREADME.md\nanalysis\n   |-- \x01gitkeep\n   |-- \x01ulse-learning-analysis.ipynb\ndata\n   |-- \x01DS_Store\n   |-- \x01gitkeep\n   |-- \x01ulStr_16-07-2023.ezip\n   |-- \x01ulStr_20-07-2023.ezip\ndirectory.path\nflyoptostim\n   |-- \x01_init__.py\n   |-- \x01dp_client.py\npoetry.lock\npoetry.toml\nprocessed_data\n   |-- \x01gitkeep\n   |-- \x01ulStr_20-07-2023\n   |   |-- \x01ootstrap_optimization_results_100.pkl\n   |   |-- \x01ootstrap_optimization_results_20.pkl\n   |   |-- \x01ootstrap_optimization_results_200.pkl\n   |   |-- \x01ootstrap_optimization_results_50.pkl\n   |   |-- \x01ootstrap_optimization_results_500.pkl\n   |   |-- \x01lobal_optimization_results.pkl\n   |-- \x01l_fit_boot.pkl\n   |-- \x01l_fit_go.pkl\npyproject.toml\nscripts\n   |-- \x01gitkeep\ntests\n   |-- \x01_init__.py\nutils\n   |-- \x01uild.py\n   |-- \x01uickstart.py\n   |-- \x01pdate.py\n```
