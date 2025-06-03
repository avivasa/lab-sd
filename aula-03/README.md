# Aula-03: Criação do Projeto Django

Nesta aula vamos criar o projeto Django 


## Passo 1: Criação do Ambiente Virtual
``` bash
python3 -m venv env
``` 

## Passo 2: Ativação do Ambiente Virtual
``` bash
source env/bin/activate 
``` 

## Passo 3: Instalação do Django
```bash
pip3 install django
``` 

## Passo 4: Criar o Projeto Django
```bash
django-admin startproject monografias .
``` 

## Passo 5: Faça a migração
```bash
./manage.py migrate
``` 
## Passo 6: Teste seu Projeto
Abra seu navegador no endereço http://locahost:8000 e verifique o funcionamento do seu projeto 
```bash
./manage runserver
``` 
