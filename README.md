# WES-cli

[![Apache License](https://img.shields.io/badge/license-Apache%202.0-orange.svg?style=flat&color=important)](http://www.apache.org/licenses/LICENSE-2.0)

Client based on bravado for the Workflow Execution Service (WES)

# Installation

Clone repository

```bash
git clone https://github.com/zavolanlab/WES-cli.git
```

Traverse to project directory

```bash
cd WES-cli
project_dir="$PWD"
```

Create and activate virtual environment

```bash
virtualenv -p `which python3` venv
source venv/bin/activate
```

Install required packages

```bash
pip install -r requirements.txt
```
