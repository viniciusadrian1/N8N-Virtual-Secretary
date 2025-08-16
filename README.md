# 🤖 Secretária Virtual - n8n Workflow / Virtual Secretary - n8n Workflow

Este repositório contém o workflow **Secretária** (principal) e seus workflows auxiliares, desenvolvidos no **n8n Cloud**, para atuar como uma **secretária virtual inteligente**.  
Os **workflows auxiliares** são responsáveis por acionar e executar funções específicas dentro do fluxo principal.

---

This repository contains the **Secretary** workflow (main) and its auxiliary workflows, developed in **n8n Cloud**, to act as an **intelligent virtual secretary**.  
The **auxiliary workflows** are responsible for triggering and executing specific functions inside the main flow.

---

## 📌 Descrição / Description
- **PT**:  
  O workflow **Secretária** centraliza o atendimento, organização de contatos, registros e agendamentos.  
  Os workflows auxiliares funcionam como módulos independentes, chamados pelo fluxo principal para realizar tarefas específicas:  

  - `MCP Google Calendar.json` → integração com Google Calendar  
  - `Baixar e enviar arquivo do Google Drive.json` → manipulação de arquivos no Google Drive  
  - `Atualizar status.json` → atualização de status em tempo real  
  - `Assistente interno.json` → suporte interno e IA auxiliar  

- **EN**:  
  The **Secretary** workflow centralizes customer service, contact management, records, and scheduling.  
  The auxiliary workflows work as independent modules, called by the main flow to perform specific tasks:  

  - `MCP Google Calendar.json` → Google Calendar integration  
  - `Baixar e enviar arquivo do Google Drive.json` → Google Drive file handling  
  - `Atualizar status.json` → real-time status updates  
  - `Assistente interno.json` → internal assistant and AI support  

---

## 🚀 Funcionalidades / Features
- **PT**:
  - 📩 Receber e organizar mensagens via Webhook  
  - 📝 Registrar informações automaticamente em **Google Sheets** ou **CRM**  
  - 📆 Gerenciar agendamentos e lembretes com Google Calendar  
  - 📂 Baixar e enviar arquivos do Google Drive  
  - 🤖 Usar IA como assistente interno para automações inteligentes  
  - 🔗 Ativar funções extras através de workflows auxiliares  

- **EN**:
  - 📩 Receive and organize messages via Webhook  
  - 📝 Automatically log information into **Google Sheets** or **CRM**  
  - 📆 Manage scheduling and reminders with Google Calendar  
  - 📂 Download and send files from Google Drive  
  - 🤖 Use AI as an internal assistant for smart automation  
  - 🔗 Trigger extra functions through auxiliary workflows  

---

## 📂 Estrutura do Projeto / Project Structure
- `1. Secretária.json` → **Workflow principal / Main workflow**  
- `2. MCP Google Calendar.json` → Workflow auxiliar / Auxiliary workflow  
- `3. Baixar e enviar arquivo do Google Drive.json` → Workflow auxiliar / Auxiliary workflow  
- `4. Atualizar status.json` → Workflow auxiliar / Auxiliary workflow  
- `5. Assistente interno.json` → Workflow auxiliar / Auxiliary workflow  
- `README.md` → Este guia / This guide  

---

## 🛠️ Requisitos / Requirements
- Conta no [n8n Cloud](https://n8n.io) ou instalação local do **n8n**  
- Credenciais configuradas:
  - **Google Sheets API**  
  - **Google Calendar API**  
  - **Google Drive API**  
  - **CRM** (Zoho, HubSpot, Pipedrive, etc.)  
  - **Webhook URL**  

---

## 📥 Como Importar / How to Import
**PT**  
1. Acesse o painel do **n8n**  
2. Clique em **Import** → **From File**  
3. Importe primeiro o workflow `1. Secretária.json`  
4. Em seguida, importe os workflows auxiliares (2 a 5)  
5. Configure as credenciais e ative os fluxos 🚀  

**EN**  
1. Go to your **n8n** dashboard  
2. Click **Import** → **From File**  
3. Import the `1. Secretária.json` workflow first  
4. Then import the auxiliary workflows (2 to 5)  
5. Configure the credentials and activate the flows 🚀  

---

## 👨‍💻 Autor / Author
- **Vinícius Adrian Siqueira**

---

## 👨‍💻 Contribuição / Contribution
- **PT**: Sugestões e melhorias são bem-vindas!  
- **EN**: Suggestions and improvements are welcome!  

---

✨ **PT**: Secretária Virtual – automação inteligente de atendimento com n8n  
✨ **EN**: Virtual Secretary – smart customer service automation with n8n  
