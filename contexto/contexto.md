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
  - HTML5 Puro (sem frameworks / semântica rigorosa a partir da v2.0)
  - CSS3 Puro (sem Tailwind, Bootstrap ou pré-processadores)
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
├── css/                  # Folhas de estilo (CSS puro)
├── js/                   # Scripts funcionais (Vanilla JS)
├── php/                  # Lógica de backend e templates modulares
└── index.html            # Ponto de entrada atual (HTML base v1.0)
```

---

## 5. Histórico e Status das Partes
| Parte | Descrição | Status | Commit |
| :---: | :--- | :---: | :---: |
| **0** | Inicialização do repositório, estrutura de pastas e arquivo de contexto | ✅ Concluído | `Commit Projeto Web parte: 0` |
| **1** | **Versão 1.0**: Estrutura base em HTML puro com as 5 seções obrigatórias (`<div>`, `<h1>`-`<h6>`, `<p>`, `<img>`, `<a>`, `<b>`, `<i>`, `<span>`, `<strong>`, `<em>`, `<br>`, `<hr>`) | ✅ Concluído | `Commit Projeto Web parte: 1` |
| **2** | **Versão 2.0**: HTML5 Semântico (`<header>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`) e Tabelas/Listas de dados | ⏳ Próxima | `Commit Projeto Web parte: 2` |

---

## 6. Sugestões e Ideias para Criação (Roadmap e F1 Experience)
Aqui estão sugestões de recursos imersivos e temáticos para as próximas etapas:

1. **Evolução Semântica (Parte 2 - HTML5 Semântico)**:
   - Substituição de `<div>` de topo por `<header>` e do rodapé por `<footer>`.
   - Organização da vitrine em `<main>` contendo `<section>` com `<article>` para cada produto.
   - Utilização de `<table>` estilizada para comparação de telemetria/especificações técnicas dos volantes e miniaturas.
   - Utilização de `<ul>` e `<ol>` para itens da caixa e passos do checkout/pit stop.
2. **Estilização e Identidade Visual (Parte 3 - CSS Puro)**:
   - Paleta de cores inspirada no asfalto, vermelho de alta rotação (`#e10600`), preto carbono e detalhes em amarelo pit-lane.
   - Cards com efeito de elevação e bordas que lembram fibra de carbono.
3. **Grid Responsivo (Parte 4 - Flexbox & Grid)**:
   - Grade de produtos adaptável com cards idênticos a grandes portais de e-commerce.
4. **Formulários e Checkout (Parte 5 - Forms)**:
   - Formulário de credenciamento "Paddock Pass" (cadastro de cliente) e tela de pagamento com bandeira quadriculada.
5. **Dinamismo e Interatividade (Parte 6 - JavaScript & PHP)**:
   - Carrinho dinâmico ("Pit Stop"), cálculo instantâneo com frete por circuito e backend PHP para processar os pedidos.
