# 📧 Serviço de Notificação

Este projeto é um **microserviço responsável pelo envio de notificações**, atuando como parte de um ecossistema baseado em **arquitetura de microserviços**.

Ele é acionado por outros serviços do sistema sempre que ocorre um evento relevante, como criação ou atualização de tarefas, garantindo **desacoplamento**, **escalabilidade** e **responsabilidade única**.

---

## 🧩 Papel no Ecossistema

Este serviço é responsável exclusivamente por:
- Envio de notificações por e-mail
- Processamento de eventos do sistema
- Comunicação assíncrona entre serviços

Ele é consumido por:
- 📅 Serviço de Agendamento de Tarefas
- 🧩 BFF (Backend for Frontend)

---

## 🚀 Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Spring Web
- Maven
- Docker
- API REST

---

## ⚙️ Funcionalidades

- Envio de notificações por e-mail
- Recebimento de eventos de outros serviços
- Tratamento básico de falhas

---

## ▶️ Como Executar o Projeto

### 🔹 Pré-requisitos
- Java 17+
- Maven
- Docker

---

### 🔹 Executando localmente

```bash
mvn clean spring-boot:run
