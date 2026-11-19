# ⚽ Simulador de Rebaixamento — Brasileirão 2026

![Brasileirão 2026](https://img.shields.io/badge/Brasileir%C3%A3o-2026-green?style=for-the-badge)
![Atualizado](https://img.shields.io/badge/Atualizado-19%2F11%2F2026-blue?style=for-the-badge)
![Monte Carlo](https://img.shields.io/badge/Monte%20Carlo-20.000x-orange?style=for-the-badge)
![Modelo Poisson](https://img.shields.io/badge/Estat%C3%ADstica-Poisson-purple?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-brightgreen?style=for-the-badge&logo=github)
![Licença MIT](https://img.shields.io/badge/Licen%C3%A7a-MIT-yellow?style=for-the-badge)

> 🌐 **Acesse a aplicação ao vivo no GitHub Pages:**  
> **[https://marceloasl99.github.io/brasileirao-rebaixamento-2026/](https://marceloasl99.github.io/brasileirao-rebaixamento-2026/)**

---

## 📌 Sobre o Projeto

Uma aplicação web interativa em página única (*Single-Page Application*), desenvolvida em **HTML5, CSS3 e Vanilla JavaScript puro** (sem dependências ou frameworks externos), que simula todas as probabilidades e cenários da reta final do **Campeonato Brasileiro de 2026**.

O simulador combina um **modelo estocástico de gols via Distribuição de Poisson** com um motor de **20.000 simulações de Monte Carlo** executadas diretamente no navegador em alta performance com *TypedArrays*.

---

## 🚨 Panorama Atual do Campeonato (Atualizado em 19/11/2026)

Após os primeiros jogos da 35ª rodada, a disputa contra o rebaixamento segue aberta:

* 🟥 **Chapecoense confirmada na Série B**: A equipe chegou a 21 pontos em 35 jogos e encerrou sua participação desta rodada sem chance de permanência.
* 🦅 **Corinthians reage**: A goleada por 4 a 0 sobre o Botafogo levou o Timão a 40 pontos e para a 15ª posição.
* 🟦 **Remo respira, mas segue ameaçado**: A vitória por 2 a 0 sobre a Chapecoense colocou o Leão Azul em 32 pontos.
* 🇪🇪 **Grêmio permanece pressionado**: O empate com o Bahia levou o Tricolor gaúcho a 38 pontos e manteve-o na zona de rebaixamento.
* 🏆 **Flamengo lidera**: A vitória por 2 a 1 sobre o Athletico-PR levou o Rubro-Negro a 79 pontos em 35 jogos.
* ⚡ **Cruzeiro vence o Palmeiras**: A Raposa chegou a 63 pontos e se consolida na 3ª colocação.
* 🎯 **Linha de Corte Projetada**: Os dados oficiais apontam para uma margem próxima de 42 a 43 pontos.

---

## 📅 Placares Atualizados da 35ª Rodada

| Data | Mandante | Placar | Visitante | Impacto Principal |
| :---: | :--- | :---: | :--- | :--- |
| **14/11** | Mirassol | **0 x 0** | Atlético-MG | Empate mantém Mirassol com 41 pts |
| **18/11** | Coritiba | **0 x 1** | **Santos** | Peixe chega a 50 pts |
| **18/11** | **Remo** | **2 x 0** | Chapecoense | Remo sobe para 32 pts |
| **18/11** | **Cruzeiro** | **2 x 1** | Palmeiras | Raposa chega a 63 pts |
| **18/11** | **Flamengo** | **2 x 1** | Athletico-PR | Líder chega a 79 pts |
| **18/11** | Grêmio | **0 x 0** | Bahia | Grêmio soma 1 ponto e chega a 38 pts |
| **18/11** | **Corinthians** | **4 x 0** | Botafogo | Timão sobe para 40 pts |

---

## 🏆 Tabela Oficial de Classificação (Referência 19/11/2026)

<small>📊 Dados estatísticos do modelo Poisson · 20.000 simulações Monte Carlo</small>

| # | Time | Pts | J | V | E | D | GP | GC | SG | 📉 Risco Z4 | 🏷️ Zona / Situação |
| :-: | :--- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :---: | :--- |
| **1** | 🏆 **Flamengo** | **79** | 35 | 24 | 7 | 4 | 73 | 30 | +43 | 0.0% | 🟢 G4 (Libertadores) |
| **2** | 🥈 **Palmeiras** | **73** | 35 | 21 | 10 | 4 | 63 | 25 | +38 | 0.0% | 🟢 G4 (Libertadores) |
| **3** | 🥉 **Cruzeiro** | **63** | 35 | 19 | 6 | 10 | 57 | 49 | +8 | 0.0% | 🟢 G4 (Libertadores) |
| **4** | 🅿️ **Fluminense** | **57** | 34 | 16 | 9 | 9 | 55 | 42 | +13 | 0.0% | 🟢 G4 (Libertadores) |
| **5** | ⭐ **Athletico-PR** | **54** | 35 | 15 | 9 | 11 | 52 | 45 | +7 | 0.0% | 🔵 Pré-Libertadores |
| **6** | 🅱️ **Bahia** | **54** | 35 | 14 | 12 | 9 | 50 | 45 | +5 | 0.0% | 🔵 Pré-Libertadores |
| **7** | ⚪ **Atlético-MG** | **51** | 35 | 14 | 9 | 12 | 44 | 40 | +4 | 0.0% | 🟡 Sul-Americana |
| **8** | 🅾️ **Santos** | **50** | 35 | 13 | 11 | 11 | 51 | 49 | +2 | 0.5% | 🟡 Sul-Americana |
| **9** | 🅿️ **Red Bull Bragantino** | **47** | 34 | 13 | 8 | 13 | 44 | 39 | +5 | 0.0% | 🟡 Sul-Americana |
| **10** | 🆚 **São Paulo** | **44** | 34 | 12 | 8 | 14 | 39 | 39 | 0 | 0.01% | 🟡 Sul-Americana |
| **11** | 💢 **Vasco da Gama** | **44** | 34 | 12 | 8 | 14 | 45 | 50 | -5 | 1.8% | ⚪ Permanência |
| **12** | ⭐ **Botafogo** | **42** | 35 | 11 | 9 | 15 | 46 | 57 | -11 | 1.5% | 🟡 Sul-Americana |
| **13** | 🟢 **Coritiba** | **42** | 35 | 11 | 9 | 15 | 40 | 52 | -12 | 4.8% | 🟡 Sul-Americana |
| **14** | 🟡 **Mirassol** | **41** | 35 | 10 | 11 | 14 | 39 | 48 | -9 | 16.1% | 🟠 Risco Moderado |
| **15** | 🔴 **Vitória** | **38** | 34 | 10 | 8 | 16 | 35 | 51 | -16 | 21.4% | 🟠 Risco Elevado |
| **16** | 🇦🇹 **Internacional** | **38** | 34 | 9 | 11 | 14 | 38 | 42 | -4 | 40.8% | 🟠 Limite do Z4 |
| **17** | 🦅 **Corinthians** | **40** | 35 | 10 | 10 | 15 | 40 | 42 | -2 | **55.0%** | 🟠 Permanência |
| **18** | 🇪🇪 **Grêmio** | **38** | 35 | 9 | 11 | 15 | 38 | 47 | -9 | **60.4%** | 🟠 Limite do Z4 |
| **19** | 🦁 **Remo** | **32** | 35 | 7 | 11 | 17 | 39 | 57 | -18 | **99.56%** | 🟥 **Zona de Rebaixamento (Z4)** |
| **20** | 🏹 **Chapecoense** | **21** | 35 | 4 | 9 | 22 | 33 | 72 | -39 | **100.0%** | 🪦 **REBAIXADA À SÉRIE B 2027** |

---

## 🧮 Motor Matemático e Algoritmo de Simulação

### 1. Modelo de Gols por Distribuição de Poisson Bivariada
O cálculo das probabilidades de cada confronto baseia-se na força ofensiva (`att`) e defensiva (`def`) de cada equipe, ponderadas pela média histórica da liga e vantagem do mando de campo:

$$\lambda_h = \text{LEAGUE\_AVG} \times \exp(\text{att}_h + \text{def}_a + \text{HOME\_ADV}/2)$$
$$\lambda_a = \text{LEAGUE\_AVG} \times \exp(\text{att}_a + \text{def}_h - \text{HOME\_ADV}/2)$$

A probabilidade de ocorrência de cada resultado exato (de 0x0 até 8x8) é calculada pela função de probabilidade de Poisson:
$$P(k; \lambda) = \frac{\lambda^k e^{-\lambda}}{k!}$$

Com base nisso, os botões de aposta (**1**, **X**, **2**) exibem as chances reais em tempo real.

### 2. Simulação Estocástica de Monte Carlo (20.000 iterações)
* **Jogos Fixados**: Qualquer palpite escolhido pelo usuário é respeitado como resultado certo na simulação.
* **Jogos Abertos**: Os gols de cada equipe são sorteados via gerador estocástico de Poisson (algoritmo de Knuth).
* **Desempate Oficial da CBF**: A cada rodada simulada, a tabela final é recalculada estritamente por:
  1. Pontos ganhos
  2. Número de vitórias
  3. Saldo de gols
  4. Gols pró
* As posições 17 a 20 (Z4) são computadas e as porcentagens de rebaixamento são atualizadas instantaneamente.

---

## 🎮 Funcionalidades da Aplicação

* 🌓 **Tema Claro e Escuro**: Interface inicia no modo claro, com alternância disponível no cabeçalho e preferência salva no navegador.
* 🕹️ **Palpites Interativos nos 33 Jogos Restantes**: Selecione Mandante (1), Empate (X) ou Visitante (2) para projetar os cenários que salvam ou rebaixam seu time.
* ⚡ **Presets de Cenários Rápidos**:
  * *Corinthians vence Botafogo e Grêmio*
  * *Inter vence Vitória e Bragantino*
  * *Grêmio vence Mirassol e Bahia*
  * *Lógica do Mandante (todos os donos da casa vencem)*
  * *Gerar 1 Cenário Estatístico (sorteio aleatório ponderado pelas odds)*
* 📊 **Cards de Risco no Z4**: Acompanhamento visual dos 10 times mais ameaçados com barras de progresso dinâmicas coloridas (seguro, atenção, perigo).
* 🏟️ **Broadcast Stadium HUD (Placares Encerrados)**: Visualização de alta fidelidade televisiva dos 18 jogos encerrados até 19/11, com:
  * **Barra de Filtros Segmentada**: Abas para isolar jogos por *Todos (11)*, *Luta no Z4 (9)*, *G4 / Título (5)* e *⚡ Goleadas & Viradas (3)*.
  * **Linha do Tempo dos Gols**: Autores e minutagem exata de cada gol com badges visuais.
  * **Badges de Impacto Narrativo**: Destaques contextuais imediatos (*Queda Matemática Confirmada*, *Grêmio Afunda no Z4*, *Goleada 5x1*).
  * **Tipografia Numérica Atlética**: Dígitos em visor digital escuro com numerais tabulares alinhados.
* ♿ **Acessibilidade e Design Responsivo**:
  * Total conformidade com WCAG 2.1 (skip link, `:focus-visible`, labels ARIA dinâmicos).
  * Design otimizado com tema dark moderno e legibilidade garantida em qualquer celular, tablet ou desktop.
  * Zero dependências externas (sem frameworks pesados ou CDNs lentos).

---

## 🔍 Otimização para Mecanismos de Busca (SEO, AEO e GEO)

A aplicação foi integralmente estruturada seguindo as diretrizes avançadas de SEO técnico do kit **`claude-seo`** e do Google Search Essentials:

* 🏷️ **Metadados Completos**: `<title>` atrativo sob 60 caracteres, `<meta description>` focada em intenção de busca, canonical tag e tags de indexação (`max-snippet`, `max-image-preview:large`).
* 📱 **Social Sharing (OpenGraph & Twitter)**: Cartões visuais completos (`og:image`, `twitter:card`) com banner dedicado em vetor (`og-image.svg`) para pré-visualizações ricas no WhatsApp, Twitter, LinkedIn e Discord.
* 🤖 **Schema.org Estruturado (JSON-LD + Microdata)**: Entidades completas com `@graph` cobrindo `WebApplication`, `SportsEvent`, `FAQPage` (para rich snippets no Google) e `BreadcrumbList`.
* 🗺️ **Rastreamento e Indexação**: Arquivos [`sitemap.xml`](file:///C:/44/4/sitemap.xml) e [`robots.txt`](file:///C:/44/4/robots.txt) para indexação rápida no Google Search Console e Bing.
* 🧠 **GEO / AEO (Agentic Search)**: Arquivo [`llms.txt`](file:///C:/44/4/llms.txt) padronizado para descoberta orgânica por mecanismos de IA generativa (ChatGPT Search, Perplexity, Claude e Gemini).
* ❓ **Conteúdo Indexável On-Page**: Seção de FAQ (Perguntas Frequentes) e Metodologia Científica com HTML semântico (`<details>`, `<summary>`) renderizada nativamente para indexação de palavras-chave de cauda longa (*long-tail keywords*).

---

## 🚀 Como Executar Localmente

Como a aplicação é 100% autocontida em um único arquivo HTML, executá-la é simples e instantâneo:

```bash
# 1. Clone o repositório
git clone https://github.com/marceloasl99/brasileirao-rebaixamento-2026.git

# 2. Acesse o diretório
cd brasileirao-rebaixamento-2026

# 3. Abra o arquivo index.html no navegador diretamente:
# No Windows:
start index.html

# No macOS:
open index.html

# No Linux:
xdg-open index.html

# Ou suba um servidor HTTP local simples:
python -m http.server 8000
# Acesse no navegador: http://localhost:8000
```

---

## 🌐 Publicação no GitHub Pages

O projeto já está configurado para publicação automática no **GitHub Pages** a partir do branch `main`. Qualquer atualização enviada ao repositório é refletida no ar em instantes.

🔗 **Link de Produção**: [https://marceloasl99.github.io/brasileirao-rebaixamento-2026/](https://marceloasl99.github.io/brasileirao-rebaixamento-2026/)

---

## 📄 Licença

Este projeto é disponibilizado sob os termos da licença **MIT**. Consulte o repositório para mais detalhes.

---

*Desenvolvido com foco em ciência de dados esportiva, probabilidades estocásticas e interfaces de alto desempenho.*
