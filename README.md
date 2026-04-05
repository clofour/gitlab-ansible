This is a deployment of GitLab Omnibus with Ansible. It can be used on bare metal/VMs for <1000 users.

Note that it has not been tested. It is also incomplete, with various functionality gaps and bugs.

# Usage
1. Set up an inventory, with the "env" and "grafana_secrets" parameters
3. Place a certificate at ~/.secrets/[env]/domain.cert.pem and a private key at ~/.secrets/[env]/private.key.pem
4. Run the playbook with your inventory