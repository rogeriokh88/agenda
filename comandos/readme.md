inicia o projeto django

'''
python -m venv venv
.venv/bin/activate
pip install django
django-admin startproject project .
python manage.py startapp contact
python manage.py sunserver


configurar o git

'''
git config --global user.name 'seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
git init
git add .
git commit -m 'mensagem'
'''
'''
migrando a base de dados de django

'''
python manage.py makemigrations
python manage.py migrate

'''
criando e modificando a senha de um super usuario django
'''
'''
python manage.py createsuperuser
python manage.py changepassword USERNAME

'''
