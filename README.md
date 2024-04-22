# Curso de Django: persistência de dados e Admin
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

O que foi ensinado no curso:
- Entender como lidar com dados em uma aplicação Django utilizando banco de dados
- Conhecer o Django Admin, uma rota administrativa nativa do framework
- Criar formulários com ferramentas nativas do Django
- Aprender como lidar com arquivos de mídia no Django

## Aulas

- Lidando com Dados | 11/11
    - Apresentação
    - Preparando o ambiente
    - Preparando ambiente
    - Nomes dinâmicos
    - Banco de dados
    - Para saber mais: Object-Relational-Mapper (ORM)
    - Criando dados
    - Models no Django
    - Para saber mais: Models
    - Faça como eu fiz
    - O que aprendemos?
- Admin | 10/10
    - Projeto da aula anterior
    - Acessando o banco
    - Passando uma referência
    - Django Admin
    - Para saber mais: Admin
    - CRUD no Admin
    - Incluindo categoria
    - Makemigrations e migrate
    - Faça como eu fiz
    - O que aprendemos?
- Avançado no admin 7/7
    - Projeto da aula anterior
    - Personalizando o admin
    - Funcionalidade de publicação
    - Incrementando o index
    - Django Admin
    - Faça como eu fiz
    - O que aprendemos ?
- Imagens e filtros | 0/7
    - Projeto da aula anterior
    - Novo caminho para fotos
    - Imagem ''not found''
    - Alterando template imagem
    - Configurações do Admin
    - Faça como eu fiz
    - O que aprendemos?
- Mecanismo de Busca | 0/10
    - Projeto da aula anterior
    - Funcionalidade buscar
    - View de buscar
    - Autenticação e autorização
    - Foto no banco de dados
    - Faça como eu fiz
    - Projeto final
    - O que aprendemos?
    - Conclusão
    - Créditos

## Links Úteis

- [Curso de Django: templates e boas práticas](https://cursos.alura.com.br/course/django-templates-boas-praticas)
- [Instalando o Python no Windows](https://youtu.be/wFB3yZqHxL0)
- [Models Django](https://docs.djangoproject.com/pt-br/4.1/topics/db/models/)

## Instalação
Para criar uma virtualenv na pasta "alura_space", usamos o comando python -m virtualenv .venv, sendo ".venv" o nome do nosso ambiente virtual.
```sh
python -m virtualenv .venv
```
Após isso, clicamos na pasta "Scripts" e depois em "Activate". Precisamos chegar na pasta "activate" para ativarmos o nosso ambiente virtual. Acessaremos novamente o terminal, e digitamos .venv\Scripts\activate , sendo "Scripts" o nome da pasta que vimos antes de chegarmos em "activate".
```sh
.venv\Scripts\activate
```
Os pacotes e módulos estão localizados no arquivo "requirements.txt".
```sh
requirements.txt
```

Para instalar todos de uma vez só, acesse o terminal e rodamos pip install -r requirements.txt.
```sh
pip install -r requirements.txt
```

Django instalado! Com base nisso, para iniciar o projeto e basta verificar se irá rodar com sucesso. No terminal, executando o comando python manage.py runserver.
```sh
python manage.py runserver
```

## Pacotes utilizados

| Nome | Site |
| ------ | ------ |
| asgiref | https://pypi.org/project/asgiref |
| Django | https://www.djangoproject.com/ |
| python-dotenv | https://pypi.org/project/python-dotenv/ |
| sqlparse | https://pypi.org/project/sqlparse/ |
