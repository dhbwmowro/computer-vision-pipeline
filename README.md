<!-- PROJECT LOGO -->
<p align="center">
   <a href="https://github.com/dhbwmowro/computer-vision-pipeline">
      <img src="./images/mowro_logo.png" alt="Logo" width=230 style="border-radius:6px">
      </a>
      <br/>
      <br/>
<h1 align="center">Mowro Computer Vision Pipeline</h1>
<p align="center">
A machine learning pipeline based on kedro to segement images on a nvidia jetson.
<br />
  <a  href="https://github.com/dhbwmowro/computer-vision-pipeline"><h3 align="center">Explore the docs »</h3></a>
</p>
</p>
<br />
<br />
<!-- TABLE OF CONTENTS -->
<details open="open">
   <summary>
      <h2 style="display: inline-block">Table of Contents</h2>
   </summary>
   <ol>
      <li>
         <a href="#about-the-project">Overview</a>
         <ul>
            <li><a href="#input-data">Input Data</a></li>
            <li><a href="#input-data">Thoughts on ML</a></li>
            <li><a href="#input-data">Target Variable</a></li>
            <li><a href="#input-data">Features</a></li>
         </ul>
      </li>
      <li>
         <a href="#getting-started">Getting Started</a>
         <ul>
            <li><a href="#prerequisites">Prerequisites</a></li>
            <li><a href="#installation">Installation</a></li>
         </ul>
      </li>
      <li><a href="#rules-and-guidelines">Rules and Guidelines</a></li>
      <li><a href="#authors">Authors</a></li>

   </ol>
</details>
<br/>
<br/>
<br/>
<!-- ABOUT THE PROJECT -->

## Overview 🌟


### Input Data


## Thoughts on ML


### Features


## Getting Started 🚀

To get a local copy up and running follow these simple steps.

### Prerequisites

- [Git Large File Storage](https://git-lfs.github.com/)

  ```sh
  # MacOs
    # Install git lfs
    brew install lfs  # MacOs only.

    # Add the extension to git
    git lfs install
  ```

- [Kedro](https://kedro.readthedocs.io/en/stable/index.html)

 ```bash
    # Pip
    pip install kedro

    # Conda
    conda install -c conda-forge kedro
 ```

## Installation

1. Clone the repository

 ```bash
    git clone https://github.com/dhbwmowro/computer-vision-pipeline
```

2. Install all requirements

 ```bash
    kedro install
 ```

3. Open the repository in vscode and install the extension requirements

4. Add a settings.json file in .vscode with the following content

 ```json

   {
      "python.pythonPath": "path to your python distribution",

      "files.exclude": {
         "**/images": true,
         "**/build": true,
         "**/dist": true,
         "**/src.egg-info": true,
         "**/.gitkeep": true,
         "**/__pycache__": true
         },
         "editor.formatOnSave": true,
         "python.formatting.provider": "black",
         "python.formatting.blackArgs": ["-v"],
         "autoDocstring.docstringFormat": "google"

        "yaml.schemas": {
            "https://raw.githubusercontent.com/quantumblacklabs/kedro/develop/static/jsonschema/kedro-catalog-0.17.json": "conf/**/*catalog*"
        }
   }
 ```

## Rules and guidelines 🧾

In order to get the best out of the template:

* Don't remove any lines from the `.gitignore` file we provide
* Make sure your results can be reproduced by following a [data engineering convention](https://kedro.readthedocs.io/en/stable/12_faq/01_faq.html#what-is-data-engineering-convention)
* Don't commit data to your repository
* Don't commit any credentials or your local configuration to your repository. Keep all your credentials and local configuration in `conf/local/`


## Authors 🤓

- [Felix Behne](https://github.com/FelixBehne)
- Milan Wosel
