# Local Kubernetes Setup

Multi node Kubernetes cluster setup with [kube-prometheus-stack](https://github.com/prometheus-operator/kube-prometheus) for local development.

## Installation

Make sure you have [VirtualBox](https://www.virtualbox.org/), [Vagrant](https://www.vagrantup.com/docs/installation), [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) and the [Ansible Kubernetes Collection](https://galaxy.ansible.com/community/kubernetes) installed on your system.

### Usage

Start VM:

```sh
vagrant up
```

Connect to VM:

```sh
vagrant ssh master
vagrant ssh worker
```
