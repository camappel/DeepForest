<div align="center">
    <h6>Environmental Data Science Book</h6>
</div>

<p align="center">
<img src="https://github.com/alan-turing-institute/environmental-ds-book/blob/master/book/figures/logo/logo.png?raw=True" alt="thumbnail" width="200"/>
</p>

<div align="center">
    <h1>Livestock detection using DeepForest</h1>
</div>

<p align="center">
    <a href="https://github.com/eds-book-gallery/[repository name]/blob/main/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg">
    </a>
    <a href="http://mybinder.org/v2/gh/eds-book-gallery/95199651-9e81-4cae-a3a7-66398a9a5f62/main?labpath=notebook.ipynb">
        <img alt="Binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://github.com/eds-book-gallery/95199651-9e81-4cae-a3a7-66398a9a5f62/actions/workflows/render.yaml/badge.svg">
        <img alt="Continuous integration badge" src="https://github.com/eds-book-gallery/95199651-9e81-4cae-a3a7-66398a9a5f62/actions/workflows/render.yaml/badge.svg">
    </a>
    <br/>
</p>

# How to run

## Running on Binder
The notebook is designed to be launched from Binder. 

Click the **Launch Binder** button at the top level of the repository

## Running locally
You may also download the notebook from GitHub to run it locally:
1. Open your terminal

2. Check your conda install with `conda --version`. If you don't have conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html))

3. Clone the repository
    ```bash
    git clone https://github.com/eds-book-gallery/95199651-9e81-4cae-a3a7-66398a9a5f62.git
    ```

4. Move into the cloned repository
    ```bash
    cd 95199651-9e81-4cae-a3a7-66398a9a5f62
    ```

5. Create and activate your environment from the `.binder/environment.yml` file
    ```bash
    conda env create -f .binder/environment.yml
    conda activate 95199651-9e81-4cae-a3a7-66398a9a5f62
    ```  

6. Launch the jupyter interface of your preference, notebook, `jupyter notebook` or lab `jupyter lab`

# Credits
The **How to run** section was adapted from the [Project Pythia Cookbook](https://cookbooks.projectpythia.org/) project.