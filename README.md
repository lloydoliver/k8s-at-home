# My k8s At Home

K3s running on 3x RaspberryPi 4 (8GB).

*W.I.P*

## Hardware

3x Raspberry Pi 4B 8GB
3x PNY SSDs
3x Sabrent USB SATA cables

## Tools used

[k3s](k3s.io)
[flux](https://toolkit.fluxcd.io/)
[SOPS](https://github.com/mozilla/sops)
[pre-commit](https://github.com/pre-commit/pre-commit)

## Apps/Components deployed

[cert-manager](https://cert-manager.io/) - SSL certificates - with Cloudflare DNS challenge
[hajimari](https://github.com/toboshii/hajimari) - start page with ingress discovery
[Home Assistant](https://www.home-assistant.io/) - Home automation tooling
[Longhorn](https://longhorn.io) - Storage provider
[metallb](https://metallb.universe.tf/) - bare metal load balancer
[Mosquitto](https://mosquitto.org/) - MQTT Broker
[traefik](https://traefik.io) - ingress controller


## :handshake:&nbsp; Thanks

Big shout out to all the authors and contributors to the projects that were used in the template repo from which this is based - [k8s-at-home](https://github.com/k8s-at-home/template-cluster-k3s)
