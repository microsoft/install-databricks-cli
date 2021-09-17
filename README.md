# Databricks CLI Install Action [![Build](https://github.com/microsoft/install-databricks-cli/actions/workflows/cd.yml/badge.svg)](https://github.com/microsoft/install-databricks-cli/actions/workflows/cd.yml)

GitHub Action that installs the Databricks CLI.

## When to use

This action is useful when you need to use the [Databricks command-line interface (CLI)](https://docs.databricks.com/dev-tools/cli/index.html) as an easy-to-use interface to the Databricks platform.

## Getting Started

### Prerequisites

If your GitHub Actions workflows are running on a [self-hosted runner](https://docs.github.com/en/actions/hosting-your-own-runners/about-self-hosted-runners):

* Make sure you installed python. You can use the [Setup Python Action](https://github.com/actions/setup-python)

### Usage

```yml
steps:
    - name: Install Databricks-CLI
      uses: microsoft/install-databricks-cli@v1.0.0
```

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
