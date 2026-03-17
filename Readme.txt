# 🎮 Xbox Pass Subscriptions Sales Dashboard

Dashboard de vendas de assinaturas Xbox desenvolvido no Microsoft Excel, com foco na organização e visualização de dados para análise do desempenho comercial e tomada de decisões baseadas em dados.



## 📋 Sobre o Projeto

Este projeto transforma dados brutos de **Assinantes Xbox** em visualizações claras e objetivas, permitindo identificar padrões de receita por plano, tipo de assinatura e adesão aos Season Passes.



## 📁 Estrutura do Arquivo

O arquivo `xbobx_subscription.xlsx` é organizado em 4 abas:

| Aba | Descrição |
|---|---|
| `Assets` | Paleta de cores e referências visuais do tema Xbox |
| `Bases` | Dados brutos dos 295 assinantes |
| `Cálculos` | Tabelas dinâmicas com agrupamentos e totais |
| `Dashboard` | Painel visual final — **Xbox Pass Subscriptions Sales** |



## 📊 Dados Utilizados

Base com **295 registros** de assinantes, contendo as seguintes colunas:

| Coluna | Descrição |
|---|---|
| `Subscriber ID` | Identificador único do assinante |
| `Name` | Nome do assinante |
| `Plan` | Plano contratado: Core, Standard ou Ultimate |
| `Start Date` | Data de início da assinatura |
| `Auto Renewal` | Renovação automática (Yes/No) |
| `Subscription Price` | Preço base da assinatura (R$) |
| `Subscription Type` | Periodicidade: Monthly, Quarterly ou Annual |
| `EA Play Season Pass` | Adesão ao EA Play (Yes/No) |
| `EA Play Season Pass Price` | Valor do EA Play Season Pass (R$) |
| `Minecraft Season Pass` | Adesão ao Minecraft (Yes/No) |
| `Minecraft Season Pass Price` | Valor do Minecraft Season Pass (R$) |
| `Coupon Value` | Desconto aplicado via cupom (R$) |
| `Total Value` | Valor total pago pelo assinante (R$) |

### Resumo dos dados

| Métrica | Valor |
|---|---|
| Total de assinantes | 295 |
| Ticket médio | R$ 25,87 |
| Desconto médio (cupom) | R$ 7,19 |
| Plano mais popular | Core (101 assinantes) |
| Tipo mais comum | Monthly (139 assinantes) |



## 📈 Análises Presentes na Aba Cálculos

As tabelas dinâmicas cobrem:

- **Receita por Auto Renewal** — comparação entre assinantes com e sem renovação automática (Sim: R$ 1.502 / Não: R$ 806)
- **EA Play Season Pass por Plano** — receita do EA Play filtrada por assinaturas Quarterly, agrupada por Core, Standard e Ultimate
- **Minecraft Season Pass por Plano** — receita do Minecraft filtrada por assinaturas Quarterly, agrupada por plano (Total: R$ 1.140)



## 🚀 Como Reproduzir

### Pré-requisitos

- Microsoft Excel 2016 ou superior

### Passos

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Abra o arquivo**
   ```
   Abra o arquivo xbobx_subscription.xlsx no Excel
   ```

3. **Navegue pelas abas**
   - Consulte os dados brutos na aba `Bases`
   - Explore os agrupamentos na aba `Cálculos`
   - Visualize o painel na aba `Dashboard`

4. **Atualize os dados (opcional)**
   - Adicione ou edite registros na aba `Bases`
   - Atualize as Tabelas Dinâmicas clicando com o botão direito → **Atualizar**



## 🎨 Identidade Visual

O dashboard segue a paleta oficial Xbox definida na aba `Assets`:

| Cor | Hex |
|---|---|
| Verde Xbox | `#9BC848` |
| Verde Neon | `#22C55E` |
| Verde Água | `#2AE6B1` |
| Verde Claro | `#5BF6A8` |



