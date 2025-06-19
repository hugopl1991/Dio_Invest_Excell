# Desafio "Criando uma Ferramenta de Controle de Investimentos com Excel" da plataforma DIO.me

## Descrição do Desafio

> Este laboratório tem como objetivo tem como objetivo aplicar os conceitos de Excel no desenvolvimento de uma ferramenta prática de simulação de investimentos em fundos imobiliários. A partir de uma compreensão aprofundada sobre como os fundos imobiliários funcionam e as perguntas típicas dos investidores (quanto investir, por quanto tempo, taxa de rendimento, etc.), o desafio consiste em construir uma planilha que ajude o usuário a realizar essas simulações, auxiliando-o a tomar decisões mais informadas sobre seus investimentos. A solução proposta visa automatizar cálculos complexos, como o valor total investido, o patrimônio acumulado e os dividendos mensais, proporcionando ao usuário uma visão clara de seu potencial retorno.

## Planilha

Leves alterações em geral na planilha desenvolvida nas aulas do Professor Felipe Aguiar ("Felipão"). Com maior foco em melhorar o design gráfico da planilha, maior atenção sobre cores e fontes, além de um acabamento mais chamativo.

Pode ser encontrada para baixar e abrir localmente no arquivo Excel: [controle_investimentos](/controle_investimentos.xlsx).

![Aplicação - Topo](/images/principal-cima.png)
![Aplicação - Abaixo](/images/principal-baixo.png)

---

## Outros Recursos

### Mensagem de Entrada

Uma função da Validação de Dados da Seleção de Perfil do Investidor para esclarecer a razão da célula, com título e descrição simples e objetiva para o usuário final.

![Mensagem de Entrada de Dados](/images/mensagem-entrada.png)

### Tabela de Apoio

A Tabela de Apoio utilizada para resgatar o percentual de cada Perfil, utilizando PROCV, na planilha principal, que: identifica a devida Chave Composta (combinação do nome do Perfil com o Tipo de FII) na própria tabela principal, busca a linha certa na tabela de apoio e acha o percentual na coluna especificada.

![Tabela de Apoio](/images/tabela-apoio.png)
