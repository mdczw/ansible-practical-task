## First option (java based)
To deploying java based application run:
```
ansible-playbook java_based_app_deploy.yml
```
and enter the jar file path.

## Second option (Docker based)
To deploying Docker based application run:
```
ansible-playbook docker_based_app_deploy.yml --ask-vault-pass
```
and enter ansible-vault password.

If using a public repository, set the variable ```private_docker_repo: false``` and run:
```
ansible-playbook docker_based_app_deploy.yml
```
