<h1><img align="center" height="80" src="./assets/toolenv-logo.png"> Toolenv</h1>

A simple utility to manage environments within toolbx.

# Installation

RPM packages are available in the [`toolenv-packages`](https://github.com/pesader/toolenv-packages/) repository.

# How to use it

Toolenv's goal is to make it easy to create and use custom shell configurations (i.e. environments) for specific toolbxes. Here's the step-by-step tutorial:

1. Enter a toolbx
2. Run `toolenv create` to create an shell configuration for that toolbx
3. Run `toolenv edit` to edit the shell configuration you just created
3. Next time you enter that toolbx, that configuration will be automatically sourced by `toolenv`

It also distinguises between different shells (e.g. bash, zsh), so you can have different configurations for each.

# Why use it

Here are some possible use-cases:

- Setup CLI tools that are only installed in the toolbx (e.g. zoxide, direnv, etc)
- Use programming language environments in software development toolbxes
- Set debugging environment variables in software development toolbxes
- Change your `$HOME` directory within a toolbx

# License

This work is licensed under the terms of the GPLv3.

![](assets/toolenv-toolbx.png)

