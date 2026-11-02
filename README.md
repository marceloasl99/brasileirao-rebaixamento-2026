# brasileirao-rebaixamento-2026

## 📊 Simulador de Rebaixamento Brasileirão 2026 — Pós 33ª Rodada

Uma aplicação web interativa que simula as chances de rebaixamento do Brasileirão 2026 após a 33ª rodada, utilizando um modelo estocástico calibrado por UFMG/CNN Brasil com **20.000 simulações Monte Carlo**.

### 📅 Dados Atuais (02/11/2026)

- **Rodada referência**: 33ª — 43 pontos como linha de corte projetada para o Z4
- **Jogos restantes**: 51 confrontos (Rodadas 34 a 38 + jogo atrasado R21)
- **Status**: Interface otimizada com melhorias de acessibilidade e UI/UX

### 🎯 Principais Recursos

| Recurso | Descrição |
|---------|-----------|
| **Probabilidade Z4** | Linha de corte projetada: 43 pontos — times abaixo têm risco de rebaixamento |
| **Cards de Risco** | Visualização por time com barras de progresso e porcentagens UFMG calibradas |
| **Simulação Monte Carlo** | 20.000 cenários estatísticos para cálculo de chances reais de rebaixamento |
| **Palpites Interativos** | Selecione vencedores (1, X, 2) para cada um dos 51 jogos restantes |
| **Presets Rápidos** | Cenários pré-definidos: mandante vence, resultados específicos, lógica aleatória |
| **Tabela Completa** | Classificação em tempo real com zonas: G4 (Libertadores), Pré-Libertadores, Sul-Americana, Z4 |

### 🏆 Tabela de Posicionamento (Referência 33ª Rodada — 02/11/2026)

<small>📊 Dados baseados em 20.000 simulações Monte Carlo · Modelo UFMG/CNN Brasil · Atualizado em 02/11/2026</small>

| # | Time | 📍 | Pts | J | V | E | D | SG | 📉 Z4 | 🏷️ Classificação |
|---|------|-----|-----|---|---|---|---|----|-------|------------------|
| 1 | 🏆 **Flamengo** | 1st | 73 | 33 | 22 | 7 | 4 | +40 | 0.0% | 🟢 G4 |
| 2 | 🥈 **Palmeiras** | 2nd | 70 | 33 | 20 | 10 | 3 | +34 | 0.1% | 🟢 G4 |
| 3 | 🥉 **Cruzeiro** | 3rd | 57 | 33 | 17 | 6 | 10 | +6 | 0.3% | 🟢 G4 |
| 4 | 🅿️ **Fluminense** | 4th | 54 | 33 | 15 | 9 | 9 | +10 | 0.5% | 🟢 G4 |
| 5 | ⭐ **Athletico-PR** | 5th | 54 | 33 | 15 | 9 | 9 | +10 | 0.5% | 🟢 G4 |
| 6 | 🅱️ **Bahia** | 6th | 53 | 33 | 14 | 11 | 8 | +6 | 0.7% | 🟢 G4 |
| 7 | ⚪ **Atlético-MG** | 7th | 50 | 33 | 14 | 8 | 11 | +5 | 1.2% | 🟡 Z4 |
| 8 | 🅾️ **Santos** | 8th | 47 | 33 | 12 | 11 | 10 | +2 | 2.1% | 🟡 Z4 |
| 9 | 🅿️ **Bragantino** | 9th | 44 | 33 | 12 | 8 | 13 | +4 | 3.5% | 🟡 Z4 |
| 10 | 🆚 **São Paulo** | 10th | 43 | 33 | 12 | 7 | 14 | 0 | 5.8% | 🟠 Z4 |
| 11 | 🆘 **Coritiba** | 11th | 42 | 33 | 11 | 9 | 13 | -10 | 8.7% | 🟠 Z4 |
| 12 | 🆘 **Botafogo** | 12th | 39 | 33 | 10 | 9 | 14 | -8 | 12.3% | 🟠 Z4 |
| 13 | 🆘 **Vasco** | 13th | 38 | 32 | 10 | 8 | 14 | -9 | 15.4% | 🟠 Z4 |
| 14 | 🆘 **Vitória** | 14th | 38 | 33 | 10 | 8 | 15 | -13 | 18.9% | 🟠 Z4 |
| 15 | 🆘 **Grêmio** | 15th | 37 | 33 | 9 | 10 | 14 | -7 | 22.1% | 🟠 Z4 |
| 16 | 🆘 **Mirassol** | 16th | 37 | 33 | 9 | 10 | 14 | -10 | 25.3% | 🟥 ↓ Z4 |
| 17 | 🆘 **Corinthians** | 17th | 36 | 33 | 9 | 9 | 15 | -6 | 30.1% | 🟥 ↓ Z4 |
| 18 | 🆘 **Internacional** | 18th | 35 | 33 | 8 | 11 | 14 | -5 | 35.7% | 🟥 ↓ Z4 |
| 19 | 🆘 **Remo** | 19th | 29 | 33 | 6 | 11 | 16 | -15 | 52.3% | 🟥 ↓ Z4 |
| 20 | 🆘 **Chapecoense** | 20th | 21 | 32 | 4 | 9 | 19 | -34 | 89.6% | 🟥 ↓ Z4 |

