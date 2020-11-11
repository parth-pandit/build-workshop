[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Apache 2.0 License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![LinkedIn][linkedin-shield]][linkedin-url2]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/rhardt-pivotal/build-workshop">
    <img src="images/tanzu-bug.svg" width=80 height=80 alt="Logo" >
  </a>

  <h3 align="center">Tanzu Build Workshop</h3>

  <p>
    This is a comprehensive workshop covering the creation of a professional, reliable and secure deployable artifact and Kubernetes deployment for your Java Spring application.  This workshop will take you from a simple naive Dockerfile, eventually arriving at a secure, modular, streamlined, and up-to-date deployable OCI-compliant image and Kubernetes deployment.  This is based on <a href="https://adibsaikali.com/" target="adib">Adib Saikali's</a> excellent QCon Plus session <i>Effective Spring + Kubernetes</i>
    <br />
    <br />
    <a href="https://github.com/rhardt-pivotal/build-workshop/"><strong>Start Here »</strong></a>
    <br />
    <br />
    <a href="https://github.com/rhardt-pivotal/build-workshop">View Demo</a>
    ·
    <a href="https://github.com/rhardt-pivotal/build-workshop/issues">Report Bug</a>
    ·
    <a href="https://github.com/rhardt-pivotal/build-workshop/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Introduction](#intro)
* [Intended Audience](#audience)
* [Prerequisite Skills](#prerequisite-skills)
* [Required Tools](#required-tools)
* [Environment](#environment)
* [Validate Tools and Environment](workshop/0010-validate-tools-and-environment/README.md)
* [Build Workshop](workshop/00-validate-tools-and-environment.md)
  * Part 1: Setup and Java Runtimes
    * [Validate Tools and Environment](workshop/0010-validate-tools-and-environment/README.md)
    * [A Simple Naïve JDK Image From Scratch](workshop/0020-simple-naive-image-from-scratch/README.md)
    * [Java Base Images](workshop/0030-java-base-images/README.md)
    * [Java Versions](workshop/0040-java-versions/README.md)
  * Part 2: Application Images with Docker
    * [Single-Layer Spring Boot App](workshop/0050-single-layer-java-app/README.md)
    * [Multi-Layer Spring Boot App](workshop/0060-multi-layer-java-app/README.md)
    * [Spring Boot LayerTools](workshop/0070-layertools/README.md)
  * Part 3: Cloud Native Buildpacks
    * [Local Buildpacks](workshop/0080-local-buildpacks/README.md) <!-- ideally we do it with the pack CLI and the maven task -->
    * [On-Platform Buildpacks - KPack ](workshop/0090-on-platform-buildpacks-kpack/README.md)
    * [On-Platform Buildpacks - Tanzu Build Service ](workshop/0095-on-platform-buildpacks-tbs/README.md)
  * Part 4: K8s Cluster Provisioning
    * [K8s-the-hard-way](workshop/0100-k8s-the-hard-way/README.md)
    * [K8s-the-easy-way](workshop/0110-k8s-the-easy-way/README.md)
  * Part 5: Deploying to Kubernetes
    * [Spring Boot Features for Kubernetes](workshop/0120-spring-boot-features-for-kubernetes/README.md)
    * [Spring Cloud Kubernetes](workshop/0130-spring-cloud-kubernetes/README.md)
  * Part 6: Optimizing JVM Settings for Containers
    * [Available Processors](workshop/0140-available-processors/README.md)
    * [CPU Requests and Limits](workshop/0150-cpu-ram-requests-and-limits/README.md)
  * Part 7: 
    * [Wrap Up](workshop/0160-wrapup/README.md)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## Intro

[![Build Workshop Screen Shot][product-screenshot]](https://github.com/rhardt-pivotal/build-workshop)



## Audience
the audience

## Prerequisite Skills
your skillz

## Required Tools
tour toolz

## Environment
the working environment (K8s, Harbor, Dex, etc.)



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the Apache 2.0 License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

  * Rob Hardt: rhardt -at- vmware.com
  * Parth Pandit: panditpa -at- vmware.com

Project Link: [https://github.com/rhardt-pivotal/build-workshop](https://github.com/rhardt-pivotal/build-workshop)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Adib Saikali](https://adibsaikali.com/)
* [Best README Template](https://github.com/othneildrew/Best-README-Template)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/rhardt-pivotal/build-workshop
[contributors-url]: https://github.com/rhardt-pivotal/build-workshop/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/rhardt-pivotal/build-workshop
[forks-url]: https://github.com/rhardt-pivotal/build-workshop/network/members
[stars-shield]: https://img.shields.io/github/stars/rhardt-pivotal/build-workshop
[stars-url]: https://github.com/rhardt-pivotal/build-workshop/stargazers
[issues-shield]: https://img.shields.io/github/issues/rhardt-pivotal/build-workshop
[issues-url]: https://github.com/rhardt-pivotal/build-workshop/issues
[license-shield]: https://img.shields.io/github/license/rhardt-pivotal/build-workshop
[license-url]: https://github.com/rhardt-pivotal/build-workshop/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/robhardt/ 
[linkedin-url2]: https://linkedin.com/in/parthpandit/ 
[product-screenshot]: images/screenshot.png
