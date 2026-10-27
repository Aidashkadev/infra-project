Редактировано через веб-интерфейс GitHub
# Infra project

Учебный инфраструктурный репозиторий курса 

<!-- Допишите сюда -->
Учебный проект: инфраструктура с Docker и Ansible.

## Запуск в Docker

```bash
docker build -t infra-web:1.0 docker/
docker run -d --name infra-web -p 8080:80 infra-web:1.0
curl http://localhost:8080
docker rm -f infra-web
```
