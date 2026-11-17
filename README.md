# 🏎️ Porsche AG — Executive Sales Intelligence Dashboard

Dashboard empresarial interativo desenvolvido em **arquivo único HTML autônomo (single-file standalone)**, projetado para responder perguntas estratégicas de negócio sobre o desempenho comercial, a rentabilidade de modelos e a transição para mobilidade elétrica da Porsche.

O projeto segue a estética visual **Dark Luxury**, combinando tipografia refinada (*Syne*, *DM Mono* e *Cormorant Garamond*), paleta metálica dourada (*Porsche Exclusive Manufaktur*), micro-interações fluidas e gráficos dinâmicos orientados à tomada de decisão executiva.

---

## 🎯 Perguntas de Negócio Escolhidas e Justificativa Estratégica

> *"A pergunta de negócio separa a dashboard útil do amontoado de gráficos!"*

As três perguntas foram selecionadas com base nos desafios reais de gestão de uma montadora de supercarros e veículos esportivos de luxo:

### 1. Portfólio & Rentabilidade (Mix de Modelos)

* **Pergunta de Negócio:**  
  *Qual família de modelos é o verdadeiro motor de faturamento da Porsche, e qual o equilíbrio entre ícones de alta margem (911) versus modelos de volume (Macan / 718)?*
* **Por que foi escolhida:**  
  No segmento de altíssimo luxo automotivo, faturamento e prestígio não derivam puramente da quantidade de unidades emplacadas. A liderança comercial precisa identificar a concentração da margem de contribuição.
  * **Insight obtido:** O lendário **Porsche 911** é o principal motor financeiro, gerando **\$ 2.833.700,00** (29,9% da receita total em 16 vendas) com ticket médio recorde de **\$ 177.106,25** — alavancado por edições de topo como *911 GT3* (\$ 241k) e *911 Turbo S* (\$ 235k). O **Taycan** consolidou a vice-liderança com **\$ 2.060.000,50** e ticket de **\$ 147.142,89**, enquanto a linha **Macan** cumpre com precisão o papel de modelo de entrada em escala (ticket médio de \$ 77.696,15), diluindo custos fixos da operação.

---

### 2. Transição Energética & E-Performance (Série Temporal)

* **Pergunta de Negócio:**  
  *A eletrificação (Taycan, Macan Electric e Híbridos E-Hybrid) já é um vetor financeiramente viável frente aos motores a combustão pura (ICE), e como evolui de 2024 a 2027?*
* **Por que foi escolhida:**  
  A Porsche possui a meta corporativa de entregar mais de 80% de suas vendas globais em veículos eletrificados até o final da década. Era vital avaliar se os clientes de alto padrão já direcionam capital substancial para as opções elétricas ou se os motores a combustão interna ainda sustentam a operação isoladamente.
  * **Insight obtido:** A eletrificação já representa **28,7% da receita global** da marca (**\$ 2,72M**). Os modelos **100% Elétricos (BEV)** faturaram **\$ 2.327.500,50** (24,5% do total com 17 carros), complementados por **\$ 393.150,00** em **Híbridos Plug-in (PHEV)**. Na análise anual, a receita saltou de **\$ 1,44M em 2024** para o ápice histórico de **\$ 3,90M em 2026** (31 veículos comercializados), demonstrando aceleração na curva de adesão tecnológica.

---

### 3. Canais de Liquidez & Funil Logístico de Entrega

* **Pergunta de Negócio:**  
  *Quais métodos de pagamento viabilizam as transações de maior valor, e qual o tamanho do impacto financeiro de cancelamentos e pedidos retidos no funil logístico?*
* **Por que foi escolhida:**  
  A aquisição de carros que superam centenas de milhares de dólares envolve instrumentos financeiros atípicos (grandes remessas bancárias, leasing corporativo e criptomoedas). Identificar os gargalos entre a emissão do pedido e a efetiva entrega ao cliente é determinante para proteger o capital de giro.
  * **Insight obtido:** As transferências bancárias diretas (**Wire Transfer**) lideram em volume absoluto com **\$ 2.395.700,00** (16 supercarros), seguidas por **Credit Card** (\$ 1,69M) e **Lease** (\$ 1,25M). A modalidade **Crypto Payment** surpreendeu ao transacionar **\$ 1.083.000,00** em 6 veículos, registrando o **maior ticket médio individual da base: \$ 180.500,00 por veículo**. Em contrapartida, o monitoramento logístico revelou **\$ 516.750,00 em perdas por cancelamentos** (6 veículos) e **\$ 1.254.100,00 em pedidos com status *Pending***, apontando onde o time comercial e financeiro deve intervir.

---

## 📝 Prompt Utilizado para Geração do Dashboard

> *Espaço reservado para você colar o prompt original:*
O Que Criar
Uma dashboard em HTML, arquivo único, que responda perguntas de negócio sobre as vendas - empresa Porshe - fictico apenas um desafio que deve estruturar um Dashboard a partir desse banco desses dados enviados -

