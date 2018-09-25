# stroom-docker-compose
Docker Compose file implementing a simple baseline Stroom configuration, consisting of the following services:
1. Stroom instance
1. Separate MySQL Stroom application and statistics databases

# Usage
1. Install Docker CE locally (see https://docs.docker.com/install)
1. Clone this repository
1. `cd <path_to_cloned_repository>`
1. Set environment variables in `docker-compose.yml`
1. Run `docker-compose up` or `docker-compose up -d` to run in background
1. Wait for Stroom to download and initialise
1. Open http://localhost:8080/stroom

For more information on Stroom:
- Main Stroom repository: https://github.com/gchq/stroom
- Stroom configuration options: https://github.com/gchq/stroom-docs/blob/master/install-guide/stroom-app-install.md
- Documentation: https://gchq.github.io/stroom-docs
