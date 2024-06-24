# Ingress NGINX Controller
#1111
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/5691/badge)](https://bestpractices.coreinfrastructure.org/projects/5691)
[![Go Report Card](https://goreportcard.com/badge/github.com/kubernetes/ingress-nginx)](https://goreportcard.com/report/github.com/kubernetes/ingress-nginx)
[![GitHub license](https://img.shields.io/github/license/kubernetes/ingress-nginx.svg)](https://github.com/kubernetes/ingress-nginx/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/kubernetes/ingress-nginx.svg)](https://github.com/kubernetes/ingress-nginx/stargazers)
[![GitHub stars](https://img.shields.io/badge/contributions-welcome-orange.svg)](https://github.com/kubernetes/ingress-nginx/blob/main/CONTRIBUTING.md)


## Overview

ingress-nginx is an Ingress controller for Kubernetes using [NGINX](https://www.nginx.org/) as a reverse proxy and load
balancer.

[Learn more about Ingress on the Kubernetes documentation site](https://kubernetes.io/docs/concepts/services-networking/ingress/).

## Get started

See the [Getting Started](https://kubernetes.github.io/ingress-nginx/deploy/) document.

## Troubleshooting

If you encounter issues, review the [troubleshooting docs](docs/troubleshooting.md),
[file an issue](https://github.com/kubernetes/ingress-nginx/issues), or talk to us on the
[#ingress-nginx channel](https://kubernetes.slack.com/messages/ingress-nginx) on the Kubernetes Slack server.

## Changelog

See [the list of releases](https://github.com/kubernetes/ingress-nginx/releases) for all changes.
For detailed changes for each release, please check the [changelog-$version.md](./changelog) file for the release version.
For detailed changes on the `ingress-nginx` helm chart, please check the changelog folder for a specific version.
[CHANGELOG-$current-version.md](./charts/ingress-nginx/changelog) file.

### Supported Versions table

Supported versions for the ingress-nginx project mean that we have completed E2E tests, and they are passing for
the versions listed. Ingress-Nginx versions **may** work on older versions, but the project does not make that guarantee.

|  Supported  | Ingress-NGINX version | k8s supported version        | Alpine Version | Nginx Version | Helm Chart Version |
|:--:|-----------------------|------------------------------|----------------|---------------|------------------------------|
| 🔄 | **v1.10.1**            | 1.29, 1.28, 1.27, 1.26        | 3.19.1         | 1.25.3        | 4.10.1*                 |
| 🔄 | **v1.10.0**            | 1.29, 1.28, 1.27, 1.26        | 3.19.1         | 1.25.3        | 4.10.0*                 |
| 🔄 | **v1.9.6**            | 1.29, 1.28, 1.27, 1.26, 1.25        | 3.19.0         | 1.21.6        | 4.9.1*                 |
| 🔄 | **v1.9.5**            | 1.28, 1.27, 1.26, 1.25        | 3.18.4         | 1.21.6        | 4.9.0*                       |
| 🔄 | **v1.9.4**            | 1.28, 1.27, 1.26, 1.25        | 3.18.4         | 1.21.6        | 4.8.3                        |
| 🔄 | **v1.9.3**            | 1.28, 1.27, 1.26, 1.25        | 3.18.4         | 1.21.6        | 4.8.*                        |
| 🔄 | **v1.9.1**            | 1.28, 1.27, 1.26, 1.25        | 3.18.4         | 1.21.6        | 4.8.*                        |
| 🔄 | **v1.9.0**            | 1.28, 1.27, 1.26, 1.25        | 3.18.2         | 1.21.6        | 4.8.*                        |
|  | v1.8.4            | 1.27, 1.26, 1.25, 1.24        | 3.18.2         | 1.21.6        | 4.7.*                        |
|  | v1.7.1            | 1.27, 1.26, 1.25, 1.24        | 3.17.2         | 1.21.6        | 4.6.*              |
|    | v1.6.4                | 1.26, 1.25, 1.24, 1.23       | 3.17.0         | 1.21.6        | 4.5.*              |
|    | v1.5.1                | 1.25, 1.24, 1.23             | 3.16.2         | 1.21.6        | 4.4.*              |
|    | v1.4.0                | 1.25, 1.24, 1.23, 1.22       | 3.16.2         | 1.19.10†      | 4.3.0              |
|    | v1.3.1                | 1.24, 1.23, 1.22, 1.21, 1.20 | 3.16.2         | 1.19.10†      | 4.2.5              |
