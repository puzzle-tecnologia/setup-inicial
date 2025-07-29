# Playbook Setup Inicial

| Requisitos |
|------------|
| Ansible    |
 
 ### Instalação do Ansible
 ```bash
 sudo apt install pipx
 pipx install --include-deps ansible
 pipx ensurepath
 ```

### Execução do Playbook

```bash
ansible-playbook -v -K playbook.yml
```
