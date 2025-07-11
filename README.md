# 🚀 Challenger Swift ![Status](https://img.shields.io/badge/Status-Em%20Andamento-blue)

## 📑 Índice

- [📌 Descrição do Desafio](#-descrição-do-desafio)
- [🩺 Diagnóstico: Principais Pontos de Atrito na Jornada O2O](#-diagnóstico-principais-pontos-de-atrito-na-jornada-o2o)
  - [🛒 Checkout](#-checkout)
  - [🛍️ Falta de Cross-sell no Checkout](#-falta-de-cross-sell-no-checkout)
  - [🖥️ Layout Poluído em Partes do Site](#-layout-poluido-em-partes-do-site) 
  - [🌙 Ausência de Modo Escuro](#-ausência-de-modo-escuro)
- [✅ Soluções Propostas](#-soluções-propostas)
  - [🎯 Aumento da Conversão](#-aumento-da-conversão)
  - [💸 Aumento do Ticket Médio](#-aumento-do-ticket-médio)
  - [🚀 Viabilidade e Inovação](#-viabilidade-e-inovação)
- [📈 Impacto Esperado](#-impacto-esperado)
- [🎨 Prototipagem das telas](#-prototipagem-das-telas)
- [🗂️ Modelagem de dados](#️modelagem-de-dados)
- [👨‍💻 Pessoas Desenvolvedoras do Projeto](#-pessoas-desenvolvedoras-do-projeto)
- [🧑‍🏭 Minhas contribuições](#-minhas-contribuições)

---

## 📌 Descrição do Desafio

Atividade acadêmica (em grupo) do 1º ano de ADS da FIAP, em parceria com a JBS, cujo objetivo é melhorar a jornada de compra O2O (Online to Offline) do e-commerce da Swift, reduzindo fricções, aumentando a conversão e o ticket médio, além de propor inovações que fortaleçam a marca.


## 🩺 Diagnóstico: Principais Pontos de Atrito na Jornada O2O

### 🛒 Checkout
- 🔸 **Processo longo e segmentado**
  - Múltiplas etapas desnecessárias → Aumento da desistência  
  ![Barra de etapas](https://github.com/user-attachments/assets/d555f4f3-fe64-4a57-816b-cad0f7a86a27)

- 🔸 **Fluxo confuso**
  - **Etapa 1:** Mesmo escolhendo "Retirada na loja", o sistema pede **data de entrega**  
  ![Confusão entrega-retirada](https://github.com/user-attachments/assets/8fd9e645-6df6-4a7b-9d0f-de7a7ed172b7)
  - **Etapa 3:** Pergunta novamente sobre **Entrega ou Retirada**  
  ![Entrega-retirada-repeticao](https://github.com/user-attachments/assets/812b8861-7f85-40c3-a4e1-145f1c80118b)
  - **Etapa 4:** **Erro no pagamento** quando a opção é "Retirada na loja"  
  ![Erro-pagamento1](https://github.com/user-attachments/assets/df605544-686f-41a3-93c2-0b6406a47d94)  
  ![Erro-pagamento2](https://github.com/user-attachments/assets/07f12ba7-23d5-4bc2-b9af-60d97fa3bca9)

### 🛍️ Falta de Cross-sell no Checkout
- Nenhuma sugestão de **produtos complementares**.

### 🖥️ Layout Poluído em Partes do Site
- Excesso de informações, especialmente na **Homepage**.

### 🌙 Ausência de Modo Escuro
- Falta de conforto visual e acessibilidade para usuários sensíveis à luz.

---

## ✅ Soluções Propostas

### 🎯 Aumento da Conversão
- 🔹 **Otimização do Checkout**
  - Redução de etapas desnecessárias
  - Correção de inconsistências entre entrega/retirada e pagamento
  - Layout mais limpo e direto

- 🔹 **Diversificação de Pagamentos**
  - Inclusão de **carteiras digitais** (Apple Pay, Google Pay etc)

- 🔹 **Implementação de Modo Escuro**
  - Responsivo, moderno e acessível

- 🔹 **Reestruturação Visual**
  - Melhor usabilidade nas áreas críticas

---

### 💸 Aumento do Ticket Médio
- 🔹 **Cross-sell Inteligente**
  - Nova seção "**Sugestões do Chef**" no checkout

- 🔹 **Valorização de Categorias Estratégicas**
  - Destaque para **bebidas**, **refeições prontas** e **pratos rápidos**

- 🔹 **Gatilhos Emocionais**
  - Ofertas com senso de **urgência e escassez** no carrinho

---

### 🚀 Viabilidade e Inovação
- 🔹 **QR Codes nas Embalagens**
  - Direcionamento para **receitas**, **informações nutricionais** e **dicas de preparo** (texto e vídeo)

---

## 📈 Impacto Esperado

| ✅ Benefício | 🎯 Resultado |
|--|--|
| 🏃‍♂️ Experiência mais fluida | Menos abandono no checkout |
| 💳 Aumento da conversão | Menos fricções + recomendações |
| 💰 Maior ticket médio | Mais itens por compra |
| 💎 Fortalecimento da marca | Engajamento via QR Codes |
| 🧭 Navegação mais intuitiva | Melhor usabilidade |
| ✅ Mais confiança e conforto | Layout profissional e coerente |
| 🔁 Aumento da retenção | Usuários mais propensos a voltar |

---

## 🎨 Prototipagem das telas
![Login](https://github.com/user-attachments/assets/298d7fcd-18cf-47d2-99ab-624c300a5bd2)
![Cadastro PF](https://github.com/user-attachments/assets/d5459486-6963-43c3-9782-564494bb3ca2)
![Cadastro PJ](https://github.com/user-attachments/assets/e89f11de-39fb-41f5-9a84-00dafb4bc057)
![Home](https://github.com/user-attachments/assets/8a28dc96-bc19-4ddb-8b4d-65ffee185a15)
<div align=center> <img src="https://github.com/user-attachments/assets/098926b7-9ed1-4948-a621-7e557c27cd91" alt="Carrinho"> </div>

![Checkout](https://github.com/user-attachments/assets/e9b25097-9c53-47fc-9975-0625139802d9)

---

## 🗂️Modelagem de dados
<div align=center>
  <img src="https://github.com/user-attachments/assets/7f0efc68-cbb7-4395-90f5-ecbf58e09be4" alt"Swift-Logical">
  <img src="https://github.com/user-attachments/assets/35210511-c16c-4b6f-990a-8622e583e521" alt"Swift-Relational">  
</div>

---
## 👨‍💻 Pessoas Desenvolvedoras do Projeto

### 🐱‍💻 Com GitHub

<div>

| [<img src="https://github.com/user-attachments/assets/854d6190-615a-4d46-a288-ee246228164b" width="100" height="100" alt="Jefferson Gomes"/>](https://github.com/Jeffergs) | [<img src="https://github.com/user-attachments/assets/5c7d887a-4067-458a-8501-2901ed503514" width="100" height="100" alt="Luiz Eduardo"/>](https://github.com/luizeduardotsdev) |
|:---:|:---:|
| [![Jefferson Gomes](https://img.shields.io/badge/Jefferson_Gomes-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Jeffergs) | [![Luiz Eduardo](https://img.shields.io/badge/Luiz_Eduardo-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/luizeduardotsdev) |

</div>

### 🙋‍♂️ Sem GitHub

- Jean Carlos Martins
- Bruno Felipe Cavaeiro
- Adriano Isaias

---
## 🧑‍🏭 Minhas contribuições
Fiz a modelagem de dados, participei ativamente do planejamento das telas e contribuí na identificação dos principais pontos de atrito da jornada O2O, além de criar a documentação de soluções propostas.











