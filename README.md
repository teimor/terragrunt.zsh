# terragrunt.zsh

An Oh-My-Zsh plugin for Terragrunt, enhancing your command-line experience when working with Terragrunt and Terraform configurations.

## Overview

`terragrunt.zsh` is an Oh-My-Zsh plugin designed to streamline your workflow with Terragrunt, an open-source wrapper for Terraform that provides extra tools for working with multiple Terraform modules. This plugin offers:

1. Command completion for Terragrunt
2. Useful aliases for common Terragrunt commands
3. Integration with Oh-My-Zsh for easy installation and management

Whether you're a seasoned Terragrunt user or just getting started, this plugin aims to boost your productivity and make your Terragrunt experience in Oh-My-Zsh more enjoyable.

## Requirements

* [Zsh](https://www.zsh.org/)
* [Oh-My-Zsh](https://ohmyz.sh/)
* [Terragrunt](https://terragrunt.gruntwork.io/)

## Installation

1. Clone this repository into the Oh-My-Zsh custom plugins directory:

```bash
git clone https://github.com/teimor/terragrunt.zsh ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/terragrunt
```

2. Activate the plugin in your `~/.zshrc` file:

```shell
plugins=(... terragrunt)
```

3. Reload Oh-My-Zsh:

```bash
omz reload
```

## Features

### Command Completion

This plugin provides command completion for Terragrunt, making it easier to use Terragrunt commands and options within your Oh-My-Zsh environment.

### Aliases

| Alias  | Command                       |
|--------|-------------------------------|
| `tg`   | `terragrunt`                  |
| `tga`  | `terragrunt apply`            |
| `tgc`  | `terragrunt console`          |
| `tgd`  | `terragrunt destroy`          |
| `tgf`  | `terragrunt fmt`              |
| `tgfu` | `terragrunt force-unlock`     |
| `tggd` | `terragrunt graph-dependencies` |
| `tghf` | `terragrunt hclfmt`           |
| `tgi`  | `terragrunt init`             |
| `tgim` | `terragrunt import`           |
| `tgo`  | `terragrunt output`           |
| `tgp`  | `terragrunt plan`             |
| `tgpr` | `terragrunt providers`        |
| `tgr`  | `terragrunt refresh`          |
| `tgra` | `terragrunt run-all`          |
| `tgrj` | `terragrunt render-json`      |
| `tgs`  | `terragrunt state`            |
| `tgsh` | `terragrunt show`             |
| `tgt`  | `terragrunt taint`            |
| `tgti` | `terragrunt terragrunt-info`  |
| `tgut` | `terragrunt untaint`          |
| `tgv`  | `terragrunt validate`         |
| `tgve` | `terragrunt version`          |
| `tgvp` | `terragrunt validate-inputs`  |
| `tgw`  | `terragrunt workspace`        |

## Contributing

Contributions to improve `terragrunt.zsh` are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
