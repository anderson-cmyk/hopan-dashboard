# Dashboard HOPAN - Análise de Comissões

Dashboard interativo para análise de comissões e atrasos de operações financeiras HOPAN.

## 🚀 Acesso ao Dashboard

**URL:** https://anderson-cmyk.github.io/hopan-dashboard/

## 📊 Funcionalidades

### 1. KPIs Principais
- Total de Operações
- Valor Total Pago
- Total de Comissões
- Percentual de Comissão Geral

### 2. Análise por Faixa de Atraso
- Visualização em gráfico de barras e linha
- Tabela detalhada com métricas por faixa:
  - 0-20 dias
  - 21-30 dias
  - 31-60 dias
  - 61-90 dias
  - 91-180 dias
  - 181-360 dias
  - Maior que 360 dias

### 3. Tabela Dinâmica Configurável
- Seleção de campo para **Linha**
- Seleção de campo para **Coluna**
- Seleção de campo para **Valor**
- Tipo de agregação:
  - Soma
  - Média
  - Contagem
  - Mínimo
  - Máximo

### 4. Distribuição de % Comissão
- Histograma de distribuição por faixa de atraso
- Estatísticas detalhadas:
  - Média
  - Mediana
  - Mínimo
  - Máximo
  - Desvio Padrão

## 🎨 Design

Interface moderna inspirada no iOS 18 da Apple com:
- Tema escuro (dark mode)
- Animações suaves
- Efeitos hover interativos
- Layout responsivo
- Tipografia San Francisco

## 📁 Estrutura de Dados

### Campos Disponíveis
- **Proposta**: Número da proposta/operação
- **Cliente**: Nome do cliente
- **CPF**: CPF do cliente
- **DataBase**: Data base da operação
- **DataVcto**: Data de vencimento
- **ValorPago**: Valor bruto da operação
- **ValorComissao**: Valor da comissão
- **BaseCalculo**: Base de cálculo da comissão
- **PercComissao**: Percentual de comissão (calculado)
- **Atraso**: Dias de atraso
- **FaixaAtraso**: Faixa de atraso classificada
- **DtPgtoCmss**: Data de pagamento da comissão

## 🛠️ Tecnologias

- **HTML5**
- **CSS3** (Design System iOS 18)
- **JavaScript** (Vanilla JS)
- **Chart.js** (Visualizações)
- **GitHub Pages** (Hospedagem)

## 📈 Dados

Base de dados: **5.569 operações** de setembro/2025
- Total de operações: R$ 10.152.823,05
- Total de comissões: R$ 437.101,63
- Percentual médio: 4,31%

## 📝 Notas

- Dashboard gerado automaticamente a partir do arquivo Excel
- Dados processados e otimizados (colunas zeradas e redundantes removidas)
- Atualização em tempo real via tabela dinâmica
- Análise estatística completa por faixa de atraso

---

**Desenvolvido com Manus AI** | Outubro 2025
