<a id="readme-top"></a>

<h1><center>Janus DevOps</center></h1> <div align="center"> <a href="https://github.com/janus-bastion"> <img src="https://github.com/janus-bastion/janus-frontend/blob/main/public/janus-logo.png" alt="Janus Bastion Logo" width="160" height="160" /> </a> <p><em>The DevOps foundation of the Janus project. This repository provides Dockerfiles, build contexts, and automation configurations to support the entire Janus infrastructure lifecycle.</em></p> <table align="center"> <tr> <th>Author</th> <th>Author</th> <th>Author</th> <th>Author</th> </tr> <tr> <td align="center"> <a href="https://github.com/nathanmartel21"> <img src="https://github.com/nathanmartel21.png?size=115" width="115" alt="@nathanmartel21" /><br /> <sub>@nathanmartel21</sub> </a> <br /><br /> <a href="https://github.com/sponsors/nathanmartel21"> <img src="https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=white" alt="Sponsor nathanmartel21" /> </a> </td> <td align="center"> <a href="https://github.com/xeylou"> <img src="https://github.com/xeylou.png?size=115" width="115" alt="@xeylou" /><br /> <sub>@xeylou</sub> </a> <br /><br /> <a href="https://github.com/sponsors/xeylou"> <img src="https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=white" alt="Sponsor xeylou" /> </a> </td> <td align="center"> <a href="https://github.com/Djegger"> <img src="https://github.com/Djegger.png?size=115" width="115" alt="@Djegger" /><br /> <sub>@Djegger</sub> </a> <br /><br /> <a href="https://github.com/sponsors/Djegger"> <img src="https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=white" alt="Sponsor Djegger" /> </a> </td> <td align="center"> <a href="https://github.com/Warsgo"> <img src="https://github.com/Warsgo.png?size=115" width="115" alt="@Warsgo" /><br /> <sub>@Warsgo</sub> </a> <br /><br /> <a href="https://github.com/sponsors/Warsgo"> <img src="https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=white" alt="Sponsor Warsgo" /> </a> </td> </tr> </table> </div>

## Contents

- [`janus-core/`](./janus-core/): Base Docker image with Debian, SSH, and PHP CLI.
- [`janus-php/`](./janus-php/): PHP-specific container configurations.
- [`.github/`](./.github/): GitHub Actions workflows and Dependabot configuration.

## Features

- Modular Dockerfiles for Janus services.
- Dependabot integration to monitor and update Docker base images automatically.
- GitHub Actions-ready structure for CI/CD pipelines.
- Secure, minimal, and production-ready image designs.
- Clear separation of build contexts by service.

## Notes

- Each service has its own Dockerfile and build context.
- Dependabot is configured to automatically open PRs when base images are updated.
- Use this repository as a centralized source for building and maintaining the container images used in the Janus project.

## License

This project is licensed under the GNU General Public License v3.0 [GPL-3.0](https://github.com/janus-bastion/.github/blob/main/LICENSE).  
See the `LICENSE` file for more details.
