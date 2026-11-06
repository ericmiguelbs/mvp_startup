# Delta: YieldBet MVP Core Setup

## ADDED Requirements

### Requirement: Autenticacao e Onboarding Mockado
O sistema SHALL permitir o acesso simplificado da persona de teste com perfil e saldo inicial configurados[cite: 2, 3].

#### Scenario: Realizacao do primeiro login
- **WHEN** o usuario submete o formulario de login e aporte inicial[cite: 2, 3]
- **THEN** o sistema autentica a sessao e inicializa a conta protegida no dashboard[cite: 2, 3]

### Requirement: Mecanica de Palpites Sem Perda de Capital
O sistema SHALL registrar palpites esportivos retendo o valor em poupanca sem descontar como perda patrimonial[cite: 2, 4].

#### Scenario: Registro de palpite protegido via modal
- **WHEN** o usuario escolhe uma partida e confirma o valor do aporte[cite: 2, 3]
- **THEN** o valor e creditado no saldo seguro a 100% do CDI e o usuario ganha pontos[cite: 2, 4]

### Requirement: Extrato Analitico e Rendimento CDI
O sistema SHALL disponibilizar a tabela detalhada de transacoes e indicadores comparativos de rendimento[cite: 2, 3, 4].

#### Scenario: Consulta do extrato de transacoes
- **WHEN** o usuario navega ate a aba de Extrato e Rendimento[cite: 3]
- **THEN** o sistema lista o historico de aportes e compara com perdas de apostas convencionais[cite: 1, 2, 3]

### Requirement: Catalogo de Cupons e Vantagens Gamificadas
O sistema SHALL permitir o resgate de beneficios com base nos pontos acumulados por palpites[cite: 2, 4].

#### Scenario: Resgate de cupom de parceiro
- **WHEN** o usuario seleciona uma recompensa e confirma com pontos suficientes[cite: 2, 3]
- **THEN** o sistema debita os pontos correspondentes e gera o codigo promocional[cite: 2, 3]