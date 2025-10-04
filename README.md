<p align="center">
  <a href="https://github.com/maryvitoria002/Portal-3AII---PSW" target="_blank">
    <!-- Substitua pelo caminho real do logo no seu repo -->
    <img src="/images/logo.png" width="400" alt="Portal 3AII Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/maryvitoria002/Portal-3AII---PSW/releases">
    <img src="https://img.shields.io/github/v/release/maryvitoria002/Portal-3AII---PSW?label=Stable&style=flat-square" alt="Stable Release">
  </a>
  <a href="https://github.com/maryvitoria002/Portal-3AII---PSW/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/maryvitoria002/Portal-3AII---PSW/ci.yml?label=CI&style=flat-square" alt="CI">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/github/license/maryvitoria002/Portal-3AII---PSW.svg?label=License&style=flat-square" alt="License">
  </a>
  <a href="#">
    <img alt="Python Versions Supported" src="https://img.shields.io/badge/python-3.10%20|%203.11%20|%203.12-3776AB.svg?logo=python&logoColor=white&labelColor=555555">
  </a>
  <a href="#">
    <img alt="Framework" src="https://img.shields.io/badge/django-4.2-0C4B33.svg?logo=django&logoColor=white&labelColor=555555">
  </a>
</p>

<p align="center">
  <em>Portal 3AII</em> é um sistema acadêmico para gestão de uma turma de Ensino Médio Técnico Integrado,
  com módulos de notas, atividades, materiais, agenda, eventos e comunicação.
</p>

<p align="center">
  <!-- Substitua pelo seu screenshot -->
  <img src="docs/assets/screenshot-dashboard.png" alt="Portal 3AII Screenshot">
</p>

---

## 📚 Documentação
A melhor forma de conhecer o projeto é pela documentação no diretório <a href="docs/README.md">docs/</a>.

- **Visão geral + minimundo**: `docs/README.md`  
- **Modelo de dados (DER)**: `docs/der.md`  
- **Guia de instalação**: `docs/installation.md`  
- **Guia de contribuição**: `docs/CONTRIBUTING.md`

---

## ⚙️ Instalação (resumo)
Para instruções detalhadas, veja o <a href="docs/installation.md">Guia de Instalação</a>.

```bash
# 1) Clone o repositório
git clone https://github.com/maryvitoria002/Portal-3AII---PSW.git
cd Portal-3AII---PSW

# 2) Ambiente virtual (Python 3.10+)
python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/macOS:
source .venv/bin/activate

# 3) Dependências
pip install -r requirements.txt

# 4) Variáveis de ambiente
cp .env.example .env
# Edite SECRET_KEY, DEBUG, configurações do BD etc.

# 5) Banco e admin
python manage.py migrate
python manage.py createsuperuser

# 6) Executar
python manage.py runserver
