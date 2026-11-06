# Proposal: setup-mvp-core

## Intent
Construir a primeira versão funcional e demonstrável do MVP da **YieldBet** utilizando dados mockados no VS Code, validada pelo OpenSpec. O objetivo é apresentar a proposta de valor central: uma fintech de reabilitação financeira gamificada que canaliza o impulso de apostas desportivas para poupança protegida a render 100% do CDI, garantindo que o utilizador nunca perde o seu capital inicial.

## Problem Statement
Apostadores com rendimentos vulneráveis (como a persona *Givanildo*, estafeta) enfrentam perdas financeiras sucessivas e risco de endividamento devido à facilidade de acesso a apostas desportivas e à ilusão de ganhos imediatos. Parar abruptamente gera abstinência e frustração; por conseguinte, a plataforma substitui a dinâmica destrutiva por uma experiência de jogo em que o valor do palpite se converte em património seguro.

## Scope
- **Onboarding e Perfil Mockado:** Autenticação simplificada e configuração do saldo inicial da persona com garantia de capital 100% protegido.
- **Mecanismo de Palpite Seguro (Yield Bet):** Catálogo de partidas de futebol com opções de aposta simuladas onde o montante colocado nunca é debitado como perda patrimonial.
- **Painel de Rendimento e Impacto:** Visualização em tempo real do saldo total aportado, projeção do rendimento indexado a 100% do CDI e métrica de "capital salvo vs perdas convencionais".
- **Gamificação e Recompensas:** Atribuição de pontos/moedas virtuais por palpite efetuado e catálogo de resgate de vantagens (cupões de combustível, refeições e descontos de parceiros).

## Non-Goals
- Integrações bancárias em produção via Open Finance ou liquidação regulatória real junto do BACEN neste primeiro ciclo de entrega (horizonte de 3 a 4 semanas com custo zero).
- Algoritmos complexos de liquidação de apostas em tempo real ou ligação direta a feeds desportivos pagos (utilização exclusiva de dados mockados em memória/JSON).

## Success Criteria
- O pipeline do OpenSpec valida a especificação e as tarefas sem erros (`openspec validate setup-mvp-core`).
- A interface gráfica permite demonstrar, de forma clara e fluida, o ciclo completo: registo do utilizador, colocação de palpite, preservação do capital a render juros e resgate de recompensas com os pontos acumulados.