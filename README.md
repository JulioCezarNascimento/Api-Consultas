API de Gestão de Consultas Médicas
Esta é uma API RESTful para gerenciamento de profissionais da saúde e suas respectivas consultas, desenvolvida com Django, Django REST Framework e PostgreSQL. O projeto é totalmente containerizado com Docker e possui um pipeline de CI/CD configurado com GitHub Actions para deploy na AWS.

Funcionalidades
CRUD de Profissionais: Criação, leitura, atualização e exclusão de profissionais da saúde.

CRUD de Consultas: Criação, leitura, atualização e exclusão de consultas, sempre associadas a um profissional.

Busca de Consultas: Filtro de consultas por ID do profissional.


Tecnologias Utilizadas
Backend: Python 3.11, Django 5.0, Django REST Framework

Banco de Dados: PostgreSQL 15

Gerenciador de Dependências: Poetry

Containerização: Docker, Docker Compose

CI/CD: GitHub Actions

Cloud: AWS (ECS, ECR, RDS, S3)
