<br/>
<p align="center">
  <a href="https://github.com/dhbwmowro/computer-vision-pipeline">
    <img src="images/mowro_logo.png" alt="Logo" width=230 style="border-radius:6px0">
  </a>

  <h3 align="center">Mowro Computer Vision Pipeline</h3>

  <p align="center">
    An awesome computer vision pipeline to enable autonomous driving of our robot !
    <br/>
    <br/>
    <a href="https://github.com/dhbwmowro/computer-vision-pipeline"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://trello.com/b/mTT1iq3v/kanban-template">Go to Trello</a>
    .
    <a href="https://github.com/dhbwmowro/computer-vision-pipeline/issues">Report Bug</a>
    .
    <a href="https://github.com/dhbwmowro/computer-vision-pipeline/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/dhbwmowro/computer-vision-pipeline/total) ![Contributors](https://img.shields.io/github/contributors/dhbwmowro/computer-vision-pipeline?color=dark-green) ![Forks](https://img.shields.io/github/forks/dhbwmowro/computer-vision-pipeline?style=social) ![Issues](https://img.shields.io/github/issues/dhbwmowro/computer-vision-pipeline) ![License](https://img.shields.io/github/license/dhbwmowro/computer-vision-pipeline) 

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [About The Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
  - [Creating A Pull Request](#creating-a-pull-request)
- [License](#license)
- [Authors](#authors)

## About The Project

This project contains the machine learning pipeline for training a model used for image segmentation. Subsequently, this model can be deployed on the Nvidia Jetson computer purchased for this project and, in combination with the driving logic, forms the basis for the autonomous driving of the robot.

## Built With

* Kedro 

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

-  [Miniconda](https://docs.conda.io/en/latest/miniconda.html) 
 ```bash
   # works on macos only
    brew install miniconda 
    
  # for window refer to the official documentation
 ```
- [Kedro](https://kedro.readthedocs.io/en/stable/index.html)
 ```bash
    conda install -c conda-forge kedro
 ```

### Installation

1. Clone the repository

 ```bash
    git clone https://github.com/dhbwmowro/computer-vision-pipeline
```

2. Install all requirements
 ```bash
    kedro install
 ```


## Roadmap

See the [open issues](https://github.com/dhbwmowro/computer-vision-pipeline/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/dhbwmowro/computer-vision-pipeline/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/dhbwmowro/computer-vision-pipeline/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.
* Don't remove any lines from the `.gitignore` file we provide
* Make sure your results can be reproduced by following a [data engineering convention](https://kedro.readthedocs.io/en/stable/12_faq/01_faq.html#what-is-data-engineering-convention)
* Don't commit data to your repository
* Don't commit any credentials or your local configuration to your repository. Keep all your credentials and local configuration in `conf/local/`


### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/ShaanCoding/Mowro Computer Vision Pipeline/blob/main/LICENSE.md) for more information.

## Authors

* [Felix Behne](https://github.com/FelixBehne)
* [Milan Wosel](https://github.com/mpingus)

