<img src="https://camo.githubusercontent.com/5b298bf6b0596795602bd771c5bddbb963e83e0f/68747470733a2f2f692e696d6775722e636f6d2f7031527a586a512e706e67" align="left" width="144px" height="144px"/>

### My home Kubernetes cluster ⛵
_... managed by Flux and serviced with RenovateBot_ 🤖

<br/>
<br/>
<br/>


<div align="center">

[![Ubuntu](https://img.shields.io/badge/ubuntu-22.0.4.1-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![k3s](https://img.shields.io/badge/k3s-v1.24.8-blue?style=for-the-badge&logo=kubernetes&logoColor=white)](https://k3s.io/)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-enabled?logo=pre-commit&logoColor=white&style=for-the-badge&color=brightgreen)](https://github.com/pre-commit/pre-commit)
[![renovate](https://img.shields.io/badge/renovate-enabled-enabled?style=for-the-badge&logo=renovatebot&logoColor=white&color=brightgreen)](https://github.com/renovatebot/renovate)
[![Discord](https://img.shields.io/discord/673534664354430999?style=for-the-badge&label=discord&logo=discord&logoColor=white&color=teal)](https://discord.gg/k8s-at-home)


</div>

## 📖  Overview

This is home to my personal Kubernetes cluster. [Flux](https://github.com/fluxcd/flux2) watches this Git repository and makes the changes to my cluster based on the manifests in the [cluster](./kubernetes/) directory.

## 🖥️ Hardware

| Device               | Count | OS Disk Size | Data Disk Size              | Ram | Operating System | Purpose           |
|----------------------|-------|--------------|-----------------------------|-----|------------------|-------------------|
| Fujitsu Esprimo Q956 | 1     | 120GB        | -                           | 8GB | Ubuntu           | Kubernetes Master |
| Xiaomi Mijia 2       | 8     | -            | -                           | -   | [Custom](https://pvvx.github.io/ATC_MiThermometer/TelinkMiFlasher.html)         | Monitoring        |

## 📝 ToDo

### Apps:
- [ ] [Awesome Self Hosted](https://github.com/awesome-selfhosted/awesome-selfhosted)
- [ ] Accounting App
- [ ] Borg Backup
- [ ] Heimdall
- [ ] Home-assistent config
- [ ] Jellyfin
- [ ] Keycloak/Authentik
- [ ] Paperless-ngx
- [ ] Wildcard Certs

## 👉 Useful Links
- [k8s-at-home-search](https://nanne.dev/k8s-at-home-search/)
- [Initial Setup Guide](SETUP.md)

## 🤝 Special Thanks
[onedr0p](https://github.com/onedr0p) for the awesome template and the whole [Kubernetes@Home](https://discord.gg/k8s-at-home) community!
