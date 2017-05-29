# Cluster in a Box

## Introduction

Everything necessary to create a cluster using [Metal-as-a-Service](https://maas.io/) (MAAS) and [Juju](https://jujucharms.com), the idea being to easily bootstrap both OpenStack or Kubernetes small clusters.

## Install

To install and configure use the net install option when booting from [Ubuntu install media](https://www.ubuntu.com/download/server). This repo is tested against Ubuntu Server 16.04.2 LTS.

- [] Create initial preseed.cfg file that installs git and ansible
- [] Create Ansible role to install and configure MAAS
- [] Create Ansible role to install, and bootstrap Juju controller
