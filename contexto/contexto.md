# Contexto Geral do Projeto: F1 Paddock Store (Projeto Web)

> **AVISO OBRIGATÓRIO PARA O AGENTE**:  
> Este documento deve ser lido e atualizado **sempre** antes de iniciar e logo após concluir cada nova parte do projeto.

---

## 1. Visão Geral
- **Nome do Projeto**: F1 Paddock Store — E-commerce & Portal de Fórmula 1.
- **Tema**: Automobilismo / Fórmula 1 (produtos oficiais, miniaturas, simuladores, vestuário de escuderias, ingressos, etc.).
- **Objetivo**: Construir uma aplicação web completa de forma evolutiva e modular, consolidando conceitos fundamentais de desenvolvimento web.

---

## 2. Stack Tecnológica
- **Front-end**:
  - HTML5 Puro com semântica completa e formulários avançados (GET e POST)
  - CSS3 Puro centralizado externamente em `css/estilo.css` (sem frameworks, sem inline styles e sem `<style>`)
  - JavaScript Puro (Vanilla JS para próximas etapas de dinamismo)
- **Back-end**:
  - PHP Puro (estruturado / modular para processamento de regras, checkout e dados)
- **Controle de Versão**:
  - Git local com commits padronizados.

---

## 3. Padrão de Commits Git
Todas as entregas e etapas devem seguir estritamente o padrão solicitado:
```text
Commit Projeto Web parte: X
```
*(ou `Commit Projeto Web parte: X.X.X` caso seja uma sub-etapa ou correção pontual)*.

---

## 4. Estrutura de Diretórios
```text
projeto Web/
├── contexto/
│   └── contexto.md          # Arquivo de diretrizes, regras e sugestões
├── assets/                  # Imagens, ícones e mídias
├── css/
│   └── estilo.css           # Folha de estilo externa com Reset, Box Model, Menu, Cards, Tabela Zebra e Forms
├── js/                      # Scripts funcionais (Vanilla JS para próximas etapas)
├── php/                     # Lógica de backend e templates modulares
├── index.html               # Página principal completa com design CSS3 externo
└── processa-pedido.html     # Página de confirmação pós-checkout POST com CSS3
```

---

## 5. Histórico e Status das Partes
| Parte | Descrição | Status | Commit |
| :---: | :--- | :---: | :---: |
| **0** | Inicialização do repositório, estrutura de pastas e arquivo de contexto | ✅ Concluído | `Commit Projeto Web parte: 0` |
| **1** | **Versão 1.0**: Estrutura base em HTML puro com as 5 seções obrigatórias (`<div>`, `<h1>`-`<h6>`, `<p>`, `<img>`, `<a>`, `<b>`, `<i>`, `<span>`, `<strong>`, `<em>`, `<br>`, `<hr>`) | ✅ Concluído | `Commit Projeto Web parte: 1` |
| **2** | **Versão 2.0**: Refatoração semântica HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`), listas (`<ul>`, `<ol>`), vídeo com `<video controls>` + múltiplos `<source>` e fallback, e tabela comparativa estruturada (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`) | ✅ Concluído | `Commit Projeto Web parte: 2` |
| **3** | **Versão 3.0**: Formulários de Coleta de Dados com métodos GET (busca e filtro no header) e POST (checkout estruturado com `<fieldset>`, `<legend>`, text, email, password, date, number, radio, select, checkbox, textarea e botões submit/reset) | ✅ Concluído | `Commit Projeto Web parte: 3` |
| **4** | **Versão 4.0**: Estilização Externa e Design de Layout com CSS3 (`css/estilo.css`, reset global, box model, tipografia, menu de navegação com `:hover`, cards com sombras e cantos arredondados, multimídia fluida responsiva, tabela comparativa com zebra striping, formulários com estados `:focus` e botões com transição) | ✅ Concluído | `Commit Projeto Web parte: 4` |
| **5** | **Versão 5.0**: Layout Responsivo com CSS Flexbox / Grid ou Interatividade Dinâmica em JavaScript | ⏳ Próxima | `Commit Projeto Web parte: 5` |

---

## 6. Sugestões e Ideias para Criação (Roadmap e F1 Experience)
Aqui estão sugestões de recursos imersivos e temáticos para as próximas etapas:

1. **Layout Grid & Flexbox Avançado (Parte 5)**:
   - Disposição lado a lado do `<aside>` com a vitrine principal `<main>` usando CSS Grid de 2 colunas no desktop.
   - Vitrine de produtos em grade responsiva com `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))`.
   - Menu hambúrguer ou barra de telemetria expansível para telas móveis.
2. **Dinamismo em JavaScript Puro (Parte 6)**:
   - Adição e remoção dinâmica de itens no carrinho com atualização de contadores em tempo real.
   - Cálculo automático do total com base no tipo de frete selecionado (Grid padrão grátis vs. Pit Stop Expresso R$ 45).
   - Validação imediata de campos de senha e confirmação de e-mail.
3. **Backend PHP (Parte 7)**:
   - Conversão do checkout para processar os dados enviados via POST com PHP, salvando pedidos em banco SQLite ou arquivo JSON estruturado.
