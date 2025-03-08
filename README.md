# Python Backend DevOps - Roadmap de Estudos

## 📌 Sobre o Projeto
Este repositório tem como objetivo ser um guia de estudos para desenvolvedores backend Python que desejam aprender sobre DevOps. O projeto está estruturado para ser seguido em **90 dias**, incluindo conceitos, exercícios práticos e projetos para reforçar o aprendizado.

## 📂 Estrutura do Repositório

```
📁 python-backend-devops
│── 📄 README.md             # Explicação do projeto
│── 📄 .gitignore            # Arquivos ignorados pelo Git
│── 📄 pyproject.toml        # Configuração do Poetry
│── 📄 .python-version       # Versão do Python gerenciada pelo pyenv
│── 📁 .venv                 # Ambiente virtual gerenciado pelo Poetry (não enviar para o GitHub)
│── 📁 src                   # Código-fonte principal
│   ├── 📁 fundamentos       # Conceitos básicos de Python
│   ├── 📁 poo               # Programação Orientada a Objetos
│   ├── 📁 banco_de_dados    # SQL, NoSQL, ORM (SQLAlchemy/Django ORM)
│   ├── 📁 web               # Desenvolvimento Web com Flask/Django
│   ├── 📁 devops            # CI/CD, Docker, Kubernetes
│   ├── 📁 seguranca         # Criptografia, hashing, boas práticas
│   ├── 📁 redes             # Programação com sockets, HTTP, APIs REST
│   ├── 📁 avancado          # Métodos mágicos, metaprogramação, C extensions
│── 📁 tests                 # Testes automatizados para cada módulo
│   ├── 📄 test_fundamentos.py
│   ├── 📄 test_poo.py
│   ├── 📄 test_web.py
│── 📁 projetos              # Projetos práticos por módulo
│   ├── 📁 projeto1-fundamentos
│   ├── 📁 projeto2-api-rest
│   ├── 📁 projeto3-devops
│── 📁 docs                  # Documentação do projeto
│   ├── 📄 requisitos.md
│   ├── 📄 roadmap.md
│── 📁 scripts               # Scripts úteis para automação
│   ├── 📄 setup.sh          # Instalação de dependências
│   ├── 📄 run_tests.sh      # Rodar testes automaticamente
```

## 🚀 Como Configurar o Ambiente

### 1️⃣ Clonar o Repositório
```sh
git clone <URL_DO_REPOSITORIO>
cd python-backend-devops
```

### 2️⃣ Configurar o pyenv e Poetry
```sh
pyenv install 3.11  # Instala a versão desejada
pyenv local 3.11    # Define a versão do Python para o projeto

poetry install      # Instala dependências
```

### 3️⃣ Rodar Testes Automatizados
```sh
pytest tests/
```

### 4️⃣ Enviar Atualizações para o GitHub
```sh
git add .
git commit -m "Adiciona novas funcionalidades"
git push origin main
```

## 📅 Roadmap de 90 Dias
O estudo está dividido em 3 fases:

1️⃣ **Fundamentos de Python** (Dias 1-30)
- Tipos de dados, controle de fluxo, funções e POO
- Exercícios e um mini-projeto

2️⃣ **Banco de Dados e Web** (Dias 31-60)
- SQL, NoSQL, Flask/Django, APIs REST
- Projeto: API completa com Flask/Django

3️⃣ **DevOps e Avançado** (Dias 61-90)
- Docker, Kubernetes, CI/CD, Segurança, Redes
- Projeto final: App escalável com CI/CD
---

Vamos juntos nessa jornada! 🚀

