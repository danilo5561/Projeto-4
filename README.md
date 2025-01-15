# Análise de Planos Pré-Pagos da Megaline

## Objetivo do Projeto
Este projeto tem como objetivo analisar os dois planos pré-pagos oferecidos pela empresa de telecomunicações Megaline — **Surf** e **Ultimate** — para determinar qual deles gera maior receita. A análise ajudará o departamento comercial a ajustar o orçamento de publicidade com base no comportamento dos clientes e na lucratividade de cada plano.

## Descrição do Projeto
A base de dados contém informações de 500 clientes da Megaline, incluindo:
- Dados demográficos e região dos clientes;
- Plano utilizado (Surf ou Ultimate);
- Número de chamadas, mensagens enviadas e volume de dados consumidos em 2018.

### Metodologia
1. **Preparação dos Dados**:
   - Conversão de dados para os tipos adequados.
   - Identificação e correção de possíveis inconsistências ou erros nos dados.
   - Cálculo de métricas mensais para cada cliente:
     - Número de chamadas realizadas e minutos utilizados.
     - Quantidade de mensagens enviadas.
     - Volume de dados consumido.
     - Receita mensal gerada considerando excedentes dos pacotes.

2. **Análise Exploratória**:
   - Comportamento do cliente por plano:
     - Estatísticas descritivas (média, variância, desvio padrão).
     - Histogramas das distribuições de minutos, mensagens e volume de dados.
   - Comparação do comportamento entre os planos Surf e Ultimate.

3. **Testes de Hipóteses**:
   - **Hipótese 1**: As receitas médias dos planos Surf e Ultimate são diferentes.
   - **Hipótese 2**: A receita média dos usuários da região de NY-NJ é diferente da de outras regiões.
   - Realização de testes estatísticos para verificar significância.

4. **Conclusão Geral**:
   - Resumo dos resultados e recomendações para a estratégia comercial.

## Resultados
- O volume de dados consumido pelos clientes do plano **Surf** ultrapassa frequentemente o limite do plano, gerando receitas adicionais significativas para a empresa.
- Apesar de o comportamento médio entre os usuários dos dois planos ser semelhante, o plano **Ultimate** apresenta maior custo-benefício para os clientes.
- A região **NY-NJ** não apresenta diferença significativa na receita média em comparação com outras regiões, com base nos testes realizados.

### Insights Relevantes:
1. O plano **Surf** gera mais receita para a empresa devido ao consumo de internet que frequentemente excede o limite do plano.
2. Para os clientes, o plano **Ultimate** seria mais vantajoso financeiramente, mas para a empresa, manter clientes no plano **Surf** é mais lucrativo.

## Conclusão
Este projeto demonstrou que, enquanto os clientes do plano **Surf** poderiam se beneficiar de um upgrade para o plano **Ultimate**, a empresa Megaline obtém maior lucro quando os clientes permanecem no plano Surf devido às taxas de excedente.

---

**Autores**: Danilo  
**Ferramentas Utilizadas**: Python, Pandas, Matplotlib, Seaborn  
**Contato**: [Meu LinkedIn](https://www.linkedin.com/in/danilojosedelara/)
