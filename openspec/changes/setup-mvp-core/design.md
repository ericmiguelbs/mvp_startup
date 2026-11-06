# Design: setup-mvp-core

## Architecture
Aplicação Web Single Page Application (SPA) modular com Tailwind CSS e gestão de estado reativa em memória (JavaScript), simulando a experiência completa de 5 ecrãs funcionais[cite: 3].

## Components & Views
1. **ViewLogin (Onboarding):** Formulário de autenticação simplificado com configuração do aporte inicial protegido[cite: 2, 3].
2. **ViewDashboard:** Visão consolidada de saldo acumulado, rendimento CDI diário e métrica de capital salvo contra perdas[cite: 2, 3, 4].
3. **ViewPalpites:** Catálogo de partidas desportivas com modal interativo para alocação de valores[cite: 2, 3].
4. **ViewRendimentos:** Extrato analítico comparativo entre o modelo seguro YieldBet e o cenário de perdas de casas de apostas convencionais[cite: 2, 3, 4].
5. **ViewRecompensas:** Montra de vantagens e cupões de parceiros resgatáveis através de pontos acumulados[cite: 2, 3, 4].

## Data Schema (In-Memory State)
- `user`: `{ nome, telefone, saldoAportado, rendimentoCDI, pontos }`
- `matches`: Lista de objetos `{ id, casa, fora, horario, camp }`
- `betsHistory`: Registo cronológico `{ id, partida, palpite, valor, data }`
- `transactions`: Extrato financeiro `{ data, tipo, destino, valor, status }`
- `rewards`: Catálogo de benefícios `{ id, title, parceiro, custo, icon }`