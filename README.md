# 📱 Gerador de QR Code Dinâmico com Integração de API

Este projeto é uma aplicação interativa que transforma qualquer texto ou URL em um código QR instantaneamente. Ele utiliza uma API externa para gerar a imagem e possui uma interface responsiva com estados dinâmicos controlados por JavaScript.

## 🚀 Tecnologias Utilizadas
* **HTML5:** Estrutura semântica e importação de fontes externas (Google Fonts - Roboto).
* **CSS3:** * **Transições:** Efeito de expansão suave do container via `transition`.
    * **Estados Dinâmicos:** Uso de classes auxiliares (`.active`) para controlar a visibilidade e o tamanho dos elementos.
    * **Layout Flexbox:** Centralização perfeita do conteúdo na tela.
* **JavaScript (ES6+):**
    * **Integração com API:** Consumo da API `qrserver.com` para geração de imagens.
    * **Eventos de Teclado:** Suporte para disparar a geração ao apertar a tecla "Enter".
    * **Tratamento de Imagem:** Uso do evento `load` para exibir o resultado apenas quando a imagem estiver totalmente carregada.

## 🧠 Lógica e UX Aplicada:
* **Feedback ao Usuário:** O botão altera o texto para "Gerando código..." enquanto a requisição é processada.
* **Limpeza Automática:** O sistema remove o QR Code da tela caso o campo de entrada seja apagado (evento `keyup`).
* **Design Limpo:** Interface intuitiva com foco total na funcionalidade de conversão.

## ⚙️ Como visualizar
1. Clone este repositório.
2. Abra o arquivo `index.html` no seu navegador.
3. Insira um link ou frase e clique em "Gerar QR Code".

---
Projeto desenvolvido para praticar consumo de APIs e manipulação de classes CSS via JavaScript no curso de ADS. 💻🔥
Com base no curso de Front-End completo do Matheus Battisti.
