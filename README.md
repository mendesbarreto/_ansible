# Ansible Installation Guide

This guide covers Ansible installation and dependencies across different operating systems.

## macOS Installation

### Install Homebrew

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Install Ansible and Dependencies
```shell
brew install ansible
brew install coreutils
```

## Arch Linux Installation

### Update System and Install Ansible

```shell
sudo pacman -Sy ansible
```

## Verify Installation

```shell
ansible --version
```

## Directory Structure

