# 📊 DIO INVEST PRO — Simulador Premium de Fundos Imobiliários (Excel)

Este projeto foi desenvolvido como parte do laboratório da DIO com o objetivo de aplicar conceitos de Excel na construção de uma ferramenta prática de simulação de investimentos em Fundos Imobiliários (FIIs).

A planilha permite que o usuário simule aportes mensais, estime o patrimônio acumulado ao longo do tempo e projete dividendos futuros com base em uma taxa de rendimento definida.

---

## 🎯 Objetivos do Desafio

- Criar ferramenta de simulação de investimentos em Excel  
- Aplicar cálculos financeiros (rendimento mensal e dividendos)  
- Automatizar projeções de patrimônio e dividendos  
- Documentar processo técnico de forma estruturada  
- Utilizar GitHub para versionamento e publicação  

---

## 🧮 Conceitos Financeiros Aplicados

- Juros compostos com aportes mensais
- Cálculo de Dividend Yield mensal
- Projeção de crescimento patrimonial
- Reinvestimento opcional de dividendos
- Cálculo de:
  - Total investido
  - Patrimônio acumulado
  - Dividendos no último mês
  - Dividendos acumulados
  - Riqueza total (patrimônio + dividendos sacados)
  - TIR (Taxa Interna de Retorno)
  - VPL (Valor Presente Líquido)
  - CAGR (Taxa de Crescimento Anual Composta)
  - Patrimônio real ajustado pela inflação

---

## 🏗 Estrutura da Planilha

A solução está organizada em quatro abas principais:

### 🔹 APP
Interface principal do usuário, onde são inseridos os parâmetros do investimento:

- Valor inicial
- Aporte mensal
- Prazo em meses
- Dividend Yield mensal
- Crescimento da cota
- Perfil do investidor
- Reinvestimento de dividendos

Exibe automaticamente:
- Total investido
- Patrimônio final
- Dividendos projetados
- Riqueza total

---

### 🔹 ENGINE
Motor de cálculo com projeção mês a mês (até 360 meses), incluindo:

- Saldo inicial
- Aportes
- Dividendos
- Reinvestimento
- Crescimento da cota
- Fluxo de caixa para cálculo de TIR

---

### 🔹 BASE
Tabela de apoio contendo:

- Perfis de investidor (Conservador, Moderado, Agressivo)
- Percentual de alocação por tipo de FII
- Parâmetros de cenários

---

### 🔹 DASH
Dashboard executivo com:

- KPIs principais
- Evolução patrimonial
- Evolução dos dividendos
- Comparação de cenários
- Visual institucional organizado

---

## 📊 Funcionalidades Implementadas

✔ Cálculo automático do total investido  
✔ Projeção mensal detalhada  
✔ Reinvestimento opcional de dividendos  
✔ Simulação de crescimento da cota  
✔ Ajuste por inflação  
✔ Análise por cenários  
✔ Dashboard executivo  
✔ Estrutura modular e organizada  

---

## 🚀 Como Utilizar

1. Abra o arquivo no Excel
2. Vá até a aba **APP**
3. Preencha apenas as células destacadas (inputs)
4. Analise os resultados automáticos
5. Visualize o Dashboard na aba **DASH**

---

## 📈 Possíveis Evoluções Futuras

- Integração com Power Query
- Versão com dados reais de FIIs
- Simulação Monte Carlo
- Versão Power BI
- Automação com VBA

---

## 📌 Conclusão

Este projeto demonstra a aplicação prática de conceitos financeiros no Excel, estruturando uma ferramenta funcional que auxilia investidores na tomada de decisão por meio de projeções automatizadas e visualização estratégica dos dados.

---

### 📎 Autor

Projeto desenvolvido como parte do desafio da plataforma DIO.