O que precisa funcionar:
* Três perguntas de negócioPergunta de Negócio:
Qual família de modelos é o verdadeiro motor de faturamento da Porsche, e qual o equilíbrio entre ícones de alta margem (911) versus modelos de volume (Macan / 718)?
Por que importa para a gestão:
No mercado ultra-premium, volume de unidades não define liderança de margem. A liderança comercial precisa identificar onde está a concentração de rentabilidade bruta e garantir que os modelos de entrada cumpram o papel de captação de clientes sem canibalizar o prestígio da marca.
Resposta Visual:
Gráfico Misto Interativo combinando Receita Total por Família (Barras Douradas) com Ticket Médio (Linha Azul com Marcadores), além de mini-indicadores de participação no faturamento (Share of Wallet) - Pergunta de Negócio:
A eletrificação (Taycan, Macan Electric e Híbridos E-Hybrid) já é um vetor financeiramente viável frente aos motores a combustão pura (ICE), e como evolui ao longo dos anos (2024–2027)?
Por que importa para a gestão:
A Porsche tem como meta estratégica global atingir mais de 80% de suas entregas em veículos eletrificados até o encerramento do ciclo decenal. É indispensável verificar se o capital dos clientes está de fato migrando para veículos elétricos a bateria (BEV) e híbridos plug-in (PHEV) de maneira sustentável ao longo do tempo.
Resposta Visual:
Gráfico Donut de Mix de Faturamento por Propulsão com cálculo dinâmico de faturamento e unidades por tecnologia - Pergunta de Negócio:
Quais métodos de pagamento viabilizam as transações de maior valor, e qual o tamanho do impacto financeiro de cancelamentos e pedidos retidos no funil logístico?
Por que importa para a gestão:
Vendas de bens de alto luxo exigem gestão rigorosa de capital de giro e mitigação de risco de crédito. Identificar os métodos de pagamento dominantes e mensurar a perda em cancelamentos permite ao CFO agir antes que o faturamento se transforme em custo de estoque parado.
Resposta Visual:
Gráfico de Barras Horizontais por Método de Pagamento cruzado com métricas do pipeline de entregas;
* Filtros que deixem recortar os dados, como modelo, cidade, ano ou método de pagamento;
* Indicadores de topo, como total de vendas e receita;                                                                                                                                                                                                             A pergunta de negócio separa a dashboard útil do amontoado de gráficos!                                                             o Dashboard deve seguir o design do HTML anexado a voce

## 🧹 Tratamento e Higienização da Base de Dados

Antes de enviar a massa de dados para processamento e geração analítica pela IA, foram aplicadas etapas rigorosas de ETL (Extração, Transformação e Limpeza):

1. **Exclusão de Colunas Não Sanitizadas:**
   * A base bruta continha campos redundantes e não higienizados. Apenas as colunas com sufixo `Sanitized` foram homologadas e mantidas no modelo de dados final:
     * `sale_id`, `SaleDateSanitized`, `PorscheModelSanitized`, `ModelYearSanitized`, `SalesPriceSanitized`, `VehicleMileageSanitized`, `PayMethodSanitized`, `CitySanitized`, `StateSanitized`, `DeliveryStatusSanitized`.

2. **Exclusão Estrita de Dados Marcados como `INVALID`:**
   * A base original continha **100 transações**.
   * Durante a auditoria de consistência, identificou-se que exatamente **24 registros** possuíam o valor `'INVALID'` na coluna de data de venda (`SaleDateSanitized`).
   * **Tratamento:** Todas as 24 linhas inválidas foram **sumariamente expurgadas** antes de qualquer cálculo ou agregação.
   * **Resultado:** O dashboard opera exclusivamente sobre **76 transações 100% válidas e homologadas**, totalizando uma receita confiável de **\$ 9.486.700,50**.

3. **Enriquecimento e Tipagem Analítica:**
   * Conversão dos preços de venda em valores numéricos decimais de ponto flutuante.
   * Criação de categorização por **Família de Veículos** (*911*, *Taycan*, *Cayenne*, *Panamera*, *Macan*, *718*).
   * Classificação por **Tipo de Propulsão** (*Combustão ICE*, *100% Elétrico BEV*, *Híbrido E-Hybrid PHEV*).
   * Extração de ano da venda para alimentação dos filtros e séries temporais.

---

## 🤖 Ferramenta e Abordagem Utilizada

* **Abordagem:** **Agente Antigravity com referências de trabalhos anteriores já estruturados.**
* **Metodologia de Execução:**
  * Utilização de um agente autônomo Antigravity especializado em engenharia de dados, business intelligence e desenvolvimento front-end de alto nível.
  * O agente inspecionou as referências de design corporativo prévias da biblioteca de padrões (*Dark Luxury* em Vanilla JS com estética minimalista e paleta dourada).
  * Execução de pipeline automatizado em Python para análise exploratória de dados, verificação de consistência e geração de arquivo HTML único (*single-file* com Chart.js e JSON higienizado embutidos inline).
  * Validação dinâmica em tempo real via Chrome DevTools para garantir que todos os filtros reativos, cálculos de KPIs e gráficos renderizem perfeitamente em qualquer dispositivo, online e offline.

---

## 📂 Estrutura de Arquivos da Entrega

```text
atividade DIO/
├── porsche-dashboard.html                      # Dashboard corporativo em arquivo único HTML (Entrega principal)
├── index.html                                  # Espelho do dashboard para abertura imediata via duplo clique
└── README.md                                   # Documentação completa e ordenada do processo
```

---

## 🚀 Como Visualizar o Dashboard
LINK - https://guilhermepedru02-ship-it.github.io/atividade-DIO/
