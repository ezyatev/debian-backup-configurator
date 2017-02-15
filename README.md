# Debian Backup Configurator

List of Ansible playbooks to configure backup clients for [debian-ssh-backup](https://github.com/ezyatev/debian-ssh-backup).

## How to Use

1. Copy the `secrets.example.yml` file and save the new file as `secrets.yml` in the same directory.
2. Copy the `inventory.example.txt` file and save the new file as `inventory.txt` in the same directory.
3. At this point, give the configurator a go. Please run: `ansible-playbook -uroot main.yml`


## Author

Eugene Zyatev ([eu@businesslogic.io](mailto:eu@businesslogic.io))