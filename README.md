# Projeto Django Girls Tutorial

Este repositório contém a implementação do projeto apresentado no Tutorial Django Girls.

## Executando o Projeto com Docker

Caso queira rodar este projeto usando Docker, você pode utilizar o seguinte comando:

```bash
docker-compose up
```
Depois que o contêiner estiver rodando, é necessário executar o seguinte comando dentro do contêiner:
```bash
python manage.py migrate
```
Este comando irá aplicar todas as migrações do Django.
