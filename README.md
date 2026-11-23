# ⚽ Simulador de Rebaixamento — Brasileirão 2026

![Brasileirão 2026](https://img.shields.io/badge/Brasileir%C3%A3o-2026-green?style=for-the-badge)
![Atualizado](https://img.shields.io/badge/Atualizado-22%2F11%2F2026-blue?style=for-the-badge)
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

## 🚨 Panorama Atual do Campeonato (Atualizado em 22/11/2026)

Após a conclusão de seis jogos da 36ª rodada até 22/11, restam quatro jogos dessa rodada e 20 jogos das rodadas 37 e 38:

* 🟥 **Chapecoense confirmada na Série B**: A equipe chegou a 21 pontos em 36 jogos e encerrou sua participação sem chance de permanência.
* 🦅 **Corinthians reage**: A goleada por 4 a 0 sobre o Botafogo levou o Timão a 40 pontos e para a 16ª posição.
* 🟦 **Remo respira, mas segue ameaçado**: A vitória por 2 a 0 sobre a Chapecoense colocou o Leão Azul em 32 pontos.
* 🇪🇪 **Grêmio permanece pressionado**: O empate com o Bahia levou o Tricolor gaúcho a 38 pontos e manteve-o na zona de rebaixamento.
* 🏆 **Flamengo lidera**: O empate com o Palmeiras manteve o Rubro-Negro com 80 pontos em 36 jogos.
* ⚡ **Cruzeiro vence a Chapecoense**: A Raposa chegou a 66 pontos e se consolida na 3ª colocação.
* 🎯 **Linha de Corte Projetada**: Os dados oficiais apontam para uma margem próxima de 42 a 43 pontos.

---

## 📅 Placares Atualizados da 36ª Rodada

| Data | Mandante | Placar | Visitante | Impacto Principal |
| :---: | :--- | :---: | :--- | :--- |
| **22/11** | **Athletico-PR** | **4 x 2** | Remo | Athletico chega a 57 pts |
| **22/11** | **Fluminense** | **1 x 0** | Mirassol | Flu chega a 63 pts |
| **22/11** | **Bragantino** | **1 x 0** | Vasco | Massa Bruta chega a 50 pts |
| **21/11** | Chapecoense | **1 x 2** | **Cruzeiro** | Raposa chega a 66 pts |
| **21/11** | Bahia | **0 x 1** | **Coritiba** | Coxa permanece com 45 pts |
| **21/11** | Palmeiras | **1 x 1** | Flamengo | Líder segue com 80 pts |
| **14/11** | Mirassol | **0 x 0** | Atlético-MG | Empate mantém Mirassol com 41 pts |
| **19/11** | São Paulo | **0 x 1** | **Fluminense** | Flu chega a 60 pts |
| **19/11** | **Vasco** | **2 x 1** | Internacional | Vasco chega a 47 pts |
| **19/11** | **Vitória** | **2 x 1** | Bragantino | Vitória ganha respiro no Z4 |
| **18/11** | Coritiba | **0 x 1** | **Santos** | Peixe chega a 50 pts |
| **18/11** | **Remo** | **2 x 0** | Chapecoense | Remo sobe para 32 pts |
| **18/11** | **Cruzeiro** | **2 x 1** | Palmeiras | Raposa chega a 63 pts |
| **18/11** | **Flamengo** | **2 x 1** | Athletico-PR | Líder chega a 79 pts |
| **18/11** | Grêmio | **0 x 0** | Bahia | Grêmio soma 1 ponto e chega a 38 pts |
| **18/11** | **Corinthians** | **4 x 0** | Botafogo | Timão sobe para 40 pts |

---

## 🏆 Tabela Oficial de Classificação (Referência 22/11/2026)

<small>📊 Dados estatísticos do modelo Poisson · 20.000 simulações Monte Carlo</small>

| # | Time | Pts | J | V | E | D | GP | GC | SG | 📉 Risco Z4 | 🏷️ Zona / Situação |
| :-: | :--- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :---: | :--- |
| **1** | 🏆 **Flamengo** | **80** | 36 | 24 | 8 | 4 | 74 | 31 | +43 | 0.0% | 🟢 G4 (Libertadores) |
| **2** | 🥈 **Palmeiras** | **74** | 36 | 21 | 11 | 4 | 64 | 26 | +38 | 0.0% | 🟢 G4 (Libertadores) |
| **3** | 🥉 **Cruzeiro** | **66** | 36 | 20 | 6 | 10 | 59 | 50 | +9 | 0.0% | 🟢 G4 (Libertadores) |
| **4** | 🅿️ **Fluminense** | **63** | 36 | 18 | 9 | 9 | 57 | 42 | +15 | 0.0% | 🟢 G4 (Libertadores) |
| **5** | ⭐ **Athletico-PR** | **57** | 36 | 16 | 9 | 11 | 56 | 47 | +9 | 0.0% | 🔵 Pré-Libertadores |
| **6** | 🅱️ **Bahia** | **54** | 36 | 14 | 12 | 10 | 50 | 46 | +4 | 0.0% | 🔵 Pré-Libertadores |
| **7** | ⚪ **Atlético-MG** | **51** | 35 | 14 | 9 | 12 | 44 | 40 | +4 | 0.0% | 🟡 Sul-Americana |
| **8** | 🅿️ **Red Bull Bragantino** | **50** | 36 | 14 | 8 | 14 | 46 | 41 | +5 | 0.0% | 🟡 Sul-Americana |
| **9** | 🅾️ **Santos** | **50** | 35 | 13 | 11 | 11 | 51 | 49 | +2 | 0.5% | 🟡 Sul-Americana |
| **10** | 💢 **Vasco da Gama** | **47** | 36 | 13 | 8 | 15 | 47 | 52 | -5 | 1.8% | ⚪ Permanência |
| **11** | 🆚 **São Paulo** | **44** | 35 | 12 | 8 | 15 | 39 | 40 | -1 | 0.01% | 🟡 Sul-Americana |
| **12** | ⭐ **Botafogo** | **42** | 35 | 11 | 9 | 15 | 46 | 57 | -11 | 1.5% | 🟡 Sul-Americana |
| **13** | 🟢 **Coritiba** | **45** | 36 | 12 | 9 | 15 | 41 | 52 | -11 | 4.8% | 🟡 Sul-Americana |
| **14** | 🟡 **Mirassol** | **41** | 36 | 10 | 11 | 15 | 39 | 49 | -10 | 16.1% | 🟠 Risco Moderado |
| **15** | 🔴 **Vitória** | **41** | 35 | 11 | 8 | 16 | 37 | 52 | -15 | 21.4% | 🟠 Risco Elevado |
| **16** | 🦅 **Corinthians** | **40** | 35 | 10 | 10 | 15 | 40 | 42 | -2 | **55.0%** | 🟠 Permanência |
| **17** | 🇦🇹 **Internacional** | **38** | 35 | 9 | 11 | 15 | 39 | 44 | -5 | 40.8% | 🟠 Limite do Z4 |
| **18** | 🇪🇪 **Grêmio** | **38** | 35 | 9 | 11 | 15 | 38 | 47 | -9 | **60.4%** | 🟠 Limite do Z4 |
| **19** | 🦁 **Remo** | **32** | 36 | 7 | 11 | 18 | 41 | 61 | -20 | **99.56%** | 🟥 **Zona de Rebaixamento (Z4)** |
| **20** | 🏹 **Chapecoense** | **21** | 36 | 4 | 9 | 23 | 34 | 74 | -40 | **100.0%** | 🪦 **REBAIXADA À SÉRIE B 2027** |

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
* As posições 17 a 20 (Z4), 1 a 6 (Libertadores) e 7 a 12 (Sul-Americana) são computadas e as probabilidades de cada zona são atualizadas instantaneamente.

---

## 🎮 Funcionalidades da Aplicação

* 🌓 **Tema Claro e Escuro**: Interface inicia no modo claro, com alternância disponível no cabeçalho e preferência salva no navegador.
* 🏆 **Abas de Probabilidades**: Consulte Z4/rebaixamento, classificação à Libertadores e vagas da Sul-Americana nas mesmas 20.000 simulações.
* 🕹️ **Palpites Interativos nos 24 Jogos Restantes**: Inclui os quatro jogos pendentes da 36ª rodada e os dez jogos das rodadas 37 e 38. Selecione Mandante (1), Empate (X) ou Visitante (2) para projetar os cenários.
* ⚡ **Presets de Cenários Rápidos**:
  * *Corinthians vence Botafogo e Grêmio*
  * *Inter vence Vitória e Bragantino*
  * *Grêmio vence Mirassol e Bahia*
  * *Lógica do Mandante (todos os donos da casa vencem)*
  * *Gerar 1 Cenário Estatístico (sorteio aleatório ponderado pelas odds)*
* 📊 **Cards de Risco no Z4**: Acompanhamento visual dos 10 times mais ameaçados com barras de progresso dinâmicas coloridas (seguro, atenção, perigo).
* 🏟️ **Broadcast Stadium HUD (Placares Encerrados)**: Visualização de alta fidelidade televisiva dos 27 jogos encerrados até 22/11, com:
  * **Barra de Filtros Segmentada**: Abas para isolar jogos por *Todos*, *Luta no Z4*, *G4 / Título* e *⚡ Goleadas & Viradas*.
  * **Linha do Tempo dos Gols**: Autores e minutagem exata de cada gol com badges visuais.
  * **Badges de Impacto Narrativo**: Destaques contextuais imediatos (*Queda Matemática Confirmada*, *Grêmio Afunda no Z4*, *Goleada 5x1*).
  * **Tipografia Numérica Atlética**: Dígitos em visor esportivo com numerais tabulares alinhados.
* ♿ **Acessibilidade e Design Responsivo**:
  * Total conformidade com WCAG 2.1 (skip link, `:focus-visible`, labels ARIA dinâmicos).
  * Design otimizado com temas claro e escuro e legibilidade garantida em qualquer celular, tablet ou desktop.
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
