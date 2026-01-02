# 🤖 EprocAuto — Automação Inteligente do Sistema EPROC

## 📌 Visão Geral

**EprocAuto** é uma aplicação de automação desenvolvida em **Python**, criada para otimizar e padronizar processos repetitivos realizados no sistema **EPROC**, amplamente utilizado em fluxos administrativos e jurídicos.

O projeto automatiza desde o **login**, **navegação**, **análise** e **tratamento de documentos**, até a **extração de informações relevantes**, reduzindo drasticamente o tempo de execução manual, minimizando erros humanos e aumentando a produtividade operacional.

> 🚀 Projeto desenvolvido e aplicado em contexto real de estágio, com foco em automação institucional e ganho de eficiência.

---

## 🎯 Objetivos do Projeto

- Automatizar tarefas repetitivas no sistema EPROC  
- Reduzir tempo operacional e falhas humanas  
- Padronizar processos administrativos  
- Facilitar o uso por usuários não técnicos  
- Criar uma solução reutilizável e escalável  

---

## 🧠 Principais Funcionalidades

- 🔐 **Login Automatizado**
  - Preenchimento automático de credenciais
  - Reaproveitamento de sessão via cookies
  - Detecção de sessão expirada

- 🖥️ **Interface Gráfica (GUI)**
  - Interface amigável para controle da automação
  - Feedback visual em tempo real (logs)
  - Execução guiada sem necessidade de linha de comando

- 📂 **Processamento de Documentos**
  - Navegação automatizada no EPROC
  - Leitura e classificação de documentos
  - Extração de informações relevantes (ex: CPF, município, tipo de processo)

- ⚙️ **Automação Robusta**
  - Tratamento de exceções
  - Execução estável mesmo em fluxos longos
  - Logs detalhados de cada etapa do processo

- 🧩 **Arquitetura Modular**
  - Separação clara entre autenticação, extração, interface e utilitários
  - Código organizado para fácil manutenção e expansão

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.12**
- **Playwright** (automação de navegador)
- **Tkinter + ttkbootstrap** (interface gráfica)
- **Nuitka** (geração de executável)
- **Inno Setup** (instalador Windows)
- **HTML / DOM Automation**
- **Regex & Tratamento de Texto**

---

## 🗂️ Estrutura do Projeto

```text
EprocAuto/
├── Interface/          # Interface gráfica (GUI)
├── auth/               # Autenticação e gerenciamento de sessão
├── extracao/           # Extração e análise de dados
├── tratamentoSessao/   # Controle de cookies e sessão
├── utils/              # Utilitários, logs e recursos
├── templates/          # Modelos e estruturas auxiliares
└── MenuApp.py          # Ponto de entrada da aplicação

