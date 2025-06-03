# Aula-02: Criação do Ambiente Virtual 

Nesta aula vamos criar o ambiente Virtual para o projeto. 


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

## Passo 4: Gerar arquivo requirements.txt
```bash
pip3 freeze > requirements.txt
``` 

## Passo 5: Verifique o arquivo requirements.txt
```bash
$ cat requirements.txt 
asgiref==3.8.1
Django==5.2.1
sqlparse==0.5.3
``` 
## Instalar as bibliotecas utilizando o arquivo requirements.txt
Quando for enviar seu projeto para outra pessoa utilize o comando para a instalação 
de todas as dependências do projeto.
```bash
$ cat requirements.txt 
$ pip3 install -r requirements.txt 
``` 
