<p align="center">
  <a href="https://github.com/maryvitoria002/Portal-3AII---PSW" target="_blank">
    <!-- Substitua pelo caminho real do logo no seu repo -->
    <img src="/images/logo.png" width="400" alt="Portal 3AII Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/maryvitoria002/Portal-3AII---PSW/releases">
    <!-- opcional: badge de releases -->
    <!-- <img src="https://img.shields.io/github/v/release/maryvitoria002/Portal-3AII---PSW?label=Stable&style=flat-square" alt="Stable Release"> -->
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
  <em>O Portal 3AII</em> é um sistema acadêmico completo desenvolvido para gerenciamento de uma turma de ensino médio técnico integrado. O sistema facilita a comunicação entre estudantes e administradores, oferecendo funcionalidades de gestão de notas, atividades, materiais didáticos, eventos, agenda e organização institucional.
</p>

<p align="center">
  <!-- Substitua pelo seu screenshot -->
  <img src="/images/printSistema.png" alt="Portal 3AII Screenshot">
</p>

---

📚 Documentação
A melhor forma de conhecer o projeto é pela documentação no diretório <a href="docs/README.md">docs/</a>.

- **Visão geral + minimundo**: `docs/README.md`  
- **Modelo de dados (DER)**: `docs/der.md`  
- **Guia de instalação**: `docs/installation.md`  
- **Guia de contribuição**: `docs/CONTRIBUTING.md`

---

👤 Autores

- **@maryvitoria002** - manutenção do repositório, desenvolvimento e coordenação (<a href="https://github.com/maryvitoria002">GitHub</a>)
- **@PedroHTP** - manutenção do repositório, desenvolvimento e coordenação (<a href="https://github.com/PedroHTP">GitHub</a>)
- **@kelvinstanley** - manutenção do repositório, desenvolvimento e coordenação (<a href="https://github.com/kelvinstanley">GitHub</a>)


> Para contato sobre roadmap/arquitetura: `maryvitoria054@gmail.com`.

---

👥 Contribuidores

Agradecimento a todas as pessoas que colaboram com código, documentação, design, testes e ideias.

<a href="https://github.com/maryvitoria002/Portal-3AII---PSW/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=maryvitoria002/Portal-3AII---PSW" alt="Contributors" />
</a>

<!-- Lista opcional de destaques:
- @usuario1 — docs e scripts de deploy
- @usuario2 — DER e validações
- @usuario3 — UI/UX e acessibilidade
-->

---

 🧱 Feito com

- **Django 4.2.x** (back-end)  
- **Python 3.10+** (linguagem)  
- **Bootstrap 5** (front-end)  
- **SQLite / PostgreSQL** (banco de dados)

---

 ⚙️ Instalação (resumo)
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
