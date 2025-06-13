# CI/CD Template Project

This repository provides a template to integrate CI/CD into a project.
The example project is a simple Python application that includes a counter.

CI/CD configurations are located in:

* `.github/` — GitHub Actions workflows
* `.tekton/` — Tekton pipelines for use with the OpenShift platform

## Setup

To install the required software and dependencies, run the `setup.sh` script located in the `bin/` directory:

```bash
bash bin/setup.sh
```

Once the script has completed, **exit the current shell** and start a new one to activate the Python virtual environment:

```bash
exit
```

Then reopen your terminal and navigate back to the project directory.
