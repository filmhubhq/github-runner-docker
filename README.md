# Github Actions Runner in Docker Container

Based on [Deploying Self-Hosted GitHub Actions Runners with Docker](https://testdriven.io/blog/github-actions-docker/).

# Setup & Run

* set `GITHUB_ACCESS_TOKEN` to a Github personal access token
* `docker compose build`
* `docker compose up [--scale runner=n]` to start one or optionally n runners
