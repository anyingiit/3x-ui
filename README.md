<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# 3x-ui

A repository scaffold for anyingiit/3x-ui that ships only governance and tooling configuration -- issue and pull request templates, CODEOWNERS, Dependabot, pre-commit hooks, and contributing, security, and license policies -- with no application source code yet.

**English** · [简体中文](README.zh-CN.md)

[![License](https://img.shields.io/github/license/anyingiit/3x-ui)](LICENSE)

[Report a bug](https://github.com/anyingiit/3x-ui/issues/new?template=bug_report.yml) · [Request a feature](https://github.com/anyingiit/3x-ui/issues/new?template=feature_request.yml)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

This repository currently holds only the GitHub-facing scaffolding a project needs before it has any code: issue and pull request templates (`.github/ISSUE_TEMPLATE`, `.github/PULL_REQUEST_TEMPLATE.md`), a `CODEOWNERS` file, Dependabot and release-note configuration, a pre-commit hook set (`.pre-commit-config.yaml`), and the contributing, code of conduct, security, and license documents that source code would normally sit alongside. There is no manifest, no entry point, and no application source anywhere in the tree.

See the [open issues](https://github.com/anyingiit/3x-ui/issues) for planned features and known issues.

## Getting Started

### Prerequisites

- Git, to clone the repository.
- Python 3.9 or newer with `pip install pre-commit`, only if you want to run the hook set in `.pre-commit-config.yaml` locally; nothing here needs a compiler or runtime beyond that.

### Installation

```sh
git clone https://github.com/anyingiit/3x-ui.git
cd 3x-ui
pre-commit install  # optional: runs the hooks below before each commit
```

There is no build step: cloning gives you the complete contents of the repository as it stands today.

## Usage

The only thing that currently runs is the pre-commit hook set:

```sh
pre-commit run --all-files
```

This checks the tracked files for trailing whitespace, a missing final newline, invalid YAML, unresolved merge-conflict markers, and accidentally committed large files, per `.pre-commit-config.yaml`. Beyond that, use the templates under `.github/ISSUE_TEMPLATE` and `.github/PULL_REQUEST_TEMPLATE.md` to report a bug, request a feature, or propose a change.

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) for how to open an issue or a pull request, and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for the standards expected of everyone taking part.

Please do not report security issues in public issues or pull requests. [SECURITY.md](SECURITY.md) explains how to report them privately.

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

Project link: [https://github.com/anyingiit/3x-ui](https://github.com/anyingiit/3x-ui)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
