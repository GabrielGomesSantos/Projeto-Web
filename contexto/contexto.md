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
  - HTML5 Puro com semântica completa (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<video>`, `<table>`, listas)
  - CSS3 Puro (sem Tailwind, Bootstrap ou pré-processadores a ser introduzido na v3.0)
  - JavaScript Puro (Vanilla JS, sem bibliotecas externas)
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
│   └── contexto.md       # Arquivo de diretrizes, regras e sugestões
├── assets/               # Imagens, ícones e mídias
├── css/                  # Folhas de estilo (CSS puro - próximo passo)
├── js/                   # Scripts funcionais (Vanilla JS)
├── php/                  # Lógica de backend e templates modulares
└── index.html            # Ponto de entrada atualizado (HTML5 Semântico v2.0)
```

---

## 5. Histórico e Status das Partes
| Parte | Descrição | Status | Commit |
| :---: | :--- | :---: | :---: |
| **0** | Inicialização do repositório, estrutura de pastas e arquivo de contexto | ✅ Concluído | `Commit Projeto Web parte: 0` |
| **1** | **Versão 1.0**: Estrutura base em HTML puro com as 5 seções obrigatórias (`<div>`, `<h1>`-`<h6>`, `<p>`, `<img>`, `<a>`, `<b>`, `<i>`, `<span>`, `<strong>`, `<em>`, `<br>`, `<hr>`) | ✅ Concluído | `Commit Projeto Web parte: 1` |
| **2** | **Versão 2.0**: Refatoração semântica HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`), listas (`<ul>`, `<ol>`), vídeo com `<video controls>` + múltiplos `<source>` e fallback, e tabela comparativa estruturada (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`) | ✅ Concluído | `Commit Projeto Web parte: 2` |
| **3** | **Versão 3.0**: Estilização com CSS Puro (Cores, Tipografia, Espaçamento, Reset CSS e Formatação dos Cards de Produtos) | ⏳ Próxima | `Commit Projeto Web parte: 3` |

---

## 6. Sugestões e Ideias para Criação (Roadmap e F1 Experience)
Aqui estão sugestões de recursos imersivos e temáticos para as próximas etapas:

1. **Estilização Visual com CSS Puro (Parte 3 - Próxima)**:
   - Reset CSS padronizado (`box-sizing: border-box`, `margin: 0`, `padding: 0`).
   - Variáveis CSS nativas (`:root`) para temas de F1:
     - `--f1-red: #e10600;` (Vermelho oficial F1)
     - `--f1-dark: #15151e;` (Preto asfalto paddock)
     - `--f1-light: #f3f3f3;` (Cinza claro para fundos de contraste)
     - `--f1-accent: #ff1801;`
   - Formatação em cartões com sombras suaves (`box-shadow`), bordas arredondadas e badges estilizados de "Em Promoção" ou "Frete Grátis".
   - Estilização completa da tabela comparativa com linhas zebradas (`nth-child(even)`), cabeçalho contrastante e cantos arredondados.
2. **Grid Responsivo e Layout (Parte 4 - Flexbox & Grid)**:
   - Layout fluido com barra lateral (`<aside>`) ao lado da vitrine principal em telas grandes.
   - Grid de produtos adaptativo para smartphones, tablets e desktop.
3. **Formulários e Checkout (Parte 5 - Forms)**:
   - Formulário de credenciamento "Paddock Pass" com campos organizados por `<fieldset>` e `<legend>`.
4. **Dinamismo e Interatividade (Parte 6 - JavaScript & PHP)**:
   - Carrinho interativo, cálculo de frete por CEP/Região e integração com PHP.
