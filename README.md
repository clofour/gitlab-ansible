This is a deployment of GitLab Omnibus with Ansible. It can be used on bare metal/VMs for <1000 users.

# Usage
1. Set up an inventory
2. Place a certificate at ~/.secrets/[env]/domain.cert.pem and a private key at ~/.secrets/[env]/private.key.pem
3. Run the playbook with your inventory and the "env" parameter