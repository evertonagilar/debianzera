# Debianzera

A lightweight and easy-to-provision development VM powered by **Vagrant** and **Ansible**, with **Docker Engine preinstalled and configured with TLS support**.

Ideal for testing, development, and secure Docker client/daemon setups.

---

## 🔧 Features

- Debian-based Vagrant box
- Docker CE installed and configured
- TLS (X.509) certificates for secure remote Docker access
- Ready-to-use Docker environment via `vagrant ssh`

---

## 🚀 Getting Started

```bash
# Start the VM
vagrant up

# Access the VM
vagrant ssh

# Use Docker
docker ps
