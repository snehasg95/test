<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.jpg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Argus</h3>

  <p align="center">
    A Single Window Monitoring System to Visualize and Analayze SecRnD Services
    <br />
    <a href="https://drive.google.com/drive/u/1/folders/1yr9FLbr_yS4ofR2BRjLvdh686F4YNlMf"><strong>Explore the Docs »</strong></a>
    <br />
    <br />
    <a href="https://github.intuit.com/secrnd-devops/argus/issues">Report Bug</a>
    ·
    <a href="https://github.intuit.com/secrnd-devops/argus/issues">Request Feature</a>
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
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Argus is a grafana dashboard that provides a consolidated view of all the services within SecRnD at Intuit, along with the ability to analyze and visualize them. Although, there were some existing tools that we relied on, none of them offered a single window monitoring system solution, that could give us a comprehensive summary of all our services 
Our goal was to create a user-friendly and customizable tool that would allow users to delve deeper into panel metrics and gain more insights

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

* [![Grafana][grafana]]['https://grafana.com/']
* [![AWS][aws]]['https://aws.amazon.com/']
* [![Python][python]]['https://www.python.org/']
* [![PagerDuty][pagerduty]]['https://www.pagerduty.com/']

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To learn more about the tool please visit : https://drive.google.com/drive/u/1/folders/1yr9FLbr_yS4ofR2BRjLvdh686F4YNlMf

### Prerequisites

The tool heavily relies on PagerDuty to depict operational data across services
For now all SecrnD services are onboarded to Argus, however in the future once intergration with devportal is complete, only services that have PagerDuty configured on devportal will be able to onboard

### Installation / Onboarding

The tool will be available as a plugin to oboard from devportal


<!-- ROADMAP -->
## Roadmap

- [ ] Gather and display more insights for a service using PagerDuty
- [ ] Intergrate other data sources like Golend Signals & JIRA
- [ ] Plugin creation in DevPortal
    - [ ] We are working with DevPortal team to understand our next steps for this capability


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions helps our team understand what features users like to see as well changes to existing dashboard.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Thank you!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact
1. Snehapiriya Kammalakannon - [@slack-handle](@sneha) - sneha_kammalakannon@intuit.com
2. Harpreet Wadhwa - [@slack-handle](@haps) - hwadhwa@intuit.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [SDOI](https://drive.google.com/drive/folders/1tL3KZQUZ5ZbpJn8MDwQ_JpN1UP2M3wPO?usp=share_link)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.intuit.com/secrnd-devops/argus/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.intuit.com/secrnd-devops/argus/network/members
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.intuit.com/secrnd-devops/argus/issues
[grafana]: https://img.shields.io/badge/Grafana-20232A?style=for-the-badge&logo=grafana&logoColor=F46800
