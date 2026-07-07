<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stars][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]


<br />
<div align="center">
  <a href="https://github.com">
    <img src="https://i.imageupload.app/be8d41245d703f229d59.jpeg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Vire Configuration Templates</h3>

  <p align="center">
    Example TOML configuration templates for Vire projects.
    <br />
    <a href="https://github.com/Vire-Systems/vire-configfiles"><strong>View TOML Files »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Vire-Systems/vire-configfiles/issues/new?labels=bug&template=bug-report.md">Report Configuration Error</a>
    &middot;
    <a href="https://github.com/Vire-Systems/vire-configfiles/issues/new?labels=enhancement&template=feature-request.md">Request Variable Change</a>
  </p>
</div>


<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-config">About The Configuration</a></li>
    <li><a href="#how-to-use">How To Use</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<a id="about-the-config"></a>
## About The Configuration

This repository contains example configuration TOML files. They are intended to be used as templates when configuring Vire for your own projects.

> **Note**: These configuration files are meant to be placed inside the `.vire` directory in your **project's root**.

Providing these example configuration files makes it easier for new users to get started and understand how Vire is configured.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

[![TOML][TOML-shield]][TOML-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- HOW TO USE -->
<a id="how-to-use"></a>
## How To Use

You can use these templates as the starting point for your project's Vire configuration.

### Direct Fetch (CURL/Wget)

#### 1. Create a directory in the project's root called `.vire`:
```sh
mkdir .vire
```

#### 2. Download the template files into the `.vire` directory:

1. `vire.toml` - Project build configuration: 
```sh
curl -L https://raw.githubusercontent.com/Vire-Systems/vire-configfiles/main/vire.toml > .vire/vire.toml
```

2.  `vire.deploy.toml` - Project deployment configuration:
```sh
curl -L https://raw.githubusercontent.com/Vire-Systems/vire-configfiles/main/vire_deploy.toml > .vire/vire.deploy.toml
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a id="contributing"></a>
## Contributing

Any updates or additions to these configuration parameters are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewSetting`)
3. Commit your Changes (`git commit -m 'Add new api endpoint config'`)
4. Push to the Branch (`git push origin feature/NewSetting`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!--License-->
<a id="license"></a>
## License

Distributed under the MIT License. See [LICENSE](/LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!--Contact-->
<a id="contact"></a>
## Contact

Project Link: [Vire Organization](https://github.com/Vire-Systems)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


[contributors-shield]: https://img.shields.io/github/contributors/Vire-Systems/vire-configfiles?style=for-the-badge
[contributors-url]: https://github.com/Vire-Systems/vire-configfiles/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/Vire-Systems/vire-configfiles?style=for-the-badge
[forks-url]: https://github.com/Vire-Systems/vire-configfiles/network/members

[stars-shield]: https://img.shields.io/github/stars/Vire-Systems?style=for-the-badge&label=Organization%20Stars
[stars-url]: https://github.com/Vire-Systems

[issues-shield]: https://img.shields.io/github/issues/Vire-Systems/vire-configfiles?style=for-the-badge
[issues-url]: https://github.com/Vire-Systems/vire-configfiles/issues

[license-shield]: https://shields.io
[license-url]: https://github.com/Vire-Systems/vire-configfiles/blob/main/LICENSE

[TOML-shield]: https://img.shields.io/badge/TOML-Vire%20Configuration%20Files-blue?style=for-the-badge&logo=toml
[TOML-url]: https://toml.io
