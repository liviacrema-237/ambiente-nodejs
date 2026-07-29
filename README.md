# ambiente-nodejs
# Node.js Capabilities & Features

> Um guia de referência rápida e documentação sobre o poder, arquitetura e principais capacidades do **Node.js**.

---

##  Visão Geral

O **Node.js** é um ambiente de execução JavaScript *open-source*, *cross-platform* e assíncrono, construído sobre o motor V8 do Google Chrome. Ele permite executar código JavaScript no lado do servidor com foco em alta performance e escalabilidade.

---

##  Principais Capacidades

### 1. I/O Assíncrono e Orientado a Eventos
* **Non-Blocking I/O:** Executa operações de entrada/saída (arquivos, banco de dados, rede) sem travar a thread principal.
* **Event Loop:** Gerencia operações assíncronas através de fases, permitindo lidar com milhares de conexões simultâneas de forma leve.

### 2. Ecossistema NPM (Node Package Manager)
* Acesso ao maior registro de bibliotecas de código aberto do mundo.
* Gestão simplificada de dependências, scripts e automatizações de build.

### 3. Sistemas de Arquivos e Streams (`fs` / `stream`)
* Manipulação nativa do sistema de arquivos local.
* **Streams:** Processamento de grandes volumes de dados em pedaços (*chunks*) sem sobrecarregar a memória RAM.

### 4. Suporte Completo a Módulos
* **CommonJS:** Padrão legado/tradicional (`require` / `module.exports`).
* **ES Modules (ESM):** Padrão moderno nativo (`import` / `export`).

### 5. Execução Paralela e Concorrência
* **Worker Threads:** Para tarefas pesadas focadas em CPU (cálculos matemáticos, processamento de imagem).
* **Child Processes (`child_process`):** Criação e controle de subprocessos do sistema operacional.
* **Cluster Module:** Multiplicação da aplicação em múltiplos processos para aproveitar todos os núcleos do processador.

### 6. Rede e Comunicação em Tempo Real
* Criação nativa de servidores **HTTP**, **HTTPS**, **HTTP/2** e **WebSockets**.
* Suporte nativo a protocolos TCP e UDP (`net` / `dgram`).

---

##  Arquitetura Resumida