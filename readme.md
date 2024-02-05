# Dockerized .NET application example

## CI description

This repository contains GitHub Workflows to implement [semantic release](https://github.com/semantic-release/semantic-release) CI processes based on [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

For more details see [docker.yml](./.github/workflows/docker.yml) workflow

Also, this workflow assumes that this repository is integrated with [AWS by using OIDC](https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-amazon-web-services)

## Application description

This application has two endpoints:

* /WeatherForecast - to show some information
* /healthz - default health check endpoint
