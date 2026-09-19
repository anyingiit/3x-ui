[English](README.md) · **简体中文**

> 英文版是规范版本。本页与 [README.md](README.md) 不一致时，以英文版为准。

<!-- translation-of: README.md sha256:aa7cf045019c4984 -->

<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# 3x-ui

这是 anyingiit/3x-ui 的仓库脚手架，目前只包含治理与工具配置——issue 与 pull request 模板、CODEOWNERS、Dependabot、pre-commit 钩子，以及贡献、安全和许可证方面的政策文档——尚无任何应用源代码。

[![License](https://img.shields.io/github/license/anyingiit/3x-ui)](LICENSE)

[报告问题](https://github.com/anyingiit/3x-ui/issues/new?template=bug_report.yml) · [提出需求](https://github.com/anyingiit/3x-ui/issues/new?template=feature_request.yml)

<details>
  <summary>目录</summary>
  <ol>
    <li><a href="#about-the-project">关于本项目</a></li>
    <li><a href="#getting-started">开始使用</a></li>
    <li><a href="#usage">用法</a></li>
    <li><a href="#contributing">参与贡献</a></li>
    <li><a href="#license">许可证</a></li>
    <li><a href="#contact">联系方式</a></li>
  </ol>
</details>

## 关于本项目

这个仓库目前只有一个项目在拥有任何代码之前需要的、面向 GitHub 的脚手架：issue 与 pull request 模板（`.github/ISSUE_TEMPLATE`、`.github/PULL_REQUEST_TEMPLATE.md`）、一个 `CODEOWNERS` 文件、Dependabot 与发布说明配置、一套 pre-commit 钩子（`.pre-commit-config.yaml`），以及本应与源代码并存的贡献指南、行为准则、安全政策和许可证文档。整个目录树里没有任何清单文件、入口点，也没有任何应用源代码。

计划中的功能与已知问题，见 [open issues](https://github.com/anyingiit/3x-ui/issues)。

## 开始使用

### 环境要求

- Git，用于克隆本仓库。
- 如果想在本地运行 `.pre-commit-config.yaml` 中的钩子集，需要 Python 3.9 及以上版本并执行 `pip install pre-commit`；除此之外不需要任何编译器或运行时。

### 安装

```sh
git clone https://github.com/anyingiit/3x-ui.git
cd 3x-ui
pre-commit install  # 可选：让下面的钩子在每次提交前自动运行
```

这里没有构建步骤：克隆下来的内容就是本仓库目前的全部内容。

## 用法

目前唯一可以运行的是 pre-commit 钩子集：

```sh
pre-commit run --all-files
```

它会依据 `.pre-commit-config.yaml` 检查已跟踪文件是否存在行尾空白、缺少末尾换行、无效的 YAML、未解决的合并冲突标记，以及被意外提交的大文件。除此之外，可以使用 `.github/ISSUE_TEMPLATE` 和 `.github/PULL_REQUEST_TEMPLATE.md` 下的模板来报告缺陷、提出新功能或提交改动。

## 参与贡献

欢迎参与。[CONTRIBUTING.md](CONTRIBUTING.md) 说明如何提交 issue 或 pull request，[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) 说明对所有参与者的行为要求。

请不要在公开的 issue 或 pull request 中报告安全问题。[SECURITY.md](SECURITY.md) 说明了私下报告的方式。

## 许可证

以 MIT 许可证分发。详见 [LICENSE](LICENSE)。

## 联系方式

项目地址：[https://github.com/anyingiit/3x-ui](https://github.com/anyingiit/3x-ui)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
