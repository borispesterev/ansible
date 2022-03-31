## Роль docker-install устанавливает и запускает Docker на машинах в группах app
## Роль postgresql-install устанавливает и запускает postgresql-server на машинха в группах database

- Запуск роли docker-install происходит командой ansible-playbook docker-install.yml -D -i hosts
- Запуск роли postgresql-install происходит командой ansible-playbook postgresql-install.yml -D -i hosts
