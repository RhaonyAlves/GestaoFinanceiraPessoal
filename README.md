# 📊 FinFlow — Gestão Financeira Pessoal

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0--MVP-orange)
![Coverage](https://img.shields.io/badge/coverage-100%25-green)

## 📋 Gestão Financeira Pessoal - FinFlow

Projeto: Gestão Financeira Pessoal (Organização Financeira)
Identificação: Rhaony Alves
Descriação do projeto

O FinFlow é um aplicativo de gestão financeira pessoal concebido para resolver o descontrole de gastos diários enfrentado por pessoas físicas. A solução permite centralizar em um só lugar as contas bancárias, cartões de crédito, receitas e despesas, eliminando a dependência de planilhas complexas ou anotações manuais. Com uma interface focada na agilidade de uso, o sistema oferece categorização simples de transações, criação de orçamentos por categoria com alertas preventivos de limite e painéis visuais sobre o fluxo de caixa. O aplicativo busca capacitar o usuário a tomar decisões financeiras mais conscientes e atingir suas metas de economia de forma descomplicada.

## 🎯 Problemas do Público Alvo
Qual é o problema identificado?
A falta de previsibilidade, acompanhamento diário e controle sobre as receitas e despesas pessoais.
Quem enfrenta esse problema?
Pessoas físicas, estudantes e jovens profissionais que tentam gerenciar seus orçamentos mensais individualmente.
Como esse problema é resolvido atualmente?
O problema é abordado por meio de anotações soltas, planilhas manuais complexas ou consultas pontuais diretamente nos aplicativos de múltiplos bancos.
Quais dificuldades existem no processo atual?
Esquecimento frequente do registro de pequenas despesas, atraso no pagamento de faturas/contas por falta de lembretes, falta de visão clara de gastos por categoria e falta de alertas antes do estouro do limite do orçamento.

## 🎯 A Solução
O FinFlow é uma aplicação mobile e web focada na gestão financeira pessoal. Ele centraliza o registro de receitas e despesas, permite a categorização automática ou manual de gastos, organiza limites de orçamento com alertas e possibilita a definição e acompanhamento de metas financeiras através de dashboards simples e intuitivos.
Objetivo geral do sistema: Proporcionar uma experiência fluida para que o usuário pessoa física consiga organizar suas finanças diárias em poucos segundos, garantindo previsibilidade de orçamento e apoio no alcance de metas de economia.
Público-alvo: Pessoas físicas que buscam simplicidade e agilidade para controlar suas finanças diárias.
Principais benefícios esperados: Redução de gastos impulsivos, prevenção do atraso de contas por falta de notificação, clareza sobre o destino do dinheiro e maior facilidade para criar reservas financeiras.

---
## ✨ Principais Funcionalidades

- 🔐 **Autenticação Segura:** Login por e-mail, redes sociais e biometria (FaceID/TouchID) com suporte a 2FA.
- 💳 **Gestão de Contas & Cartões:** Controlo centralizado de contas correntes, poupanças e cartões de crédito com cálculo automático de faturas.
- 💸 **Registo e Categorização:** Lançamento rápido de transações diárias, recorrentes ou parceladas.
- 📈 **Dashboards & Relatórios:** Gráficos interativos com visão de fluxo de caixa e distribuição de despesas por categoria.
- 🎯 **Orçamentos e Metas:** Definição de teto de gastos com notificações automáticas (ao atingir 80% e 100% do limite) e acompanhamento de metas de poupança.
- 🏦 **Importação & Open Finance:** Suporte para importação de extratos (OFX/CSV) e integração futura com instituições bancárias via Open Financeira.

---

## 🚀 Tecnologias Utilizadas

### **Front-end / Mobile**
- **Mobile:** React Native / Flutter
- **Web:** React.js / Next.js
- **UI Components:** Material Design / Human Interface Guidelines

### **Back-end & Infraestrutura**
- **API:** Node.js / Python (FastAPI/Django)
- **Base de Dados:** PostgreSQL / MongoDB
- **Autenticação:** JWT, OAuth2, Biometria
- **Infraestrutura Cloud:** AWS / Firebase

---

## 🔒 Segurança e Conformidade

O projeto foi construído respeitando rigorosos padrões de segurança de software e privacidade de dados:

- 🛡️ **LGPD:** Conformidade total com a Lei Geral de Proteção de Dados (exportação e eliminação de dados a pedido do utilizador).
- 🔑 **Criptografia:** TLS 1.3 para dados em trânsito e AES-256 para dados em repouso.
- 🔑 **Hash de Senhas:** Armazenamento seguro de credenciais utilizando algoritmos fortes (bcrypt/Argon2).

---

## 📋 Arquitetura de Requisitos (ERS)

| ID | Requisito | Tipo | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF001** | Autenticação e Gestão de Perfil | Funcional | Alta |
| **RF004** | Registo de Transações (Receita/Despesa) | Funcional | Alta |
| **RF011** | Dashboard Financeiro e Gráficos | Funcional | Alta |
| **RNF001** | Criptografia de Dados (TLS 1.3 / AES-256) | Não Funcional | Alta |
| **RNF003** | Tempo de Resposta < 2 segundos em 4G/5G | Não Funcional | Média |

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
