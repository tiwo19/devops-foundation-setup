# 🛠️ DevOps Foundation Setup

This repo contains my Week 1 Foundation and tool setup as part of my 60-day DevOps hands-on journey.  
Tools installed and configured:

- [x] Terraform CLI
- [x] AWS CLI
- [x] GitHub CLI
- [x] Docker Desktop
- [x] Ansible

## 📂 Structure

- `screenshots/`: Proof of setup, CLI versions

## 📌 Why This Matters

A proper foundation ensures:
- Version control from day one
- Real-world Git/GitHub usage (branching, PRs)
- Reusability across future DevOps projects

> Part of my #60DaysOfDevOps project. Follow along [@Damipe Tiwo LinkedIn](https://www.linkedin.com/in/damipe-tiwo/)


## 🛠️ Tools Installed

| Tool        | Download Link |
|-------------|----------------|
| Terraform   | [Download](https://developer.hashicorp.com/terraform/downloads) |
| AWS CLI     | [Download](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) |
| GitHub CLI  | [Download](https://cli.github.com/) |
| Docker      | [Download](https://www.docker.com/products/docker-desktop/) |
| Ansible     | [Install Guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) |

## Challenges 

## Error

``` C:\Users\DAMIPE>python3 -m pip install --user ansible-core``
Python was not found; run without arguments to install from the Microsoft Store, or disable this shortcut from Settings > Apps > Advanced app settings > App execution aliases.```

## Cause
That error usually means your pip command is pointing to a Python installation that either no longer exists or is broken

This usually means:

The system is trying to run python3, but there’s no registered executable.

On Windows, sometimes python3 is just an alias that points nowhere unless configured.

It might be trying to launch via a broken App Execution Alias, which Windows often sets when Python is installed via the Microsoft Store.

## My Solution 
```pip install  ansible```

