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

### 🏆 Tabela de Posicionamento (Referência 33ª Rodada)

| Pos | Time | Pts | Zona |
|-----|------|-----|------|
| 1 | Flamengo | 73 | 🏆 G4 |
| 2 | Palmeiras | 70 | 🟢 G4 |
| 3 | Cruzeiro | 57 | 🟢 G4 |
| ... | ... | ... | ... |
| 16 | Coritiba | 42 | ⚠️ Z4 |
| 17 | Botafogo | 39 | ⚠️ Z4 |
| 18 | Vasco | 38 | ⚠️ Z4 |
| 19 | Vitória | 38 | ⚠️ Z4 |
| 20 | Chapecoense | 21 | ⚠️ Z4 |

### 💡 Como Utilizar

1. **Seleção de palpites**: Clique nos botões 1 (mandante), X (empate) ou 2 (visitante) para cada jogo
2. **Rodar simulação**: Clique em "Simular Monte Carlo (20.000x)" para rodar o cálculo estatístico
3. **Analisar resultados**: Veja as probabilidades de rebaixamento atualizadas por time
4. **Testar cenários**: Use os presets rápidos para simular diferentes situações de campeonato

### 🛠️ Tecnologias Utilizadas

- **HTML5** com semantic markup e ARIA labels para acessibilidade
- **CSS3** com variáveis customizadas, tema dark e focus-visible states
- **JavaScript Puro** — simulação Monte Carlo com amostragem Poisson
- **Responsive Design** — grid adaptativa para mobile e desktop

### 📝 Melhorias Aplicadas (UI/UX)

Este projeto incorpora melhores práticas de desenvolvimento frontend:

- ✅ **Acessibilidade**: Skip-link para navegação keyboard, focus-visible states em todos os elementos interativos, ARIA labels completos em tabela, partidas e botões de palpite
- ✅ **Tipografia**: Variáveis `--font-display` e `--font-body` evitando fonts sistêmicas sobreusedas (Arial/Roboto)
- ✅ **Polish UI**: Transições suaves (150ms), cursor:pointer em elementos clicáveis, Estados de foco consistentes
- ✅ **HTML Semântico**: `scope` attributes, estrutura landmarks, labels descritivas
- ✅ **Contraste de Cor**: Focus states com `--accent` sobre fundo `--bg` para visibilidade
- ✅ **Dinâmica**: Atualização ARIA labels após interações do usuário

### 🏷️ Tags do Repositório

- `ui-ux-improvements` - Melhorias de acessibilidade e typography
- `monte-carlo` - Simulação estatística probabilística
- `brasileirao` - Dados do Campeonato Brasileiro
- `z4-rebaixamento` - Contexto de luta contra descenso
- `accessibility` - ARIA, focus states, semantic HTML
- `sports-statistics` - Modelos estatísticos para esportes

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

### 📝 Observação sobre CORS

Como o `index.html` carrega dados e scripts localmente, não há necessidade de configuração adicional para o GitHub Pages. Basta garantir que o `index.html` permanece na raiz do repositório.

### 📄 Licença

Este projeto está licenciado sob os termos da MIT License — veja o arquivo LICENSE para mais detalhes.

---

**Desenvolvido com Claude Code** — Melhorias de UI/UX baseadas no artigo "top-claude-skills-ui-ux-engineers" da Snyk.