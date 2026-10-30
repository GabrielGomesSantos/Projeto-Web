# Contexto Geral do Projeto: F1 Paddock Store (Projeto Web)

> **AVISO OBRIGATÓRIO PARA O AGENTE**:  
> Este documento deve ser lido e atualizado **sempre** antes de iniciar e logo após concluir cada nova parte do projeto.

---

## 1. Visão Geral
- **Nome do Projeto**: F1 Paddock Store — E-commerce & Portal Oficial de Fórmula 1.
- **Tema**: Automobilismo / Fórmula 1 (produtos oficiais, simuladores profissionais, miniaturas colecionáveis diecast, escuderias do grid mundial e métricas reais de telemetria dos pilotos).
- **Objetivo**: Construir uma aplicação web completa de forma evolutiva e modular, consolidando conceitos fundamentais de desenvolvimento web com visual de alto nível.

---

## 2. Stack Tecnológica
- **Front-end**:
  - HTML5 Puro com semântica completa e formulários avançados (GET e POST)
  - CSS3 Puro centralizado externamente em `css/estilo.css` (sem frameworks, sem inline styles e sem `<style>`)
  - JavaScript Puro (Vanilla JS para próximas etapas)
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
*(ou `Commit Projeto Web parte: X.X.X` caso seja uma sub-etapa ou refinamento visual/técnico)*.

---

## 4. Estrutura de Diretórios
```text
projeto Web/
├── contexto/
│   └── contexto.md          # Arquivo de diretrizes, regras e sugestões
├── assets/                  # Imagens, ícones e mídias locais
├── css/
│   └── estilo.css           # Estilização completa CSS3 com tema motorsport F1
├── js/                      # Scripts funcionais (Vanilla JS para próximas etapas)
├── php/                     # Lógica de backend e templates modulares
├── index.html               # Portal e e-commerce completo com vitrine, equipes, pilotos e checkout
└── processa-pedido.html     # Página de confirmação pós-checkout POST estilizada
```

---

## 5. Histórico e Status das Partes
| Parte | Descrição | Status | Commit |
| :---: | :--- | :---: | :---: |
| **0** | Inicialização do repositório, estrutura de pastas e arquivo de contexto | ✅ Concluído | `Commit Projeto Web parte: 0` |
| **1** | **Versão 1.0**: Estrutura base em HTML puro com as 5 seções obrigatórias (`<div>`, `<h1>`-`<h6>`, `<p>`, `<img>`, `<a>`, `<b>`, `<i>`, `<span>`, `<strong>`, `<em>`, `<br>`, `<hr>`) | ✅ Concluído | `Commit Projeto Web parte: 1` |
| **2** | **Versão 2.0**: Refatoração semântica HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`), listas (`<ul>`, `<ol>`), vídeo com `<video controls>` + múltiplos `<source>` e fallback, e tabela comparativa estruturada (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`) | ✅ Concluído | `Commit Projeto Web parte: 2` |
| **3** | **Versão 3.0**: Formulários de Coleta de Dados com métodos GET (busca e filtro no header) e POST (checkout estruturado com `<fieldset>`, `<legend>`, text, email, password, date, number, radio, select, checkbox, textarea e botões submit/reset) | ✅ Concluído | `Commit Projeto Web parte: 3` |
| **4** | **Versão 4.0**: Estilização Externa e Design de Layout com CSS3 (`css/estilo.css`, reset global, box model, tipografia, nav com hover, cards, tabela zebra e forms) | ✅ Concluído | `Commit Projeto Web parte: 4` |
| **4.1.0** | **Refinamento Visual & Expansão Temática F1**: Logotipo oficial F1 em SVG, fotos reais dos carros e garagens, seção de Escuderias Oficiais do Grid (Ferrari, Red Bull, McLaren, Mercedes) e Seção de Métricas & Telemetria dos Pilotos (Max Verstappen, Lewis Hamilton, Lando Norris) | ✅ Concluído | `Commit Projeto Web parte: 4.1.0` |
| **5** | **Versão 5.0**: Layout Responsivo com CSS Flexbox / Grid ou Interatividade Dinâmica em JavaScript | ⏳ Próxima | `Commit Projeto Web parte: 5` |

---

## 6. Sugestões e Ideias para Criação (Roadmap e F1 Experience)
1. **Interatividade com JavaScript (Pit Stop Simulator)**:
   - Contador de tempo de box ("Pit Stop") durante o checkout.
   - Cálculo automático do valor com desconto ao selecionar "Pix" ou somando o frete "Expresso".
   - Filtro interativo na vitrine ao digitar no campo de busca ou selecionar a categoria sem recarregar a página.
2. **Área do Fã / Credenciamento Paddock Pass**:
   - Modal com crachá interativo personalizado com foto do fã e escuderia do coração.
3. **Backend PHP Modular**:
   - Modularização dos blocos comuns (`header.php`, `footer.php`, `nav.php`) com `include`/`require`.
   - Processamento seguro dos dados do pedido no backend com gravação em JSON/SQLite.
