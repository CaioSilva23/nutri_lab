# PROJETO NUTRI_LAB
Um projeto de uma plataforma onde nutricionistas gerenciam seus pacientes, feito com Django e Python.

### TODOs
Abaixo uma lista do que adicionei ou ainda pretendo adicionar.

- [x] Cadastrar de Usuário 
- [x] Autenticação de Usuário
- [x] Login
- [x] Cadastro de Pacientes 
- [x] Cadastro de Refeições e Opções


### Tutorial
Abaixo uma lista de comandos para clonar e configurar este projeto na sua 
máquina local:

- Instalar git (Windows, Linux e Mac) e depois:

```
git clone https://github.com/CaioSilva23/nutri_lab.git
```

- Para **Windows**:

```
cd nutri_lab
python -m venv venv
venv\Scripts\activate
python -m pip install --upgrade pip setuptools wheel --user
pip install Django, Pillow
python manage.py migrate
python manage.py runserver
```

- Para **Linux**:

```
cd nutri_lab
python3.10 -m venv venv
. venv/bin/activate
pip install Django, Pillow
python manage.py migrate
python manage.py runserver
```

Pronto!

