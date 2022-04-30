# drf-clientes

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/LombaAnderson/drf-clientes/blob/main/LICENSE)

# Sobre o projeto
  Nesse projeto foi feito o versionamento de uma aplicação de cursos de uma escola utilizando QueryParameterVersioning. A API de cursos foi atualizada sem que se perca 
os seus endpoints que já estavam funcionando. Foi desenvolvido também níveis de permissões diferentes da API e por último foi feita integração da API Python/Django REST com uma API desenvolvida com React.



## Imagem de exemplo da versão principal do projeto
<div align="center">
<img src="https://user-images.githubusercontent.com/60937513/166110204-00fe4bca-8983-4207-9fb3-fc973b81af68.png" width="700" />
</div>

## Print da versão 2 com funcionalidades a mais.
<div align="center">
<img src="https://user-images.githubusercontent.com/60937513/166110473-6c593031-6602-4383-9140-f9e186099e1f.png" width="700" />
</div>

# principais Tecnologias utilizadas
- Python

 Principais Frameworks
-Django
-Django Rest Framework
-Python-decouple

-Front
-ReactJS


# Instruções para compilar, testar e rodar o projeto

```bash
# Clonar repositório
git clone https://github.com/LombaAnderson/drf-clientes

# Criação do ambiente de desenvolvimento do Python
-python -m venv venv

# Ativar o ambiente de desenvolvimento(venv)
-source venv/Scripts/.activate

# Instalação do Django (Atenção: instalar somente após a ativação da venv)
-pip install django
-pip install djangorestframework
 
# Comando de criação do projeto
-django-admin startproject setup .

# Criação do servidor
-python manage.py runserver

# Acesso ao servidor Django
http://127.0.0.1:8000/

# Apps 
-django-admin startapp escola

# Preparação das migrations
- python manage.py makemigrations

# Envio das migrations configuradas para o banco de dados
- python manage.py migrate


```

# Autor

Anderson Lomba de Oliveira

Linkedin

https://www.linkedin.com/in/anderson-lomba-140279142/

Portfólio

https://www.lombanderson.epizy.com

# Agradecimentos

Agradeço ao meu Deus que sempre me ajuda e a minha esposa que amo muito! 


