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
  - HTML5 Puro (sem frameworks / semântica rigorosa)
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

## 4. Estrutura de Diretórios Inicial
```text
projeto Web/
├── contexto/
│   └── contexto.md       # Arquivo de diretrizes, regras e sugestões
├── assets/               # Imagens, ícones e mídias
├── css/                  # Folhas de estilo (CSS puro)
├── js/                   # Scripts funcionais (Vanilla JS)
├── php/                  # Lógica de backend e templates modulares
└── index.html (ou .php)  # Ponto de entrada
```

---

## 5. Histórico e Status das Partes
| Parte | Descrição | Status | Commit |
| :---: | :--- | :---: | :---: |
| **0** | Inicialização do repositório, estrutura de pastas e arquivo de contexto | ✅ Concluído | `Commit Projeto Web parte: 0` |
| **1** | Aguardando envio da proposta pelo usuário... | ⏳ Pendente | — |

---

## 6. Sugestões e Ideias para Criação (Brainstorming F1)
Aqui estão sugestões de recursos imersivos e temáticos que podemos incorporar conforme as etapas forem avançando:

1. **Grid de Produtos por Escuderia**:
   - Filtros visuais por equipes do grid atual (Ferrari, McLaren, Red Bull, Mercedes, Aston Martin, etc.).
2. **Telemetry & Pit Stop Experience**:
   - Área do carrinho estilizada como uma "Parada no Box" (Pit Stop), onde o checkout é o tempo de liberação da compra.
3. **Seção de Pilotos & Réplicas de Colecionador**:
   - Páginas/cards com especificações técnicas reais dos carros (motorização V6 Turbo Híbrido, pneus Pirelli, asa móvel DRS).
4. **Calculadora de Frete com Pistas do Calendário**:
   - Simulação de entrega "Express Paddock" com temática de Grande Prêmio (ex: entrega expressa no circuito de Interlagos).
5. **Backend PHP para Gestão de Estoque e Pedidos**:
   - Simulação de estoque por escuderia, validação de cupons (ex: `POLEPOSITION10`, `FASTESTLAP`) e persistência simples de pedidos.
