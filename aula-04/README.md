# Aula-04: Configurações Iniciais no Projeto Django
Nesta aula vamos alterar o arquivo settings.py para ajustar a linguagem 
e o fuso-horário

## Passo 1: Edite o Arquivo settings.py 

Procure em seu arquivo de configuração por LANGUAGE_CODE e TIME_ZONE: 
```python
LANGUAGE_CODE = 'en-us' 
TIME_ZONE = 'UTC' 
``` 
Faça as seguintes alterações: 
```python
LANGUAGE_CODE = 'pt-br' 
TIME_ZONE = 'America/Sao_Paulo' 
``` 
Passo 2:  Execute o seu servidor e verifique o resultado 
```bash
./manage.py runserver 
``` 

