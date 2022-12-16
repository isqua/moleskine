# Ansible Collection

This is a collection of pieces that I’ve used at least once to set up my machines.

> :warning: No tests, no guarantees.

You can use these notes as you please, just by reading, copying your own code or importing my roles.

Please don’t use roles blindly. Read the code before executing.

## Table of Content

- [developer-tools](./roles/developer-tools/) installs common dev tools like git, vim, etc.
- [docker](./roles/docker/) installs and sets up docker engine
- [dotfiles](./roles/dotfiles/) clones repository from your dotfiles and sets symbolic links to it
- [earthly](./roles/earthly/) installs the [earthly](https://earthly.dev) tool according to machine architecture (macos/linux and amd/arm)
