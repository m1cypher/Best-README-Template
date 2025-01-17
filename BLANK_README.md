<div id="top"></div>
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
  <a href="https://github.com/m1cypher/bastion_host">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Bastion Host Script</h3>

  <p align="center">
    project_description
    <br />
    <a href="https://github.com/m1cypher/bastion_host"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/m1cypher/bastion_host">View Demo</a>
    ·
    <a href="https://github.com/m1cypher/bastion_host/issues">Report Bug</a>
    ·
    <a href="https://github.com/m1cypher/bastion_host/issues">Request Feature</a>
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

[![Product Name Screen Shot][product-screenshot]](https://example.com)

As I have build, rebuilt, and expanded my homelab, I always wanted a better way to monitor SSH traffic and restrict it. So I built these bastion host SSH script. You have 3 different scripts, the first will create a new user of your choice on your bastion host, install Google PAM for MFA, and then lockdown SSH to that user. The second script is the SSH lockdown for the remote host. The last one will be added to the ~/.bashrc at the end to restrict the terminal access

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* Bash

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Download the git project.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* bash
  ```sh
  git clone https://github.com/m1cypher/bastion_host.git
  ```

### Installation

1. Modify permissions for the scripts
```sh
chmod +x new_user.sh
chmod +x ssh_lockdown_remote.sh
```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Add Auditing
- [ ] Export of Auditing Logs

See the [open issues](https://github.com/m1cypher/bastion_host/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



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

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@mimircyber](https://twitter.com/mimircyber) - info@mimircyber.com

Project Link: [https://github.com/m1cypher/bastion_host](https://github.com/m1cypher/bastion_host)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/m1cypher/bastion_host.svg?style=for-the-badge
[contributors-url]: https://github.com/m1cypher/bastion_host/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/m1cypher/bastion_host.svg?style=for-the-badge
[forks-url]: https://github.com/m1cypher/bastion_host/network/members
[stars-shield]: https://img.shields.io/github/stars/m1cypher/bastion_host.svg?style=for-the-badge
[stars-url]: https://github.com/m1cypher/bastion_host/stargazers
[issues-shield]: https://img.shields.io/github/issues/m1cypher/bastion_host.svg?style=for-the-badge
[issues-url]: https://github.com/m1cypher/bastion_host/issues
[license-shield]: https://img.shields.io/github/license/m1cypher/bastion_host.svg?style=for-the-badge
[license-url]: https://github.com/m1cypher/bastion_host/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/garrett-e-boyd
[product-screenshot]: images/screenshot.png
