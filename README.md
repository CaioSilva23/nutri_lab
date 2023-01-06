<div align="center" id="top"> 
  <img src="#" alt="" />

<!-- &#xa0; -->


</div>

<div align="center"> 
  <h1 align="center">NUTRILAB - SISTEMA DE GERENCIAMENTO DE PACIENTES</h1>
</div>

<p align="center">
  <img alt="Principal linguagem do projeto" src="https://img.shields.io/github/languages/top/CaioSilva23/nutri_lab" />

  <img alt="Quantidade de linguagens utilizadas" src="https://img.shields.io/github/languages/count/caiosilva23/nutri_lab" />

  <img alt="Tamanho do repositório" src="https://img.shields.io/github/repo-size/caiosilva23/nutri_lab" />


</p>

<!-- Status -->

<!-- <h4 align="center">

</h4>

<hr> -->

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#sparkles-funcionalidades">Funcionalidades</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-pré-requisitos">Pré requisitos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a> &#xa0; | &#xa0;
  <a href="#memo-licença">Licença</a> &#xa0; | &#xa0;
  <a href="https://github.com/caiosilva23" target="_blank">Autor</a>
</p>

<p align="center">
  <img alt="Login" src="public/login.png" width=250>
  <img alt="home" src="public/cadastro.png" width=250>
  <img alt="execucao" src="public/dados.png" width=250>
<img alt="execucao" src="public/plano.png" width=250>
  <img alt="pregoes" src="public/home.png" width=250>
</p>

## 🎯 Sobre

O projeto desenvolvindo para nutricionistas gereciarem seus parcientes desde o cadastro até o plano alimentar.

## ✨ Funcionalidades

✔️ Autenticação de Usuário;\
✔️ Cadastro;\
✔️ Login/Logout;\
✔️ CRUD de Pacientes;\
✔️ CRUD de Refeições;\
✔️ CRUD de Plano Alimentar;\
✔️ CRUD de Dados do Paciente;\



## 🚀 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Python](https://www.python.org/)
- [Django](https://nodejs.org/en/)
- [JavaScript](https://www.javascript.com/)
- [SQLite](https://www.sqlite.org/index.html)
- [Bootstrap](https://getbootstrap.com/)

## ✅ Pré requisitos

Antes de começar 🏁, você precisa ter o [Python](https://www.python.org/downloads/) instalado em sua maquina.

## 🏁 Começando

1 - Primeiro clone o repositório e entre na pasta do projeto.

```bash
# Clone este repositório
$ git clone https://github.com/CaioSilva23/divisao-externa.git

# Entre na pasta
$ cd nutri_lab
```

2 - Segundo inicie um ambiente virtual

```bash
# Criar
  # Linux
    $ python3 -m venv venv
  # Windows
    $ python -m venv venv

#Ativar
  # Linux
    $ source venv/bin/activate
  # Windows
    $ venv/Scripts/Activate

# Caso algum comando retorne um erro de permissão execute o código e tente novamente:

  $ Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

3 - Instale as dependências

```bash
# Instale as dependências
# Linux
$ pip3 install -r requirements.txt
# Windows
$ pip install -r requirements.txt
```

4 - Faça as migrações.

```bash
# Linux
python3 manage.py migrate
# Windows
python manage.py migrate
```

5 - Inicie a aplicação

```bash
# Para iniciar o projeto
# Linux
$ python3 manage.py runserver
# Windows
$ python manage.py runserver

# O app vai inicializar em <http://127.0.0.1:8000/>

# Para iniciar o projeto em uma porta especifica
$ python manage.py runserver <porta>

# O app vai inicializar em <http://127.0.0.1:<porta>/>

```

## 📝 Licença

Este projeto está sob licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

Desenvolvido por <a href="https://github.com/caiosilva23" target="_blank">Caio Silva</a>

&#xa0;

<a href="#top">Voltar para o topo</a>
