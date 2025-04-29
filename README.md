# 🧪 Exemplo de Cliente STOMP sobre WebSocket com HTML e JavaScript

Este repositório contém uma página HTML simples com JavaScript puro utilizando a biblioteca `stomp.js`, projetada para se conectar a brokers STOMP via WebSocket, como **RabbitMQ**, **ActiveMQ**, entre outros.

Ideal para **testes rápidos**, **debug de mensagens** e **aprendizado de integração WebSocket/STOMP** sem frameworks ou ferramentas complexas.

---

## 🚀 Recursos

- Conexão WebSocket com STOMP sem SockJS
- Código simples e direto, ideal para testes locais
- Pronto para usar com servidores como RabbitMQ e ActiveMQ
- Totalmente compatível com navegadores modernos

---

## 📚 Documentação e Links Úteis

### 📘 Protocolo STOMP
- [Documentação oficial do STOMP](https://jmesnil.net/stomp-websocket/doc)

### 📗 Biblioteca `stomp.js`
- [Guia de uso do `stomp.js`](https://stomp-js.github.io/stomp-websocket/codo/extra/docs-src/Usage.md.html#toc_0)

---

## ⚠️ Evite SockJS (exceto se necessário)

Apesar de comum em tutoriais antigos, **SockJS geralmente é desnecessário** em aplicações modernas, principalmente com **Spring Boot** ou ambientes controlados. Todos os principais navegadores atuais já suportam **WebSocket nativamente**.

Use SockJS apenas se precisar de fallback para navegadores antigos ou redes restritivas.

---

## 🛠️ Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/stomp-websocket-html-client.git