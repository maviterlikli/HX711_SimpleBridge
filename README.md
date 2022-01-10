<div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- 
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
-->



<!-- PROJECT LOGO 
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</div>
-->


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

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

This is a simple PCB that is designed to work with commonly found HX711 Arduino module. So, this is an extension to the original HX711 module shown below.

This is still under work. Design is finished. However, I am still writing the manual. As you can see, even for first grade electronical engineering students, there is actually nothing hard or important about this repo, since this is a simple wheatstone bridge for HX711 module. However, while I work in my university, several students from computer sciences and engineering departments required a simple wheatstone bridge for strain gauge applications. This was a design for a really primative strain reader. It will not be useful in data acquisition applications, but it will help you learn if you are a new starter to strain gauge applications. It will, also, give you a great trick to easily calibrate your system or readings. A calibration that does not only calibrates the IC, but calibrates the whole system.

<b>Why do you need a PCB when you can do new-starter-things on breadboard?</b>

Since wheatstone bridges are really sensitive, it is imposible to acquire data on breadboards. If you like to see why, build a wheatstone bridge on breadboard with any 24bit ADC and softly blow on the breadboard. The readings will go crazy. Also, any use of standard breadboard jumpers will have the same efect. This SIMPLE one sided PCB is to minimize such enviromental effect. 


<b>BE CAREFUL!</b>
<br>
This PCB is designed to work with HW-27 Arduino module. However, it will work for the modules that has the same "J1" (see picture below) pin configuration.

![Module](images/HX711.jpg)

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

The design and shematics are made in Eagle. I aim to add universal data packages as well. However, if you would like to change the dimensions, packages, or anything else, Eagle is a free software right now.

* [Eagle](https://www.autodesk.com/products/eagle/free-download)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
First of all, you need to know basics of wheatstone bridge, and calculations. If you dont know where to start, HBM provides a good start-up knowledge [here](https://www.hbm.com/en/7163/wheatstone-bridge-circuit/). If you already have another source, you can use that as well, but be careful of resistor names, exitation points and reading points. They will vary.

There are several ways to use the PCB. It mainly depends on your budget and requried output quality. NO DOT FORGET that, HX711 is not an IC that a medium or advanced strain reader can be designed from.

### Prerequisites

### Installation


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Fahri Emre Özdemir - [@linkedin](https://www.linkedin.com/in/fahriemreozdemir/)

Project Link: [HX711_SimpleBridge](https://github.com/maviterlikli/HX711_SimpleBridge/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/maviterlikli/HX711_SimpleBridge/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/maviterlikli/HX711_SimpleBridge/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/maviterlikli/HX711_SimpleBridge/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/maviterlikli/HX711_SimpleBridge/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/maviterlikli/HX711_SimpleBridge/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/fahriemreozdemir
[product-screenshot]: images/screenshot.png
