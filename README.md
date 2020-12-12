<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

* Deploy AWS Infrastructure with ansible. 
* Small-ansible-infrastructure containes 2 EC2 nodes and 1 RDS instance along with all needed networking configuration.
* Large-ansible-infrastructure containes 5 EC2 nodes and 3 RDS instance along with all needed networking configuration and ELB.

### Built With

* [Ansible](https://ansible.com)
* [Yaml](https://yaml.com)

## Getting Started

To deploy AWS Infrastructure: ansible-playbook deploy-aws-infrastructure.yml

To terminate AWS Infrastructure: ansible-playbook terminate-aws-infrastructure.yml

Keep in mind that variables for this deployment are done through jenkins pipeline. To be done without jenkins, put variable values directly into the playbook.

### Prerequisites

Ansible version 2.9.0 +

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/m-stojanovic/aws-infrastructure-ansible/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Milos Stojanovic - [@linkedin](https://www.linkedin.com/in/infomilosstojanovic/)

Project Link: [https://github.com/m-stojanovic/aws-infrastructure-ansible](https://github.com/m-stojanovic/aws-infrastructure-ansible)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
