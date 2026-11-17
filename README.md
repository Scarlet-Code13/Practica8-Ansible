# Práctica 8: Automatización de servidores con Ansible

## Descripción

Esta práctica consiste en utilizar Ansible para automatizar la configuración y administración de cinco servidores Ubuntu ejecutados mediante Docker Compose.

Se creó una imagen personalizada de Ubuntu con un servidor SSH y un usuario para permitir la conexión remota desde Ansible. Posteriormente, se configuró un inventario y un Playbook para ejecutar tareas automáticamente en los cinco servidores.

## Tecnologías utilizadas

- Ubuntu 24.04
- Docker
- Docker Compose
- Ansible
- SSH
- Git y GitHub

## Estructura del proyecto

```text
ansible-lab/
├── ubuntu-server/
│   └── Dockerfile
├── ansible.cfg
├── docker-compose.yml
├── inventory.example.ini
├── playbook.yml
├── .gitignore
└── README.md
