# personal-k8s

Aim - Ansible this: https://community.hetzner.com/tutorials/create-microk8s-cluster

## Notes

1. Create ansible folder in ~/.ssh
2. To ~/.ssh/config add:

` Include ~/.ssh/ansible/* `

1. ansible-galaxy collection install hetzner.hcloud
2. ansible-playbook microk8s-playbook.yml



