# Formulário de Pedido de Receita (Survey Form)

Este projeto é um dos desafios de certificação da trilha **Responsive Web Design** do freeCodeCamp. O objetivo foi desenvolver um formulário de pesquisa funcional utilizando HTML5 semântico.

##  Objetivo

O formulário permite que usuários solicitem receitas para um menu futuro, coletando dados de contato, preferências de pratos e detalhes sobre o formato de conteúdo de vídeo preferido.

##  Tecnologias e Conceitos Utilizados

* **HTML5 Semântico:** Uso de tags estruturais para garantir acessibilidade e SEO.
* **Validação de Formulários:** Implementação de atributos nativos como `required`, `min`, `max` e tipos de input específicos (`email`, `number`).
* **Acessibilidade:** Uso correto de IDs e Labels para leitores de tela.

##  Estrutura Técnica (User Stories)

| Elemento | Descrição | Atributos Aplicados |
| :--- | :--- | :--- |
| **Inputs de Texto** | Nome e E-mail | `placeholder`, `required`, `type="email"` |
| **Input Numérico** | Idade ou Contato | `min="3"`, `max="100"` para controle de entrada |
| **Seleção Única** | Escolha do prato principal | Tag `<select>` com múltiplas `<option>` |
| **Botões de Rádio** | Tempo de duração do vídeo | `type="radio"` (permite apenas uma escolha) |
| **Caixas de Seleção** | Foco do conteúdo (Ingredientes/Dicas) | `type="checkbox"` (múltiplas escolhas) |
| **Área de Texto** | Sugestões adicionais | `<textarea>` para comentários longos |

## O que este projeto demonstra

1.  **Capacidade de seguir Requisitos:** O projeto cumpre todas as exigências técnicas de IDs e tipos de entrada solicitados pelo freeCodeCamp.
2.  **Organização de Dados:** Coleta de informações variadas (texto, números, escolhas únicas e múltiplas).
3.  **Atenção à Experiência do Usuário (UX):** Uso de `placeholders` que orientam o preenchimento correto dos campos.

---
*Este repositório foi feito com o intuito de praticar a lógica com html como parte dos meus estudos de desenvolvimento Web e Front-end.*
