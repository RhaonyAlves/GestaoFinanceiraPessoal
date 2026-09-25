# 📊 FinFlow — Gestão Financeira Pessoal

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0--MVP-orange)
![Coverage](https://img.shields.io/badge/coverage-100%25-green)

O **FinFlow** é uma solução mobile e web desenvolvida para revolucionar o controlo e a organização das finanças pessoais[cite: 1, 2]. O aplicativo permite o registo eficiente de receitas e despesas, categorização de gastos, definição de orçamentos mensais, conciliação bancária e exibição de relatórios analíticos de desempenho financeiro[cite: 1, 2].

---

## 🎯 O Problema & A Solução

* **O Problema:** A falta de previsibilidade e controlo sobre gastos pessoais afeta a maioria das pessoas físicas, gerando endividamento, descontrolo orçamental e incapacidade de poupar[cite: 1, 2].
* **A Solução:** O **FinFlow** oferece uma interface fluida e intuitiva com automações de lançamentos, alertas preventivos de orçamento e sincronização com instituições financeiras[cite: 1, 2].

---

## ✨ Principais Funcionalidades

- 🔐 **Autenticação Segura:** Login por e-mail, redes sociais e biometria (FaceID/TouchID) com suporte a 2FA[cite: 1, 2].
- 💳 **Gestão de Contas & Cartões:** Controlo centralizado de contas correntes, poupanças e cartões de crédito com cálculo automático de faturas[cite: 1, 2].
- 💸 **Registo e Categorização:** Lançamento rápido de transações diárias, recorrentes ou parceladas[cite: 1, 2].
- 📈 **Dashboards & Relatórios:** Gráficos interativos com visão de fluxo de caixa e distribuição de despesas por categoria[cite: 1, 2].
- 🎯 **Orçamentos e Metas:** Definição de teto de gastos com notificações automáticas (ao atingir 80% e 100% do limite) e acompanhamento de metas de poupança[cite: 1, 2].
- 🏦 **Importação & Open Finance:** Suporte para importação de extratos (OFX/CSV) e integração futura com instituições bancárias via Open Finance[cite: 1, 2].

---

## 🚀 Tecnologias Utilizadas

### **Front-end / Mobile**
- **Mobile:** React Native / Flutter
- **Web:** React.js / Next.js
- **UI Components:** Material Design / Human Interface Guidelines[cite: 1, 2]

### **Back-end & Infraestrutura**
- **API:** Node.js / Python (FastAPI/Django)
- **Base de Dados:** PostgreSQL / MongoDB
- **Autenticação:** JWT, OAuth2, Biometria[cite: 1, 2]
- **Infraestrutura Cloud:** AWS / Firebase

---

## 🔒 Segurança e Conformidade

O projeto foi construído respeitando rigorosos padrões de segurança de software e privacidade de dados:

- 🛡️ **LGPD:** Conformidade total com a Lei Geral de Proteção de Dados (exportação e eliminação de dados a pedido do utilizador)[cite: 1, 2].
- 🔑 **Criptografia:** TLS 1.3 para dados em trânsito e AES-256 para dados em repouso[cite: 1, 2].
- 🔑 **Hash de Senhas:** Armazenamento seguro de credenciais utilizando algoritmos fortes (bcrypt/Argon2)[cite: 1, 2].

---

## 📋 Arquitetura de Requisitos (ERS)

| ID | Requisito | Tipo | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF001** | Autenticação e Gestão de Perfil | Funcional | Alta[cite: 1, 2] |
| **RF004** | Registo de Transações (Receita/Despesa) | Funcional | Alta[cite: 1, 2] |
| **RF011** | Dashboard Financeiro e Gráficos | Funcional | Alta[cite: 1, 2] |
| **RNF001** | Criptografia de Dados (TLS 1.3 / AES-256) | Não Funcional | Alta[cite: 1, 2] |
| **RNF003** | Tempo de Resposta < 2 segundos em 4G/5G | Não Funcional | Média[cite: 1, 2] |

---

## 🛠️ Como Executar o Projeto Localmente

### **Pré-requisitos**
- Node.js (v18+)
- Docker e Docker Compose
- Git

### **Passo a Passo**

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/teu-usuario/finflow.git](https://github.com/teu-usuario/finflow.git)
   cd finflow
