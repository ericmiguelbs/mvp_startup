# YieldBet MVP Specification

## Purpose
A YieldBet é uma fintech de reabilitação financeira gamificada criada para substituir o ciclo destrutivo de apostas esportivas, permitindo que apostadores direcionem o valor de seus palpites para contas seguras remuneradas a 100% do CDI, sem risco de perda do patrimônio principal, mantendo o engajamento com gamificação e recompensas.

## Requirements

### Requirement: Cadastro e Onboarding Simplificado
O sistema deve permitir a criação rápida de conta com dados mínimos e exibição explícita da garantia de patrimônio protegido.

#### Scenario: Novo usuário realiza o cadastro
- **WHEN** o usuário informa os dados de cadastro e conclui o registro
- **THEN** o sistema cria o perfil e exibe a mensagem de que o capital alocado nunca é perdido

### Requirement: Registro de Palpite Protegido
O sistema deve permitir palpites esportivos retendo o valor em conta de investimento em vez de debitar como perda.

#### Scenario: Usuário confirma um palpite
- **WHEN** o usuário seleciona uma partida e confirma o valor do palpite
- **THEN** o valor é alocado no saldo protegido a 100% do CDI e permanece pertencendo ao usuário após o encerramento do evento

### Requirement: Visualização de Saldo e Rendimentos
O sistema deve disponibilizar um dashboard claro com saldo acumulado, rendimento CDI e economia gerada em relação a apostas convencionais.

#### Scenario: Usuário consulta o dashboard principal
- **WHEN** o usuário acessa a tela inicial
- **THEN** o sistema exibe o saldo aportado, o rendimento acumulado e a métrica de capital poupado

### Requirement: Gamificação e Resgate de Recompensas
O sistema deve conceder pontos, selos e catálogo de vantagens a cada ciclo de palpites.

#### Scenario: Concessão de pontos por palpite realizado
- **WHEN** o usuário conclui o registro de um palpite
- **THEN** o sistema credita pontos de experiência na conta e atualiza o catálogo de cupons e cashback disponíveis