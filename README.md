<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">

  <a href="https://github.com/OSCGRA/blue-and-gold">
    <img src="https://github.com/OSCGRA/blue-and-gold/assets/77927558/dccb0804-25b1-4013-8eba-bf51230afd79" alt="Logo" width="350" height="350">
  </a>

<h3 align="center">BLUE & GOLD</h3>

  <p align="center">
    Working towards connectography concept in UE 
    <br />
    <a href="https://github.com/OSCGRA/blue-and-gold"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/OSCGRA/blue-and-gold/blob/main/Blue%20%26%20Gold%20(New).ipynb">View Demo</a>
    
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


<div align="center">
  <img src="https://github.com/OSCGRA/blue-and-gold/assets/77927558/c87f6c15-edc7-496e-8b61-a523f0c9b3d3"     
   alt="Blue&Gold" width="500" height="500" class="centered-image">
</div>
<br />
This data visualization project aims to explore and depict the distribution of the Blue Banana and Gold Banana in Europe, incorporating the concept of sea connectography flows. The project utilizes data provided by Eurostat and represents it within NUTS (Nomenclature of Territorial Units for Statistics) regions.

The Blue Banana denotes a chain of highly urbanized and industrialized regions extending from southern England to northern Italy, traversing through Belgium, the Netherlands, Luxembourg, Germany, Switzerland, and France. The Gold Banana encompasses a broader swath of territory, encompassing regions in Spain and Portugal.

I(we) leverage datasets provided by Eurostat, the statistical office of the European Union, offering comprehensive socio-economic and geospatial information about Europe. This data is structured within NUTS regions, facilitating a hierarchical breakdown of territorial units for statistical analysis.

<strong>Integration with Sea Connectography Flows:</strong>

In addition to examining the socio-economic dynamics within the Blue Banana and Gold Banana, this project incorporates the connectography flows to visualize tge influence on economic activities and regional development, by integrating  data.

<strong>Exploring Conceptual Questions:</strong>

**Is Blue Banana a Real Phenomenon?:** We delve into the debate surrounding the Blue Banana, examining whether it constitutes a real geographical and economic pentagram, particularly considering the inclusion of metropolitan areas like Berlin and Paris within its framework.

**Relation between Blue Banana and Gold Banana:** We scrutinize the relationship between the Blue Banana and the Gold Banana, assessing whether the latter can be perceived as an extension of the former, or if they represent distinct socio-economic corridors with unique characteristics

<strong>Project Objective:</strong>

Our overarching goal is to create an interactive visualization platform that illustrates both, conectivity and phisical, dimensions of the Blue Banana and Gold Banana regions. Through this holistic approach, we seek to uncover patterns of economic development, trade flows, cultural exchanges, political and social patterns and digital spaces complementing our understanding of land-based connectivity.

**Technologies Used:**

Python: for data manipulation and analysis.
Pandas, NumPy: for data cleaning and processing.
Matplotlib, Seaborn: for creating static charts.
Plotly, Folium: for generating interactive visualizations, including maps with maritime routes.
Jupyter Notebook: for exploratory data analysis and visualization prototyping.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Vue][Vue.js]][Vue-url]
* [![Angular][Angular.io]][Angular-url]
* [![Svelte][Svelte.dev]][Svelte-url]
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

  ```sh
    pip install eurostatapiclient 
  ```
or:
  ```sh
    conda install eurostatapiclient 
  ```

### Installation

1. API Cofiguration:
   ```sh
    from eurostatapiclient import EurostatAPIClient
   
    VERSION = '1.0'
    FORMAT = 'json' 
    LANGUAGE = 'en'
   ```
2. Clone the repo
   ```sh
    git clone https://github.com/OSCGRA/blue-and-gold.git
   ```
3. Install NPM packages
   ```sh
    pip install geopandas
    pip install geoplot
   ```
4. Enter the dataset code from Eurostad database: (example: met_gind3)
   ```js
    dataset = client.get_dataset('met_gind3')
    print(dataset.label)
    df = dataset.to_dataframe();
   ```
<a href="https://ec.europa.eu/eurostat/web/main/data/database">EUROSTAT Database</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the Apache 2.0 License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - Oscar Reinoso - oscarmanuel.re@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Attribution of eurostatapiclient: https://github.com/opus-42/eurostat-api-client
  

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
