# O Clamor do meio dia - Pedidos de Oração

## Descrição

Este é um projeto de um Aplicativo Web Progressivo (PWA) para gerenciar pedidos de oração, intitulado "O Clamor do meio dia". A aplicação é projetada para ser instalável em dispositivos móveis e desktops e funcionar offline.

## Funcionalidades

- **Progressive Web App (PWA):** A aplicação pode ser "instalada" na tela inicial do seu dispositivo e oferece uma experiência de aplicativo nativo.
- **Capacidade Offline:** Os principais recursos da aplicação estão disponíveis offline, graças ao uso de Service Workers que armazenam o shell do aplicativo em cache.
- **Single Page Application (SPA):** A interface é carregada uma única vez, e as interações subsequentes são tratadas dinamicamente no lado do cliente, proporcionando uma experiência de usuário rápida e fluida.

## Estrutura do Projeto

```
/
├── index.html               # Ponto de entrada HTML principal
├── manifest.webmanifest     # Manifesto do PWA
├── registerSW.js            # Script para registrar o Service Worker
├── sw.js                    # Service Worker para caching e funcionalidade offline
├── workbox-*.js             # Biblioteca Workbox para o Service Worker
├── assets/
│   ├── index-*.css          # Folha de estilos da aplicação
│   └── index-*.js           # Lógica principal da aplicação em JavaScript
└── icons/
    ├── icon-192x192.png     # Ícone do aplicativo
    └── icon-512x512.png     # Ícone do aplicativo em alta resolução
```

## Como Executar Localmente

Este projeto parece ser um build de produção de uma aplicação web. Para visualizá-lo, você pode usar um servidor web local simples.

1.  Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.
2.  Instale um servidor local, como o `http-server`, globalmente:
    ```sh
    npm install -g http-server
    ```
3.  Execute o servidor a partir do diretório raiz do projeto:
    ```sh
    http-server
    ```
4.  Abra o seu navegador e acesse o endereço fornecido (geralmente `http://localhost:8080`).

---
*Este README foi gerado automaticamente com base na análise da estrutura do projeto.*
