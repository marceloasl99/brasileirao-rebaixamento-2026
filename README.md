# ⚽ Simulador de Rebaixamento — Brasileirão 2026

![Brasileirão 2026](https://img.shields.io/badge/Brasileir%C3%A3o-2026-green?style=for-the-badge)
![34ª Rodada](https://img.shields.io/badge/34ª%20Rodada-05%2F11%2F2026-blue?style=for-the-badge)
![Monte Carlo](https://img.shields.io/badge/Monte%20Carlo-20.000x-orange?style=for-the-badge)
![Modelo UFMG](https://img.shields.io/badge/Estat%C3%ADstica-UFMG%20%2F%20Poisson-purple?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-brightgreen?style=for-the-badge&logo=github)
![Licença MIT](https://img.shields.io/badge/Licen%C3%A7a-MIT-yellow?style=for-the-badge)

> 🌐 **Acesse a aplicação ao vivo no GitHub Pages:**  
> **[https://marceloasl99.github.io/brasileirao-rebaixamento-2026/](https://marceloasl99.github.io/brasileirao-rebaixamento-2026/)**

---

## 📌 Sobre o Projeto

Uma aplicação web interativa em página única (*Single-Page Application*), desenvolvida em **HTML5, CSS3 e Vanilla JavaScript puro** (sem dependências ou frameworks externos), que simula todas as probabilidades e cenários da reta final do **Campeonato Brasileiro de 2026**.

O simulador combina um **modelo estocástico de gols via Distribuição de Poisson** calibrado com dados oficiais da **UFMG / CNN Brasil** e um motor de **20.000 simulações de Monte Carlo** executadas diretamente no navegador em alta performance com *TypedArrays*.

---

## 🚨 Panorama Atual do Campeonato (Atualizado em 05/11/2026)

Com a realização de **9 das 10 partidas da 34ª rodada**, a disputa contra o rebaixamento atingiu seu momento mais dramático:

* 🟥 **Chapecoense matematicamente rebaixada**: Ao perder em casa por 2 a 1 para o Mirassol na Arena Condá, a Chapecoense permaneceu com 21 pontos e confirmou seu descenso à **Série B de 2027**, tornando-se o primeiro rebaixado confirmado da temporada.
* 🟥 **Remo à beira do abismo (99,56% de risco)**: A goleada sofrida por 5 a 1 diante do Palmeiras deixou a equipe paraense estacionada nos 29 pontos, necessitando de uma combinação estatística quase impossível para escapar.
* 🔥 **Z4 em chamas com gigantes**:
  * **Grêmio (60,4% de risco)**: A derrota por 3 a 1 para o líder Flamengo no Maracanã empurrou o Tricolor gaúcho para a 18ª posição com 37 pontos.
  * **Corinthians (55,0% de risco)**: O empate em 0 a 0 no clássico Majestoso contra o São Paulo manteve o Timão na 17ª posição com 37 pontos (à frente do Grêmio no saldo de gols: -6 vs -9).
  * **Internacional (40,8% de risco)**: Vitória vital por 1 a 0 sobre o Coritiba no Beira-Rio fez o Colorado saltar para 38 pontos na 16ª posição, deixando o Z4 mas ainda sob forte pressão.
* 🛡️ **Alívio para Vasco e Botafogo**: As vitórias do Vasco sobre o Athletico-PR (3 a 1) e do Botafogo sobre o Atlético-MG (1 a 0) derrubaram o risco de rebaixamento de ambos para menos de 2%.
* 🛡️ **Empate no Mineirão**: Cruzeiro 0 x 0 Bahia manteve a Raposa no G4 (58 pts) e o Tricolor de Aço no G6 (54 pts).
* 🎯 **Linha de Corte Projetada**: **42 a 43 pontos** para a permanência na Série A.

---

## 📅 Placares da 34ª Rodada (9 Jogos Realizados até Hoje — 05/11/2026)

| Data | Mandante | Placar | Visitante | Local | Impacto Principal |
| :---: | :--- | :---: | :--- | :--- | :--- |
| **02/11** | **Red Bull Bragantino** | **2 x 1** | Santos | Nabi Abi Chedid | Bragantino sobe para 47 pts; Santos fica em alerta |
| **03/11** | Chapecoense | **1 x 2** | **Mirassol** | Arena Condá | **Chapecoense rebaixada à Série B**; Mirassol respira (40 pts) |
| **03/11** | **Internacional** | **1 x 0** | Coritiba | Beira-Rio | Inter pula para 38 pts e sai do Z4; Coxa estaciona nos 42 pts |
| **04/11** | Athletico-PR | **1 x 3** | **Vasco da Gama** | Ligga Arena | Vasco chega a 41 pts e reduz risco de queda para 1,8% |
| **04/11** | **Flamengo** | **3 x 1** | Grêmio | Maracanã | Mengão consolida liderança (76 pts); Grêmio entra no Z4 |
| **04/11** | **Botafogo** | **1 x 0** | Atlético-MG | Nilton Santos | Glorioso vai a 42 pts e praticamente zera risco de Z4 (1,5%) |
| **04/11** | São Paulo | **0 x 0** | Corinthians | MorumBIS | Timão soma 1 pt no Majestoso e segue no Z4 com 55% de risco |
| **05/11** | **Palmeiras** | **5 x 1** | Remo | Nubank Parque | Verdão vai a 73 pts; Remo fica com 99,56% de risco |
| **05/11** | Cruzeiro | **0 x 0** | Bahia | Mineirão | Raposa garante 58 pts no G4; Bahia soma 54 pts no G6 |

### ⏳ Jogo Restante da 34ª Rodada e Pendência:
* **Vitória x Fluminense** — Sexta-feira, 06/11, às 20h00 (Barradão)
* **Chapecoense x Vasco** — Sábado, 14/11 (Jogo atrasado da 21ª Rodada)

---

## 🏆 Tabela Oficial de Classificação (Referência 05/11/2026)

<small>📊 Dados estatísticos calibrados com o modelo UFMG / CNN Brasil · 20.000 simulações Monte Carlo</small>

| # | Time | Pts | J | V | E | D | GP | GC | SG | 📉 Risco Z4 | 🏷️ Zona / Situação |
| :-: | :--- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :---: | :--- |
| **1** | 🏆 **Flamengo** | **76** | 34 | 23 | 7 | 4 | 71 | 29 | +42 | 0.0% | 🟢 G4 (Libertadores) |
| **2** | 🥈 **Palmeiras** | **73** | 34 | 21 | 10 | 3 | 61 | 23 | +38 | 0.0% | 🟢 G4 (Libertadores) |
| **3** | 🥉 **Cruzeiro** | **58** | 34 | 17 | 7 | 10 | 52 | 46 | +6 | 0.0% | 🟢 G4 (Libertadores) |
| **4** | 🅿️ **Fluminense** | **54** | 33 | 15 | 9 | 9 | 52 | 42 | +10 | 0.0% | 🟢 G4 (Libertadores) |
| **5** | ⭐ **Athletico-PR** | **54** | 34 | 15 | 9 | 10 | 51 | 43 | +8 | 0.0% | 🔵 Pré-Libertadores |
| **6** | 🅱️ **Bahia** | **54** | 34 | 14 | 12 | 8 | 48 | 42 | +6 | 0.0% | 🔵 Pré-Libertadores |
| **7** | ⚪ **Atlético-MG** | **50** | 34 | 14 | 8 | 12 | 44 | 40 | +4 | 0.0% | 🟡 Sul-Americana |
| **8** | 🅿️ **Red Bull Bragantino** | **47** | 34 | 13 | 8 | 13 | 44 | 39 | +5 | 0.0% | 🟡 Sul-Americana |
| **9** | 🅾️ **Santos** | **47** | 34 | 12 | 11 | 11 | 50 | 49 | +1 | 0.5% | 🟡 Sul-Americana |
| **10** | 🆚 **São Paulo** | **44** | 34 | 12 | 8 | 14 | 39 | 39 | 0 | 0.01% | 🟡 Sul-Americana |
| **11** | ⭐ **Botafogo** | **42** | 34 | 11 | 9 | 14 | 46 | 53 | -7 | 1.5% | 🟡 Sul-Americana |
| **12** | 🟢 **Coritiba** | **42** | 34 | 11 | 9 | 14 | 40 | 51 | -11 | 4.8% | 🟡 Sul-Americana |
| **13** | 💢 **Vasco da Gama** | **41** | 33 | 11 | 8 | 14 | 43 | 50 | -7 | 1.8% | ⚪ Permanência (1 jogo a menos) |
| **14** | 🟡 **Mirassol** | **40** | 34 | 10 | 10 | 14 | 39 | 48 | -9 | 16.1% | 🟠 Risco Moderado |
| **15** | 🔴 **Vitória** | **38** | 33 | 10 | 8 | 15 | 35 | 48 | -13 | 21.4% | 🟠 Risco Elevado (1 jogo a menos) |
| **16** | 🇦🇹 **Internacional** | **38** | 34 | 9 | 11 | 14 | 38 | 42 | -4 | 40.8% | 🟠 Limite do Z4 |
| **17** | 🦅 **Corinthians** | **37** | 34 | 9 | 10 | 15 | 36 | 42 | -6 | **55.0%** | 🟥 **Zona de Rebaixamento (Z4)** |
| **18** | 🇪🇪 **Grêmio** | **37** | 34 | 9 | 10 | 15 | 38 | 47 | -9 | **60.4%** | 🟥 **Zona de Rebaixamento (Z4)** |
| **19** | 🦁 **Remo** | **29** | 34 | 6 | 11 | 17 | 37 | 56 | -19 | **99.56%** | 🟥 **Zona de Rebaixamento (Z4)** |
| **20** | 🏹 **Chapecoense** | **21** | 33 | 4 | 9 | 20 | 33 | 68 | -35 | **100.0%** | 🪦 **REBAIXADA À SÉRIE B 2027** |

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

* 🕹️ **Palpites Interativos nos 42 Jogos Restantes**: Selecione Mandante (1), Empate (X) ou Visitante (2) para projetar os cenários que salvam ou rebaixam seu time.
* ⚡ **Presets de Cenários Rápidos**:
  * *Corinthians vence Botafogo e Grêmio*
  * *Inter vence Vitória e Bragantino*
  * *Grêmio vence Mirassol e Bahia*
  * *Lógica do Mandante (todos os donos da casa vencem)*
  * *Gerar 1 Cenário Estatístico (sorteio aleatório ponderado pelas odds)*
* 📊 **Cards de Risco no Z4**: Acompanhamento visual dos 10 times mais ameaçados com barras de progresso dinâmicas coloridas (seguro, atenção, perigo).
* 🏟️ **Broadcast Stadium HUD (Placares Encerrados)**: Visualização de alta fidelidade televisiva dos 9 jogos encerrados da 34ª rodada, com:
  * **Barra de Filtros Segmentada**: Abas para isolar jogos por *Todos (9)*, *Luta no Z4 (7)*, *G4 / Título (4)* e *⚡ Goleadas & Viradas (2)*.
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
