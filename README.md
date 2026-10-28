# CI/CD Final Project: Hit Counter Service

[![CI workflow](https://github.com/yashdeshmukh2845/ci-cd-final-project/actions/workflows/workflow.yml/badge.svg)](https://github.com/yashdeshmukh2845/ci-cd-final-project/actions/workflows/workflow.yml)

This repository contains the complete implementation of the Final Project for the Coursera course **Continuous Integration and Continuous Delivery (CI/CD)** / **CI/CD Tools and Practices** as part of the IBM DevOps and Software Engineering Professional Certificate.

## Project Name: Hit Counter Service CI/CD Pipeline
A microservice-based Hit Counter application with complete CI/CD automation featuring:
- **Continuous Integration (CI):** Automated linting (`flake8`) and unit tests (`nosetests`) running on GitHub Actions.
- **Continuous Delivery (CD):** Cloud-native pipeline orchestration via **Tekton Pipelines** on **Red Hat OpenShift**, implementing automated workspace cleanup, repository cloning, linting, testing, image building with Buildah, and deployment.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks


## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

Skills Network

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
