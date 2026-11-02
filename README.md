# Simulador de Rebaixamento — Brasileirão 2026

## Descrição
Simulador interativo de rebaixamento do Brasileirão 2026 com modelo estocástico calibrado (UFMG/CNN Brasil). Acompanhe a probabilidade de rebaixamento de todos os times após a 33ª rodada, com 51 jogos restantes e simulação Monte Carlo (20.000 cenários).

## Funcionalidades

- **Probabilidade de rebaixamento (Z4)**: Linha de corte projetada de 43 pontos
- **Cards de risco**: Visualização por time com progress bars e porcentagens UFMG
- **Simulação Monte Carlo**: 20.000 rodadas estatísticas para calcular chances de rebaixamento
- **Palpites interactivos**: Escolha vencedores (1, X, 2) para cada jogo restante
- **Presets rápidos**: Cenários pré-definidos (mandante vence, resultados específicos, aleatório)
- **Tabela completa**: Classificação em tempo real com zonas de Libertadores, pré-Libertadores e Sul-Americana

## Tecnologias

- HTML5 semântico com ARIA labels e foco keyboard navigation
- CSS variáveis customizadas com tema dark
- Monte Carlo simulation em JavaScript puro (Poisson sampling)
- Interface responsive (grid adaptativa para mobile/desktop)

## Rodadas Disponíveis

Jogos das rodadas 34 a 38 mais o jogo atrasado da rodada 21:
- 51 confrontos restantes
- Inclui clássicos: Majestoso (São Paulo × Corinthians), Super Decisão (Corinthians × Grêmio)
- Confronto diretos decisivos para o Z4

## Como Usar

1. Selecione palpites para cada jogo (vitória mandante, empate ou visitante)
2. Clique em "Simular Monte Carlo" para rodar 20.000 cenários
3. Veja a probabilidade de rebaixamento atualizada por time
4. Use os presets rápidos para testar cenários específicos

## Melhorias Aplicadas

- Acessibilidade: skip-link, focus-visible states, ARIA labels completos
- Tipografia: variáveis --font-display e --font-body
- UI Polish: transições suaves, cursor:pointer em elementos clicáveis
- Código limpo com comentários explicativos# brasileirao-rebaixamento-2026