**Legenda de Risco**:
- 🟢 **G4** = Classificação para Libertadores (Posições 1-4)
- 🟡 **Z4** = Zona de rebaixamento (Posições 16-20)
- 🟠 **Atenção** = Próximo do Z4 (Posições 7-15)
- 🟥 **↓ Z4** = Z4 consolidado (Posições 16-20)

**Fonte**: Modelo Estocástico Calibrado (UFMG / CNN Brasil) · 20.000 simulações Monte Carlo · Dados: 02/11/2026 (Pós-33ª Rodada)

> ⚠️ **Observação importante**: As probabilidades de rebaixamento (📉 Z4) são geradas por simulação estatística Monte Carlo com 20.000 cenários, baseadas nos parâmetros de ataque/defesa de cada time e nos palpites do usuário. A "Linha de corte projetada" de **43 pontos** indica a quantidade de pontos que, em média, manteria o time fora do Z4 nesta reta final com 51 jogos restantes.

> 💡 **Dica**: Times com **menos de 43 pontos** estão matematicamente na zona de rebaixamento (Z4). A probabilidade mostra a chance estatística de rebaixamento baseado no desempenho restante de temporada.

### 🛠️ Tecnologias Utilizadas

- **HTML5** com semantic markup e ARIA labels para acessibilidade
- **CSS3** com variáveis customizadas, tema dark e focus-visible states
- **JavaScript Puro** — simulação Monte Carlo com amostragem Poisson
- **Responsive Design** — grid adaptativa para mobile e desktop

### 📸 Screenshots da Interface

> *Capture screenshots após rodar a simulação ou ao visualizar o estado atual do campeonato. Abra o aplicativo em `http://localhost:8000` ou acesse a versão online no GitHub Pages.*

#### Principais prints recomendados:

1. **Tabela Completa** - Mostrando a classificação com cores de zona (G4, Pré-Libertadores, Sul-Americana, Z4) e probabilidades de rebaixamento ao vivo

2. **Cards de Risco** - Visualização das porcentagens de rebaixamento por time com barras de progresso e valores UFMG

3. **Modal de Simulação** - Tela do Monte Carlo em execução com spinner e texto "Calculando 20.000 cenários estocásticos..."

4. **Presets Rápidos** - Interface com os botões de cenários rápidos (Corinthians vence, Lógica do Mandante, Aleatório, etc.)

5. **Gráfico de Probabilidade** - A visualização das barras de progresso ao lado dos times no Z4, mostrando níveis de risco (safe/warning/danger)

#### Como capturar:

```bash
# No navegador (Desktop):
# - PrtScn (Print Screen) e colar em editores de imagem
# - Cmd + Shift + 4 (Mac) para selecionar área
# - Win + Shift + S (Windows) para recorte inteligente

# Ou use a função de print screen do seu SO
# As imagens podem ser salvas em PNG ou JPEG

# Recomendado: usar a versão mobile/desktop responsiva
# Testando em diferentes larguras de tela (375px, 768px, 1440px)
```

#### Exemplos de o que mostrar nas prints:

- **Times no Z4** com barras vermelhas (perigo) ou amarelas (atenção)
- **Líder da tabela** (Flamengo com 73 pontos)
- **Zona de classificação** para Libertadores (G4)
- **Probabilidades individuais** de cada time (ex: "Vasco: 15.4%")
- **Interface dark theme** com o tema visual do projeto

### 🚀 Deploy Rápido e GitHub Pages

A aplicação pode ser visualizada diretamente pelo GitHub Pages:

🌐 **URL ao vivo**: https://marceloasl99.github.io/brasileirao-rebaixamento-2026/

```bash
# Clone o repositório
git clone https://github.com/marceloasl99/brasileirao-rebaixamento-2026.git

# Acesse a pasta
cd brasileirao-rebaixamento-2026

# Ou abra diretamente o index.html em qualquer navegador
open index.html
```

O GitHub Pages já está configurado para servir o `index.html` da branch `main`. As alterações no repositório são refletidas no ar em até 1 minuto.

### 📄 Licença

Este projeto está licenciado sob os termos da MIT License.

---

**Projeto de simulação estatística para o Brasileirão 2026**