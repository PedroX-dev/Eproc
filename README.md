# EprocAuto — Automação Inteligente do Sistema EPROC

## 📌 Visão Geral
**EprocAuto** é uma aplicação de automação desenvolvida em **Python**, criada para **otimizar, padronizar e escalar** processos repetitivos executados no sistema **EPROC**, amplamente utilizado em fluxos administrativos e jurídicos.

A aplicação foi projetada para operar de forma **autônoma e confiável**, realizando desde o **login automatizado**, passando pela **navegação inteligente entre telas**, até a **análise, tratamento e extração de dados de documentos processuais**, com mínima intervenção humana.

O foco principal do projeto é **reduzir esforço manual**, **diminuir falhas operacionais** e **aumentar significativamente a produtividade**, tornando o fluxo mais rápido, previsível e sustentável em ambientes institucionais.

---

## ⚙️ Funcionamento da Automação

A automação simula a interação humana com o sistema EPROC de forma controlada, respeitando a ordem e a lógica do fluxo original do sistema. O processo ocorre em etapas bem definidas:

1. **Autenticação Automatizada**
   - Preenchimento automático de credenciais
   - Reaproveitamento de sessão por meio de cookies
   - Detecção de sessão expirada e novo login quando necessário

2. **Navegação Inteligente**
   - Acesso automatizado às áreas corretas do sistema
   - Controle de carregamento de páginas e elementos dinâmicos
   - Tratamento de exceções e falhas de carregamento

3. **Leitura e Extração de Dados**
   - Análise de documentos processuais
   - Extração de informações relevantes, como:
     - Identificadores (ex: CPF)
     - Município
     - Tipo de documento ou processo
   - Tratamento e padronização dos dados extraídos

4. **Processamento e Organização**
   - Classificação automática das informações
   - Preparação dos dados para uso posterior
   - Execução consistente mesmo em grandes volumes de petições

---

## 🖥️ Interface Gráfica (GUI)

Para facilitar o uso por **usuários não técnicos**, o projeto conta com uma **interface gráfica intuitiva**, desenvolvida em **Tkinter com ttkbootstrap**.

A interface permite:

- Iniciar e acompanhar a automação de forma visual
- Visualizar logs em tempo real durante a execução
- Receber feedback claro sobre o status do processo
- Executar a automação sem necessidade de linha de comando

Isso torna a ferramenta acessível para equipes administrativas, eliminando a dependência direta de conhecimento técnico.

---

## 🎥 Demonstração e Análise de Resultados

Por fins de demonstração, este repositório apresenta um **vídeo do processo sendo executado em tempo real**, evidenciando:

- A execução completa da automação
- O fluxo contínuo sem intervenção manual
- A estabilidade do processo em ambiente real

Em seguida, são apresentados os dados comparativos de **Antes e Depois da automação**, destacando o impacto direto no ganho de eficiência, redução de tempo e aumento expressivo da capacidade operacional.

---

## 🧩 Explicação Geral do Projeto

O EprocAuto foi desenvolvido com uma **arquitetura modular**, separando claramente responsabilidades como autenticação, extração de dados, interface gráfica e utilitários. Essa abordagem facilita:

- Manutenção do código
- Evolução do projeto
- Adaptação a mudanças no sistema EPROC
- Reutilização de componentes em novas automações

O projeto representa uma aplicação prática de **engenharia de software**, **automação de processos** e **otimização de fluxos reais**, indo além de um exercício acadêmico e sendo aplicado em um contexto institucional real.


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



