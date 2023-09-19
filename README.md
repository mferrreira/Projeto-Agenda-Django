# Iniciar o projeto Django

```
python -m venv venv
source venv/bin/activate
pip install django
django-admin startproject project .

python manage.py startapp nome_do_app
python manage.py runserver
```

# Configurar o git

```
git config --global user.name 'nome'
git config --global user.email 'email@dominio.com'
git config --global init.defaultBranch 'main'
git init

# Configurar o .gitignore

git add .
git commit -m 'Initial'

# Criar repositório no github

git remote add origin URL_DO_GIT
git push origin main
```

# Migrando a base de dados do Django

```
python manage.py makemigrations
python manage.py migrate
```

# Criando e modificando a senha de um super usuário do Django

```
python manage.py createsuperuser
python manage.py changepassword USERNAME
```