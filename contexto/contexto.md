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
  - HTML5 Puro com semântica completa, formulários avançados (GET e POST)
  - CSS3 Puro (será introduzido na Versão 4.0 em arquivo externo sem estilos inline)
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
│   └── contexto.md          # Arquivo de diretrizes, regras e sugestões
├── assets/                  # Imagens, ícones e mídias
├── css/                     # Folhas de estilo (css/estilo.css na parte 4)
├── js/                      # Scripts funcionais (Vanilla JS)
├── php/                     # Lógica de backend e templates modulares
├── index.html               # Ponto de entrada atualizado (HTML5 Semântico + Formulários GET/POST)
└── processa-pedido.html     # Destino de feedback para o envio POST
```

---

## 5. Histórico e Status das Partes
| Parte | Descrição | Status | Commit |
| :---: | :--- | :---: | :---: |
| **0** | Inicialização do repositório, estrutura de pastas e arquivo de contexto | ✅ Concluído | `Commit Projeto Web parte: 0` |
| **1** | **Versão 1.0**: Estrutura base em HTML puro com as 5 seções obrigatórias (`<div>`, `<h1>`-`<h6>`, `<p>`, `<img>`, `<a>`, `<b>`, `<i>`, `<span>`, `<strong>`, `<em>`, `<br>`, `<hr>`) | ✅ Concluído | `Commit Projeto Web parte: 1` |
| **2** | **Versão 2.0**: Refatoração semântica HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`), listas (`<ul>`, `<ol>`), vídeo com `<video controls>` + múltiplos `<source>` e fallback, e tabela comparativa estruturada (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`) | ✅ Concluído | `Commit Projeto Web parte: 2` |
| **3** | **Versão 3.0**: Formulários de Coleta de Dados com métodos GET (busca e filtro no header) e POST (checkout estruturado com `<fieldset>`, `<legend>`, text, email, password, date, number, radio, select, checkbox, textarea e botões submit/reset) | ✅ Concluído | `Commit Projeto Web parte: 3` |
| **4** | **Versão 4.0**: Estilização Externa e Design de Layout com CSS3 (`css/estilo.css`, reset global, tipografia, nav, cards, tabela zebra, formulários e botões com hover) | ⏳ Em execução | `Commit Projeto Web parte: 4` |

---

## 6. Sugestões e Ideias para Criação (Roadmap e F1 Experience)
Aqui estão sugestões de recursos imersivos e temáticos:

1. **Design System de Fórmula 1 (Parte 4 - CSS3 Puro)**:
   - Esquema cromático:
     - Vermelho F1: `#e10600`
     - Fundo Paddock Dark: `#15151e`
     - Asfalto Neutro: `#22242f`
     - Texto e Contraste: `#f7f7f7` e `#d0d0d2`
     - Destaque Ouro/Pódio: `#f5a623`
   - Cards de produtos elevados com sombras de profundidade (`box-shadow: 0 4px 15px rgba(0,0,0,0.1)`).
   - Tabela comparativa limpa, com linhas alternadas e destaque no cabeçalho.
   - Formulário com campos destacados ao foco (`input:focus`) com contorno vermelho racing.
2. **Layout Responsivo (Grid & Flexbox)**:
   - Grade adaptável e fluida para vitrine e barra lateral.
3. **Validações e Interatividade (Vanilla JS & PHP)**:
   - Validação dinâmica dos campos de formulário e carrinho em tempo real.
