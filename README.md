# configuration-management

Configuration Management in a (hopefully) sane way

## Getting Started

To get started, you will need:
  * python-2.7
  * [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html)
  * [setuptools](https://pypi.python.org/pypi/setuptools#installation-instructions)
  * [terraform](https://terraform.io/downloads.html)

Once the tools have been installed, run:
```
python boostrap.py
```
Run it frequently! :rocket: This configures, installs, and updates your virtual environment.

### Lifecycle

The lifecyle is controlled by [Jenkins](https://ci.int.zigzag.pub/job/Configuration%20Management/).

Credentials can be requested by contacting [security@zigzag.pub](mailto:security@zigzag.pub). Please prepend the subject with: "Jenkins Access Authorization".

#### Stages

The build pipeline is setup with the following stages:
  * Prepare
  * Test
  * Staging Deploy
  * Produciton Deploy
