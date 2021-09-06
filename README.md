<div align="center">

<img src="https://camo.githubusercontent.com/5b298bf6b0596795602bd771c5bddbb963e83e0f/68747470733a2f2f692e696d6775722e636f6d2f7031527a586a512e706e67" align="center" width="100px" height="100px"/>  

### My Home Kubernetes Raspberry Pi Cluster  
**Work In Progress**  
</br>
</br>

[![k3s](https://img.shields.io/badge/K3S-v1.21.4-brightgreen?style=for-the-badge&logo=kubernetes&logoColor=white)](https://k3s.io/)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white&style=for-the-badge)](https://github.com/pre-commit/pre-commit)
[![renovate](https://img.shields.io/badge/renovate-enabled-brightgreen?style=for-the-badge&logo=renovatebot&logoColor=white)](https://github.com/renovatebot/renovate)
[![sops](https://img.shields.io/badge/SOPS-encrypted-brightgreen?style=for-the-badge&logo=mozilla&logoColor=white)](https://github.com/mozilla/sops)
![GitHub last commit](https://img.shields.io/github/last-commit/lloydoliver/k8s-at-home?style=for-the-badge)

[Flux](https://github.com/fluxcd/flux2) watches this repo and makes changes to my home Kubernetes cluster when changes are committed to the ./cluster folder.  
[Renovate](https://github.com/renovatebot/renovate) also watches this Git repository and creates pull requests when application updates are available  

</br></br>
</div>

## Hardware

- 3x Raspberry Pi 4B 8GB  
- 3x PNY 120GB SSDs  
- 3x Sabrent USB SATA Adapters  

## Tools used

[k3s](k3s.io) - Lightweight Kubernetes  
[Flux](https://github.com/fluxcd/flux2) - Operator that manages your k8s cluster based on your Git repository  
[SOPS](https://github.com/mozilla/sops) - Encrypts k8s secrets with GnuPG  
[pre-commit](https://github.com/pre-commit/pre-commit) - Runs checks pre `git commit`  

## Apps/Components deployed

[BotKube](https://www.botkube.io/) - Messaging bot for monitoring Kubernetes  
[cert-manager](https://cert-manager.io/) - SSL certificates - with Cloudflare DNS challenge  
[error-pages](ghcr.io/tarampampam/error-pages) - docker image containing http error pages  
[hajimari](https://github.com/toboshii/hajimari) - start page with ingress discovery  
[Home Assistant](https://www.home-assistant.io/) - Home automation tooling  
[Longhorn](https://longhorn.io) - Storage provider  
[metallb](https://metallb.universe.tf/) - bare metal load balancer  
[Mosquitto](https://mosquitto.org/) - MQTT Broker  
[node-red](https://nodered.org/) - Flow editor  
[PiHole](https://pi-hole.net/) - DNS and Network Ad-Blocker  
[traefik](https://traefik.io) - ingress controller  
[Unbound](https://www.nlnetlabs.nl/projects/unbound/about/) - validating, recursive, caching DNS resolver  

## :handshake:&nbsp; Thanks

Massive thanks to everyone that's contributed to the [k8s-at-home](https://github.com/k8s-at-home) project.
