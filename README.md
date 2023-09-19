# Iniciar o projeto Django

```
python -m venv venv
source venv/bin/activate
pip install django
django-admin startproject project .
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
git push origin main

# Criar repositório no github

git remote add origin URL_DO_GIT
```