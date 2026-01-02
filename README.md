# 🤖 EprocAuto — Automação Inteligente do Sistema EPROC

## 📌 Visão Geral

**EprocAuto** é uma aplicação de automação desenvolvida em **Python**, criada para otimizar e padronizar processos repetitivos realizados no sistema **EPROC**, amplamente utilizado em fluxos administrativos e jurídicos.

O projeto automatiza desde o **login**, **navegação**, **análise** e **tratamento de documentos**, até a **extração de informações relevantes**, reduzindo drasticamente o tempo de execução manual, minimizando erros humanos e aumentando a produtividade operacional.

A fim de curiosidade, apresentarei o vídeo do processo sendo executado em tempo real, depois, evidenciarei o Antes e Depois da automação; por fim será feito a explicação do projeto.

---

https://github.com/user-attachments/assets/b0705393-2549-435d-bf65-1bb73f5761c1

---
## 📈 Resultados Obtidos

### 🔄 Comparativo Antes x Depois da Automação

#### ❌ Antes
- **50 petições por mês**
- **5 minutos por petição**
- **0,2 petições por minuto**

#### ✅ Depois
- **50 petições por dia**
- **1 minuto por petição**
- **1500 petições por mês**

---

### 🚀 Impacto da Automação

- 📈 **400% de aumento na eficiência**
- ⏱️ **Redução de 80% no tempo por petição**
- 🔥 **Aumento de 2900% no número de petições processadas por mês**

Esses resultados evidenciam o impacto direto da automação no ganho de produtividade, escalabilidade do processo e redução significativa de esforço manual, tornando o fluxo mais rápido, confiável e sustentável para uso institucional.

---

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
```
---

## 🧪 Status do Projeto

🟢 **Em uso e em evolução**

O projeto continua sendo aprimorado com foco em:

- Melhorias de desempenho  
- Aprimoramento da interface gráfica  
- Implementação de novas rotinas automatizadas  
- Maior robustez frente a mudanças no sistema EPROC
- 
---

## 👨‍💻 Autor

**Pedro Henrique Santos**  
Estudante de Ciência da Computação  
Estagiário em Automação de Processos  

📌 Projeto desenvolvido com foco em **automação real**, **impacto institucional** e **boas práticas de engenharia de software**.

---

## 📄 Licença

Este projeto é disponibilizado apenas para fins **educacionais e demonstrativos**.  
O uso comercial ou redistribuição deve respeitar políticas institucionais e legislações aplicáveis.

---



