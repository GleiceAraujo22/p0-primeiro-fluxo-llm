# P0 — Primeiro fluxo com LLM

![Status](https://img.shields.io/badge/Status-Em%20desenvolvimento-orange)
![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-Interface%20Web-red?logo=streamlit&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-Integração-purple)
![GitHub](https://img.shields.io/badge/GitHub-Versionamento-black?logo=github)

## Sobre o projeto

Projeto desenvolvido como parte do Programa de Capacitação em Desenvolvimento de Agentes de IA.

O objetivo é identificar um problema real envolvendo interpretação ou geração de texto e desenvolver uma aplicação web em Python que utilize um Large Language Model (LLM) por meio de uma API.

## Objetivos técnicos

- Desenvolvimento de aplicação web em Python.
- Construção da interface utilizando Streamlit.
- Integração com API de um LLM institucional.
- Versionamento com Git e GitHub.
- Tratamento de erros e proteção de credenciais.
- Organização de ambiente reproduzível.
- Testes e documentação técnica.

## Tecnologias

- Python 3.11
- Streamlit
- OpenAI Python SDK
- python-dotenv
- pytest
- Git e GitHub
- Docker
- API institucional de LLM

## Como executar o projeto

### Pré-requisitos

- Python 3.10 ou superior.
- Git.
- Visual Studio Code (recomendado).
- Acesso à plataforma Devel LLM.

### Instalação

Clone o repositório:

```bash
git clone https://github.com/GleiceAraujo22/p0-primeiro-fluxo-llm.git
```

Acesse a pasta do projeto:

```bash
cd p0-primeiro-fluxo-llm
```

Crie o ambiente virtual:

```bash
python -m venv .venv
```

Ative o ambiente virtual no Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Instale as dependências:

```bash
python -m pip install -r requirements.txt
```

### Configuração do ambiente

Crie o arquivo `.env` a partir do modelo disponibilizado:

```powershell
Copy-Item .env.example .env
```

Configure as variáveis de ambiente conforme as orientações da plataforma institucional.

**Importante:** o arquivo `.env` contém configurações locais e não deve ser enviado ao GitHub.

### Execução da aplicação

Instruções de execução serão adicionadas após a implementação da aplicação web.

### Testes

Os testes automatizados serão executados utilizando pytest.

Instruções específicas serão adicionadas após a implementação dos primeiros testes.

## Evolução do projeto

- [ ] Nível Básico
- [ ] Nível Intermediário
- [ ] Nível Avançado

## Status

Em desenvolvimento.
