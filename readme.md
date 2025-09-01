# 📝 Atividade Prática 01 
## Painel em Tempo Real com Socket.IO

## 🎯 Objetivo

Desenvolver um **painel em tempo real (dashboard)** que mostre informações sobre os usuários conectados e as rooms ativas, aplicando conceitos de **comunicação em tempo real** com **Socket.IO**.

---

## 🚀 Descrição da Atividade

Vocês vão criar uma aplicação web (servidor + cliente) que exiba em tempo real:

1. **Número total de usuários conectados.**
2. **Qual room tem mais usuários ativos.**
3. **Atualização automática a cada 1 segundo.**

O servidor será responsável por monitorar as conexões e as rooms, e o cliente exibirá os dados em uma interface simples (HTML/CSS/JS).

---

## 📦 Requisitos Técnicos

* Usar **Node.js + Express + Socket.IO** no backend.
* Usar **HTML/CSS/JS** simples no frontend.
* O servidor deve emitir os dados atualizados a cada **1 segundo**.
* O cliente deve atualizar os valores na tela em tempo real.

---

## 🧩 Etapas do Exercício

### 1. Conexão e Contagem de Usuários

* Modifiquem o servidor para **contar quantos usuários estão conectados**.
* Emitam esse número para todos os clientes.

### 2. Rooms e Popularidade

* Criem rooms e permitam que os clientes entrem nelas.
* O servidor deve calcular **qual room possui mais usuários**.
* Emitam essa informação junto com a contagem total.

### 3. Atualização Dinâmica

* Configurem o servidor para enviar essas informações a cada **1 segundo** usando `setInterval()`.
* O cliente deve **atualizar automaticamente** a tela com os novos dados.

---

## ✅ Entregáveis

* Link do seu repositório no Github contendo os seguintes artefatos:

1. **Servidor (Node.js + Socket.IO)** que:

   * Conta os usuários conectados.
   * Identifica a room mais popular.
   * Emite os dados a cada 1 segundo.

2. **Cliente (HTML/JS)** que exibe em tempo real:

   * Quantos usuários estão online.
   * Qual room está mais populosa.
   * Dados sendo atualizados sem precisar recarregar a página.

---

## 🌟 Extra (para quem quiser ir além)

* Mostrar um **ranking das rooms** (da mais cheia para a menos cheia).
* Exibir um **gráfico em tempo real** (pode usar Chart.js).
* Criar um **alerta visual** quando a quantidade de usuários em uma room ultrapassar um limite (ex: mais de 5 usuários).
