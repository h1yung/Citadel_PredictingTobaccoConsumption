<!-- Find and Replace All [repo_name] -->
<!-- Replace [product-screenshot] [product-url] -->
<!-- Other Badgets https://naereen.github.io/badges/ -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
<!-- [![License][license-shield]][license-url] -->

<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">citadel_predicting_tobacco_consumption</h3>

  <p align="center">
    Entry for the Citadel Central Datathon
    <br />
    <a href="https://github.com/h1yung/Citadel_PredictingTobaccoConsumption/blob/main/citadel_datathon.pdf">Paper</a>
    ·
    <a href="https://github.com/h1yung/Citadel_PredictingTobaccoConsumption/blob/main/datathon.ipynb">Code</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

We were able to devise regression models that, given the country and its MPOWER (national tobacco prevention efforts metric) scores, predicts population tobacco consumption to at least R2 = 0.92. Each model represents a cluster of countries. Region, or specifically country, seems to weigh into the changes in tobacco consumption with respect to MPOWER, as the score was R2 = 0.17 without. When we cluster all the countries, we’re able to increase this value to above 0.92 for each cluster.

## Usage

1. Using Google Colab, load your data and ipynb notebook onto Google Drive.
2. Adjust the file paths for reading in csv files according to where you store them in the Drive.
3. Use the models generated in the ipynb notebook.

<!-- CONTACT -->
## Contact

Daniel Park - [@h1yung][linkedin-url] - h1yungpark@gmail.com

Project Link: [https://github.com/h1yung/Citadel_PredictingTobaccoConsumption](https://github.com/h1yung/Citadel_PredictingTobaccoConsumption)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/h1yung/Citadel_PredictingTobaccoConsumption.svg?style=for-the-badge
[contributors-url]: https://github.com/h1yung/Citadel_PredictingTobaccoConsumption/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/h1yung/Citadel_PredictingTobaccoConsumption.svg?style=for-the-badge
[forks-url]: https://github.com/h1yung/Citadel_PredictingTobaccoConsumption/network/members
[stars-shield]: https://img.shields.io/github/stars/h1yung/Citadel_PredictingTobaccoConsumption.svg?style=for-the-badge
[stars-url]: https://github.com/h1yung/Citadel_PredictingTobaccoConsumption/stargazers
[issues-shield]: https://img.shields.io/github/issues/h1yung/Citadel_PredictingTobaccoConsumption.svg?style=for-the-badge
[issues-url]: https://github.com/h1yung/Citadel_PredictingTobaccoConsumption/issues
<!-- [license-shield]: 
[license-url]:  -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/fifadaniel/
