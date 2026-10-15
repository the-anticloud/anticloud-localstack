# LOCALSTACK

> Anticloud offline package — upstream: localstack/localstack @ `main`.

## What This Project Does

💻 A fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline

**Topics:** aws, cloud, continuous-integration, developer-tools, localstack, python, testing

## Upstream README

> [!IMPORTANT]
> **Project Update: Consolidation into the Unified LocalStack Image**
>
> To provide a more reliable and streamlined experience, we are consolidating our development into a single, unified image. As part of this transition, this repository is now **archived and read-only**.
>
> This decision reflects our commitment to reducing fragmentation and focusing our resources on building the most robust AWS emulation layer possible. We are deeply grateful to the contributors who helped make this project into what it is today–your work remains integral to the future of the LocalStack ecosystem.
>
> What this means for your workflow:
>
> - LocalStack for AWS offers a [range of options](https://www.localstack.cloud/pricing) including a free Hobby plan for non-commercial use with the same capabilities as this project.
> - Your input is still vital to us. Please continue to share [bug reports here](https://github.com/orgs/localstack/discussions/categories/bugs) and [submit feature requests here](https://github.com/orgs/localstack/discussions/categories/feature-requests) or join our [Slack Community](https://slack.localstack.cloud).
>
> Thank you for your continued support as we grow together.

<p align="center">
  <img src="docs/localstack-readme-banner.svg" alt="LocalStack - The Leading Platform for Local Cloud Development">
</p>

<p align="center">
  <a href="https://github.com/localstack/localstack/actions/workflows/aws-main.yml?query=branch%3Amain"><img alt="GitHub Actions" src="https://github.com/localstack/localstack/actions/workflows/aws-main.yml/badge.svg?branch=main"></a>
  <a href="https://coveralls.io/github/localstack/localstack?branch=main"><img alt="Coverage Status" src="https://coveralls.io/repos/github/localstack/localstack/badge.svg?branch=main"></a>
  <a href="https://pypi.org/project/localstack/"><img alt="PyPI Version" src="https://img.shields.io/pypi/v/localstack?color=blue"></a>
  <a href="https://hub.docker.com/r/localstack/localstack"><img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/localstack/localstack"></a>
  <a href="https://pypi.org/project/localstack"><img alt="PyPi downloads" src="https://static.pepy.tech/badge/localstack"></a>
  <a href="https://img.shields.io/pypi/l/localstack.svg"><img alt="PyPI License" src="https://img.shields.io/pypi/l/localstack.svg"></a>
  <a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>
  <a href="https://github.com/astral-sh/ruff"><img alt="Ruff" src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json"></a>
  <a href="https://bsky.app/profile/localstack.cloud"><img alt="Bluesky" src="https://img.shields.io/badge/bluesky-Follow-blue?logo=bluesky"></a>
</p>

<p align="center">
  LocalStack is a cloud software development framework to develop and test your AWS applications locally.
</p>

<p align="center">
  <a href="#overview">O

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
