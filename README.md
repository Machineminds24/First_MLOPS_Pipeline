<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">CIFAR-10 Classification Pipeline with ClearML</h3>
  <p align="center">
    An automated MLOps workflow for CIFAR-10 dataset classification using ClearML
    <br />
    <a href="https://github.com/Machineminds24/First_MLOPS_Pipeline"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Machineminds24/First_MLOPS_Pipeline/issues">Report Bug</a>
    ·
    <a href="https://github.com/Machineminds24/First_MLOPS_Pipeline/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project automates the process of managing a dataset, training and evaluating a convolutional neural network (CNN) on the CIFAR-10 dataset using ClearML. It encompasses the complete MLOps lifecycle from data preprocessing to model training, evaluation, and logging of metrics and outputs for efficient tracking and analysis.

### Built With

![Python][Python.org]
[![OpenCV][OpenCV.org]][OpenCV-url]
[![ClearML][ClearML-badge]][ClearML-url]
[![TensorFlow][TensorFlow-badge]][TensorFlow-url]
[![Matplotlib][Matplotlib-badge]][Matplotlib-url]
[![NumPy][NumPy-badge]][NumPy-url]
[![Poetry][Poetry-badge]][Poetry-url]
[![Seaborn][Seaborn-badge]][Seaborn-url]

### Works With
<!-- BADGES -->

[![Google Colab][GoogleColab-badge]][GoogleColab-url]
[![AWS SageMaker Studio][AWSSageMaker-badge]][AWSSageMaker-url]


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- Python 3.9+
- Poetry for Python package management

### Installation

1. Install Poetry:
   ```sh
   curl -sSL https://install.python-poetry.org | python3 -
   ```
   OR (following for AWS)
   ```sh
   curl -sSL https://install.python-poetry.org | POETRY_HOME=/root/poetry python3 -
   ```
3. Clone the repo:
    ```sh
   git clone https://github.com/Machineminds24/First_MLOPS_Pipeline.git

   cd First_MLOPS_Pipeline
   ```

4. Install dependencies using Poetry:
    ```sh 
   poetry install
   ```

5. Activate the Poetry shell:
    ```sh
   poetry shell
   ```

6. **IMPORTANT:** Edit the pipeline default parameters and make a repository for deployment weights to be stored in, configure a deploy key for it, save it in a file and put the path of the file in the .env file. Sample project here, please **fork**: [https://github.com/Machineminds24/Cifar10_SimpleFlaskApp](https://github.com/GitarthVaishnav/Cifar10_SimpleFlaskApp) | DON'T push to this project, pipeline will FAIL.

7. Run the pipeline:
    ```sh
   python -m first_mlops_pipeline
   ```

<!-- USAGE -->
## Usage

Use this pipeline to kickstart your project with basic image classification. You may experiment with different preprocessing techniques, or integrate additional steps into the pipeline as needed.


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Gitarth Vaishnav - [@Machineminds24](https://linkedin.com/in/gitarthvaishnav)

Email: Gitarthv@outlook.com | Gitarth.Vaishnav@uts.edu.au


Github Link: [@Machineminds24](https://github.com/Machineminds24/)

Project Link: [https://github.com/Machineminds24/First_MLOPS_Pipeline](https://github.com/GitarthVaishnav/First_MLOPS_Pipeline)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Machineminds24/First_MLOPS_Pipeline.svg?style=for-the-badge
[contributors-url]: https://github.com/Machineminds24/First_MLOPS_Pipeline/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Machineminds24/First_MLOPS_Pipeline.svg?style=for-the-badge
[forks-url]: https://github.com/Machineminds24/First_MLOPS_Pipeline/network/members
[stars-shield]: https://img.shields.io/github/stars/Machineminds24/First_MLOPS_Pipeline.svg?style=for-the-badge
[stars-url]: https://github.com/Machineminds24/First_MLOPS_Pipeline/stargazers
[issues-shield]: https://img.shields.io/github/issues/Machineminds24/First_MLOPS_Pipeline.svg?style=for-the-badge
[issues-url]: https://github.com/Machineminds24/First_MLOPS_Pipeline/issues
[license-shield]: https://img.shields.io/github/license/Machineminds24/First_MLOPS_Pipeline.svg?style=for-the-badge
[license-url]: https://github.com/Machineminds24/First_MLOPS_Pipeline/blob/master/LICENCE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/gitarthvaishnav
[Python.org]:https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://python.org
[OpenCV.org]:https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white
[OpenCV-url]: https://opencv.org/
[Python.org]:https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://python.org
[OpenCV.org]:https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white
[OpenCV-url]: https://opencv.org/
[GoogleColab-badge]: https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252
[GoogleColab-url]: https://colab.research.google.com/
[AWSSageMaker-badge]: https://img.shields.io/badge/AWS%20SageMaker-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white
[AWSSageMaker-url]: https://aws.amazon.com/sagemaker/
[ClearML-badge]: https://img.shields.io/badge/ClearML-%23FF6F00.svg?style=for-the-badge&logo=clearml&logoColor=white
[ClearML-url]: https://clear.ml/
[TensorFlow-badge]: https://img.shields.io/badge/TensorFlow-%23FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white
[TensorFlow-url]: https://tensorflow.org/
[Matplotlib-badge]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=matplotlib&logoColor=black
[Matplotlib-url]: https://matplotlib.org/
[NumPy-badge]: https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/
[Poetry-badge]: https://img.shields.io/badge/Poetry-%235A2A82.svg?style=for-the-badge&logo=poetry&logoColor=white
[Poetry-url]: https://python-poetry.org/
[Seaborn-badge]: https://img.shields.io/badge/Seaborn-%23150458.svg?style=for-the-badge&logo=seaborn&logoColor=white
[Seaborn-url]: https://seaborn.pydata.org/
