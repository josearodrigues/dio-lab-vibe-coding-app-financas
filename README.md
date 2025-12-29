# App de Organização de Finanças Pessoais com Vibe Coding

Este projeto foi desenvolvido no **Lovable** utilizando a abordagem de **Vibe Coding**, com base em um PRD (Product Requirements Document) que define claramente o problema, público-alvo e funcionalidades principais.  
O objetivo é oferecer uma experiência de controle financeiro simples, acessível e inclusiva, baseada em conversas em linguagem natural.

---

## PRD Final (refinado no Copilot Web)

```markdown
# PRD – Aplicativo de Organização de Finanças Pessoais

## 1. Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de interações em linguagem natural.  
Em vez de formulários complexos ou planilhas, o usuário conversa com o app como se fosse um “assistente financeiro”, tornando o processo mais intuitivo e acessível.

## 2. Problema
- Apps tradicionais exigem entradas manuais extensas e pouco personalizadas.  
- Isso gera frustração e abandono do hábito de registrar gastos.  
- Falta de recomendações práticas e adaptadas ao perfil do usuário.  

Solução proposta: criar uma experiência conversacional que registre gastos automaticamente, sugira economias e acompanhe metas de forma amigável, seguindo os princípios de Design Universal para garantir acessibilidade e boa experiência para o maior número possível de usuários.

## 3. Público-Alvo
- Pessoas iniciantes no controle financeiro.  
- Usuários que buscam praticidade e simplicidade.  
- Pessoas que se sentem sobrecarregadas com planilhas ou apps tradicionais.  
- Usuários diversos em idade, nível de letramento digital e necessidades de acessibilidade.

## 4. Funcionalidades-Chave
1. Registro de gastos via chat: o usuário descreve em linguagem natural (“gastei R$50 no mercado”) e o app interpreta.  
2. Classificação automática: categorização inteligente das transações (alimentação, transporte, lazer etc.).  
3. Metas financeiras: definição e acompanhamento de objetivos (ex.: economizar R$200/mês).  
4. Agente Financeiro: dicas personalizadas de economia e insights sobre hábitos de consumo.  
5. Relatórios simples: visualizações claras e personalizadas (gráficos, resumos semanais/mensais).  
6. Design Universal: interface inclusiva, com linguagem acessível, suporte a diferentes formatos de interação (texto, voz), contraste adequado e navegação intuitiva.

## 5. Entregável da IA (MVP)
- Principais telas:
  - Tela de chat (interação principal).  
  - Tela de metas (definição e progresso).  
  - Tela de relatórios (gráficos e insights).  
- Recursos necessários:
  - Processamento de linguagem natural (NLP).  
  - Motor de categorização de transações.  
  - Sistema de notificações e dicas.  
  - Banco de dados seguro para armazenar transações.  
  - Diretrizes de acessibilidade e Design Universal aplicadas desde o início.  
- Validação inicial:
  - Testes com grupo piloto de usuários iniciantes e diversos perfis.  
  - Coleta de feedback sobre clareza das conversas, acessibilidade e utilidade das recomendações.  
  - Ajustes rápidos no fluxo de chat e relatórios.
```

---
## Interações no Lovable

> Crie um app de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): [PRD]

> Integre a API OpenAI para que o assistente entenda melhor linguagem natural, categorizando gastos de forma mais inteligente e gerando dicas personalizadas com IA.

> Adicione persistência de dados com banco de dados para salvar transações e histórico de conversas do usuário.

> Adicione a funcionalidade de atualizar o valor atual das metas, permitindo registrar depósitos e acompanhar o progresso.

> Por favor, poderia verificar o por quê de não conseguir digitar ou falar nada no assistente financeiro?

> Parece que não é visualizada a caixa de entrada do chat. Verifique novamente...

> No chat, pedi para depositar em minha meta de reserva de emergência e ele somente computou como um investimento no mês, mexendo no cálculo de entradas e saídas mas não na meta. Poderia corrigir?

---

## Link para o App
[Converse Cash Flow no Lovable](https://converse-cash-flow.lovable.app/)

---

## Demonstração (Imagens do App)

<p align="center">
  <img src="https://github.com/user-attachments/assets/21a65ea3-4e7a-418c-ab0a-ee2e3a5acafa" width="300" />
  <img src="https://github.com/user-attachments/assets/89b273bd-f5bc-4787-b598-b0504c59834e" width="800" />
  <img src="https://github.com/user-attachments/assets/4743ea20-6a00-45a6-ae24-43580db3030a" width="800" />
  <img src="https://github.com/user-attachments/assets/949d9830-e0b0-4c1e-87cc-54c60c8b3d49" width="800" />
</p>

---

## Funcionalidades

- **Chat Financeiro Inteligente**  
  Registro de gastos e entradas por meio de conversas em linguagem natural.  
  Exemplo: "Gastei R$50 no mercado" → o app interpreta e registra automaticamente.

- **Classificação Automática de Transações**  
  As despesas e receitas são categorizadas de forma inteligente (alimentação, transporte, lazer, investimentos etc.), sem necessidade de configuração manual.

- **Gestão de Metas Financeiras**  
  Criação de metas personalizadas (ex.: reserva de emergência, viagem, quitar dívidas).  
  O usuário pode registrar depósitos e acompanhar o progresso em tempo real.

- **Assistente Financeiro com IA**  
  Recomendações de economia e insights sobre hábitos de consumo, adaptados ao perfil do usuário.  
  Exemplo: alertas sobre gastos recorrentes ou dicas para atingir metas mais rápido.

- **Relatórios Visuais e Personalizados**  
  Gráficos e resumos semanais/mensais que mostram entradas, saídas, saldo e evolução das metas.  
  Interface clara e acessível, com foco em iniciantes.

- **Design Universal e Acessibilidade**  
  Interface inclusiva, com suporte a diferentes formatos de interação (texto e voz), contraste adequado e navegação intuitiva.  
  Pensado para oferecer boa experiência ao maior número possível de usuários.

---

## Reflexão

- **O que funcionou bem?**  
  O PRD refinado com o Copilot acelerou a criação da aplicação, mesmo com poucos créditos no Lovable.

- **O que não funcionou como esperado?**  
  A limitação de interações reduziu a experimentação, mas ainda assim trouxe aprendizado importante sobre Vibe Coding.

- **O que aprendi sobre conversar com IAs?**  
  Sem o prompt ideal, a conversa não flui como esperado. É como conversar com alguém que ainda não conhece você. A clareza e técnica no pedido são essenciais para obter bons resultados.
