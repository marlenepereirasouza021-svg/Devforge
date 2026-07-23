 # DevForge 🛠️

> Um canivete suíço minimalista, rápido e moderno para desenvolvedores, focado em manipulação de dados, codificação e utilidades do dia a dia.

![Versão](https://img.shields.io/badge/vers%C3%A3o-3.0%20Pro-blue)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-green)
![Status](https://img.shields.io/badge/status-ativo-success)

## 🚀 Sobre o Projeto

O **DevForge** nasceu da necessidade de ter uma ferramenta leve, bonita e sem distrações para tarefas comuns de desenvolvimento. Desenvolvido puramente com tecnologias web modernas (HTML5, CSS3 e Vanilla JavaScript), ele roda direto no navegador de forma totalmente estática, garantindo máxima velocidade e privacidade (nenhum dado sai da sua máquina).

---

## ✨ Funcionalidades

### 📋 Formatadores e Inspetores
*   **Formatação de JSON**: Valida e formata estruturas JSON com identação limpa.
*   **Inspetor JWT**: Decodifica e separa o cabeçalho (*Header*) e o payload (*Payload*) de tokens JSON Web Tokens instantaneamente.

### 🔐 Codificação
*   **Base64**: Codifica e decodifica textos ou dados com suporte a caracteres especiais (UTF-8).
*   **URL Encoder/Decoder**: Trata URLs e parâmetros de forma segura.

### ⚙️ Geradores
*   **Gerador de Senhas**: Cria senhas fortes e aleatórias de 16 caracteres.
*   **Gerador de UUID v4**: Gera identificadores únicos universais compatíveis com a especificação.
*   **Timestamp Atual / Conversor**: Obtém o timestamp atual em segundos ou converte timestamps de volta para datas legíveis (UTC e Hora Local).

### 🛡️ Hashes (Criptografia)
*   **SHA-256 / SHA-512**: Calcula hashes criptográficos seguros utilizando a API nativa do navegador (`crypto.subtle`).

---

## 💻 Tecnologias Utilizadas

*   **HTML5** (Estrutura semântica)
*   **CSS3** (Variáveis CSS, Flexbox, Grid Layout, Design responsivo e tema escuro inspirado em IDEs)
*   **JavaScript (ES6+)** (Lógica nativa, manipulação de DOM e APIs modernas de criptografia/Clipboard)

---

## 📂 Estrutura de Arquivos

```text
dev-forge/
├── index.html    # Interface gráfica e estilos
├── script.js     # Lógica das ferramentas e utilitários
└── README.md     # Documentação do projeto
