# Docker Practice Project

This project is a simple Node.js application designed to demonstrate Docker containerization. It includes serving static files, a custom 404 error page, and request handling via an Nginx reverse proxy.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [License](#license)

## Features

- Static files are served from the `/static` directory.
- Custom 404 error page located in `/html/404error`.
- Nginx configured as a reverse proxy for the Node.js server.
- Docker Compose simplifies development and deployment.

## Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your system.
- [Docker Compose](https://docs.docker.com/compose/install/) installed.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Verify the following files are included:

   - `Dockerfile`: Builds the Node.js app image.
   - `docker-compose.yml`: Defines Node.js and Nginx services.
   - `nginx.conf`: Nginx configuration.
   - `html/404error/404.html`: Custom 404 error page.
   - `static/favicon.ico`: Sample static file.

## License

This project is distributed under the MIT License. Refer to the [LICENSE](LICENSE) file for details.