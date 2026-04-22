# 📈 Corporate Sales Performance - Star Schema & DAX 

![Dashboard Preview](https://github.com/KauanPolly/Corporate-Sales-Performance---Star-Schema-DAX/blob/main/image.png?raw=true)

## 🛠️ Arquitetura de Dados e Modelagem
Neste projeto, apliquei conceitos avançados de modelagem relacional para transformar um dataset bruto em um ecossistema de Business Intelligence escalável.

### Destaques Técnicos:
* **Star Schema (Esquema Estrela):** Segmentação de dados em tabelas Fato (Vendas) e Dimensões (Produtos, Clientes, Calendário), otimizando o motor de compressão VertiPaq do Power BI.
* **Inteligência de Tempo (DAX):** Desenvolvimento de medidas complexas para análise comparativa anual (YoY - Year over Year), utilizando funções como `CALCULATE`, `SAMEPERIODLASTYEAR` e `DIVIDE` para cálculo de crescimento percentual.
* **Tabela de Calendário Dinâmica:** Criação de uma Dimensão Calendário via DAX (`CALENDARAUTO`) para garantir a continuidade das análises temporais, independente de lacunas no dataset original.

### 📊 Insights Estratégicos:
* Implementação de filtros **Top N** para identificação instantânea dos produtos de maior faturamento.
* Monitoramento de performance mensal comparada, permitindo identificar sazonalidade e desvios de meta em relação ao ano anterior.
