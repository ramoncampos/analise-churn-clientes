# **Analisando o Churn de Clientes no Power BI**

## Descrição
Este projeto envolveu a análise do churn de clientes para entender os motivos da perda de clientes e a criação de um relatório abrangente utilizando o Power BI. A análise teve como objetivo identificar os principais fatores que contribuem para o churn de clientes e fornecer insights acionáveis para reduzir a rotatividade futura.

## Objetivos
- Identificar padrões e tendências associados ao churn de clientes.
- Determinar os principais fatores que influenciam a rotatividade de clientes.
- Desenvolver visualizações para comunicar os resultados de forma eficaz.
- Fornecer recomendações para reduzir o churn com base na análise.

## Fonte de Dados
A análise foi realizada utilizando um conjunto de dados de uma empresa americana fictícia de telecomunicações chamada Cia Telecom. O conjunto de dados contém informações sobre os clientes e seu status de churn. Inclui vários atributos, como dados demográficos dos clientes, uso de serviços e detalhes da conta.

## Ferramentas e Tecnologias
- Power BI: Para visualização de dados e criação de relatórios.
- Editor Power Query: Para pré-processamento e transformação de dados.
- Arquivo Fonte de Dados: `telecom_data.csv`

## Principais Insights

![Visão Geral da Análise de Churn de Clientes](https://github.com/ramoncampos/analise-churn-clientes/blob/main/analise-churn-visao-geral.png?raw=true)
- **Taxa de churn:** A taxa de churn da Cia Telecom é de ~27%.
- **Principais razões pelas quais os clientes abandonam:**
  - Concorrentes fizeram uma oferta melhor
  - Concorrentes tinham dispositivos melhores
  - Atitude do atendente
- ~45% das razões pelas quais os clientes abandonam estão relacionadas aos concorrentes, levantando a questão: A Cia Telecom é competitiva o suficiente?
- **Taxa de churn por estado:** A taxa de churn na Califórnia é anormalmente alta, com mais de 60% dos clientes deixando a empresa.

## Exploração e Análise de Dados

![Grupos e Categorias da Análise de Churn de Clientes](https://github.com/ramoncampos/analise-churn-clientes/blob/main/analise-churn-grupos.png?raw=true)

### Determinar a Taxa de Churn
- A taxa de churn da Cia Telecom é aproximadamente 27%.

### Investigar as Razões para o Churn
- As 3 principais razões pelas quais os clientes abandonam são:
  - Concorrentes fizeram uma oferta melhor
  - Concorrentes tinham dispositivos melhores
  - Atitude do atendente

### Investigar a Taxa de Churn por Estado
- A Califórnia tem uma taxa de churn anormalmente alta, com mais de 60% dos clientes deixando a empresa.

### Analisar e Visualizar Dados
#### Analisando Demográficos
- **Taxa de churn por idade:** A taxa de churn aumenta com a idade. Os cidadãos seniores (65 anos ou mais) têm uma taxa de churn de 38,46%, significativamente acima da média.
- **Planos Individuais vs. Planos de Grupo:** A taxa de churn para planos individuais é significativamente mais alta, 32,85%, comparado com planos de grupo com 2 ou mais pessoas. A cobrança média mensal para planos de grupo é mais baixa (cerca de $23) comparado com planos individuais ($33,50).
- **Contratos Mensais vs. Anuais:** Contratos mensais têm uma taxa de churn mais alta em comparação com contratos anuais.

![Análise de Churn de Clientes - Cobranças Extras](https://github.com/ramoncampos/analise-churn-clientes/blob/main/analise-churn-extra.png?raw=true)

#### Impacto do Plano de Dados Ilimitados
- **Hipótese:** Pessoas que não possuem um plano de dados ilimitados têm maior probabilidade de churn.
- A taxa de churn é de 32,11% para aqueles com planos de dados ilimitados, comparado com 16,10% para aqueles sem dados ilimitados.
- Clientes que consomem 10 gigabytes ou mais e não têm um plano de dados ilimitado pagam em média $31,19, incorrendo em custos extras por uso adicional de dados.

#### Chamadas Internacionais
- 72% das pessoas sem um plano internacional podem ser clientes potenciais para uma nova promoção.
- A taxa de churn para clientes que pagam por um plano internacional, mas não fazem chamadas internacionais, é extremamente alta.

![Insights da Análise de Churn de Clientes](https://github.com/ramoncampos/analise-churn-clientes/blob/main/analise-churn-insights.png?raw=true)

### Chamadas ao Serviço de Atendimento ao Cliente
- Embora o uso de atendimento ao cliente seja maior para clientes que cancelam, a Califórnia se destaca com a maior taxa de churn e o menor número de chamadas ao atendimento.

## Recomendações
Com base nas descobertas, as seguintes ações são recomendadas para reduzir o churn de clientes:

1. **Aumentar a Competitividade:**
   - Rever e melhorar a precificação e as ofertas de serviços para igualar ou superar os concorrentes.
   - Investir em dispositivos e tecnologia melhores para atrair e reter clientes.

2. **Melhorar o Atendimento ao Cliente:**
   - Abordar questões relacionadas à atitude e eficácia dos atendentes.
   - Aumentar o alcance do atendimento ao cliente, especialmente em estados com alta taxa de churn, como a Califórnia.

3. **Promover Planos de Grupo:**
   - Incentivar os clientes a migrarem para planos de grupo, que têm uma taxa de churn mais baixa e oferecem melhor valor.

4. **Ajustar Tipos de Contrato:**
   - Oferecer incentivos para que clientes mais velhos migrem de contratos mensais para anuais, reduzindo o churn.

5. **Promoção de Planos de Dados Ilimitados:**
   - Promover planos de dados ilimitados, especialmente para clientes que consomem grandes quantidades de dados, para evitar cobranças extras que levam ao churn.

6. **Promoção de Planos Internacionais:**
   - Direcionar promoções para clientes sem planos internacionais ou sugerir que façam downgrade em seus planos para aumentar a satisfação e reduzir o churn.

## Como Executar o Projeto

1. **Clone o repositório:**
    ```bash
    git clone [https://github.com/krystalbrantley/data-analyst-portfolio.git](https://github.com/ramoncampos/analise-churn-clientes)
    cd analise-churn-clientes
    ```

2. **Abra o Relatório no Power BI:**
    - Abra o arquivo `relatorio-churn-clientes_v4.pbix` no Power BI Desktop.
    - Revise e interaja com o relatório para explorar a análise.

3. **Revise a Análise e as Descobertas:**
    - Examine as visualizações e os insights fornecidos no relatório do Power BI.
    - Considere as recomendações e como elas podem ser aplicadas para reduzir o churn de clientes.

## Conclusão

O projeto de Análise de Churn de Clientes forneceu insights valiosos sobre as razões por trás da rotatividade de clientes. Ao utilizar o poder do Power BI para visualização de dados, a análise identificou fatores-chave que influenciam o churn e ofereceu recomendações acionáveis para aprimorar os esforços de retenção de clientes.
