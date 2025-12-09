# 🏦 Desafio BanVic – Análise de Dados / Engenharia de Analytics  
### Indicium Lighthouse – Case de Avaliação  
**Autor:** Felipe Rocha Casco  
📧 feliperochacasco@yahoo.com.br  

---

## 📌 Sobre o Projeto
Este repositório reúne todo o desenvolvimento do projeto **Desafio BanVic**, realizado para a **Indicium Lighthouse**, com foco em **Análise de Dados, Engenharia de Analytics e Business Intelligence**.

O estudo teve como objetivo realizar uma análise exploratória, comportamental e temporal sobre clientes, transações, propostas e financiamentos do BanVic, identificando padrões estratégicos para tomada de decisão.

---

# 📊 1. Análise Exploratória — Principais Números

| Indicador | Resultado |
|----------|-----------|
| **Volume Total de Propostas** | **R$ 167,78 milhões** |
| **Valor Médio das Prestações** | **R$ 4,88 mil** |
| **Volume Total Financiado pelos Clientes** | **R$ 249,52 milhões** |
| **Valor Médio de Entrada** | **R$ 40,87 mil** |
| **Volume Médio de Transações/ano** | **2,5 mil** |
| **Perfil predominante** | Clientes **+61 anos**, residentes em **AM, ES, SP e MS** |

---

# 📈 2. Indicadores e Insights Relevantes
A análise revelou padrões importantes para as estratégias da instituição:

### 🔹 **Perfis de Clientes**
- Predominância de idosos (+61 anos)  
- Forte concentração geográfica: AM, ES, SP, MS  

### 🔹 **Comportamentos de Consumo**
- Propostas e financiamentos em volumes significativos  
- Comportamento sazonal bem definido  

Esses indicadores ajudam a direcionar ações de marketing, ofertas segmentadas e políticas de crédito.

---

# 📆 3. Dimensão Temporal – Dim Calendar

| Métrica | Resultado |
|--------|-----------|
| **Trimestre com mais transações aprovadas** | 3º trimestre |
| **Trimestre com maior volume financeiro** | 4º trimestre |
| **Mês com maior volume de transações** | Dezembro |
| **Mês com menor volume** | Abril |
| **Picos sazonais** | Julho, Outubro, Novembro, Dezembro |

🔍 *Hipótese verificada:* meses com “R” **não apresentaram** padrão significativo.

---

# 🌐 4. Dados Públicos Utilizados
Foram adicionados dados externos para enriquecer o modelo:

### 📌 Indicadores Econômicos
- **IPCA (2020–2025)**  
- Correlação com volume de transações: **baixa**, mas com variações pontuais relevantes

### 📌 Dados Populacionais (IBGE)
Para entender:
- Distribuição demográfica dos clientes  
- Potencial de mercado por UF  

---

# 🔧 5. Transformações e Engenharia de Dados
Processos aplicados:

- ✔ Correção de **encoding**
- ✔ Padronização de **datas**
- ✔ Limpeza de categorias inconsistentes
- ✔ Criação de **idade** e **faixa etária**
- ✔ Remoção de **outliers**
- ✔ União das tabelas com a **Dim Calendar**
- ✔ Tratamento estrutural para uso no Power BI (DAX, M & Power Query)

---

# 🧠 6. Análises Estratégicas para Tomada de Decisão
As descobertas apoiam decisões de alto impacto:

### 📌 **Trimestres mais lucrativos**  
— Ideal para campanhas financeiras e ampliação de oferta

### 📌 **Picos de demanda**  
— Meses estratégicos para promoções

### 📌 **Perfis por faixa etária**  
— Cliente idoso = maior potencial de oferta de serviços personalizados

---

# 📝 7. Conclusões e Recomendações (para a CEO BanVic)

### 🎯 Estratégias Sazonais
Aproveitar **picos identificados** para ações promocionais e ofertas direcionadas.

### 👴 Segmentação Focada
Criar produtos especialmente desenhados para o público **+61 anos**, predominante na base.

### 📊 Evolução dos Dados
Investigar mais profundamente indicadores macroeconômicos além do IPCA.

### 🛠 Melhoria da Qualidade dos Dados
Implementar pipelines eficientes de:
- validação,
- padronização, 
- integridade.

---

# 🧰 8. Ferramentas Utilizadas
Ferramenta | Uso
---------- | ---
**Excel** | Análise exploratória e validação inicial
**Power BI** | Dashboards e visualizações interativas
**Power Query (M)** | Tratamento e modelagem de dados
**DAX** | Construção de métricas analíticas
**Python/Notebook** | EDA, testes e validação (opcional)

---

# 📁 Arquivos Utilizados
- **CSV:** agencias, clientes, colaborador_agencia, colaboradores, contas, propostas_credito, transacoes  
- **XLS:** IPCA 2020–2025  
- **Power BI:** `LH_BANVIC_FELIPECASCO.pbix`  
- **Apresentação:** `LH_EA_felipeRochaCasco.pdf`  

---

# 📂 Estrutura do Repositório
A estrutura completa está descrita na raiz deste projeto (veja acima).

---

# 📜 Licença
Este projeto está licenciado sob os termos da **MIT License**. Consulte o arquivo `LICENSE` para mais detalhes.

---

# 👤 Autor
**Felipe Rocha Casco**  
📧 Contato: **feliperochacasco@yahoo.com.br**

