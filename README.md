Ansible Playbook: Sentry
====

Install Steps:
 - copy: `/vars.yml.dist` to `/vars.yml` and configure
 - copy: `/inventory.ini.dist` to `/inventory.ini` and configure
 - run: `ansible-playbook playbook.yml -i inventory.ini`
 - on remote server, run: `sentry --config={config_file} createsuperuser` (Replace {config_file} with real path)
