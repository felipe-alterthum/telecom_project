# Descrição do projeto

Você trabalha como analista para a empresa de telecomunicações Megaline. A empresa oferece aos clientes dois planos pré-pagos: Surf e Ultimate. O departamento comercial quer saber qual dos planos gera mais receita para ajustar o orçamento de publicidade.
Você vai realizar uma análise preliminar dos planos com base em uma pequena seleção de clientes. Você terá dados de 500 clientes da Megaline: que clientes são, de onde eles são, qual plano usam e o número de chamadas e mensagens realizadas em 2018. Seu trabalho é analisar o comportamento dos clientes e determinar qual plano pré-pago gera mais receita. Mais tarde, nas instruções do projeto, você verá exatamente quais aspectos do comportamento dos clientes precisa analisar. Determinar qual plano, em média, gera mais receita é uma tarefa que pode ser resolvida usando testes estatísticos. Você vai receber mais informação sobre isso na seção das instruções do projeto.


# Instruções para concluir o projeto

## Etapa 1. Abra o arquivo de dados e estude as informações gerais

Abaixo estão os caminhos para os arquivos a serem lidos e links para baixá-los, se necessário.

/datasets/megaline_calls.csv Baixar o conjunto de dados

/datasets/megaline_internet.csv Baixar o conjunto de dados

/datasets/megaline_messages.csv Baixar o conjunto de dados

/datasets/megaline_plans.csv Baixar o conjunto de dados

/datasets/megaline_users.csv Baixar o conjunto de dados

## Etapa 2. Prepare os dados

Converta os dados para os tipos necessários.

Encontre e elimine erros nos dados. Certifique-se de explicar quais erros você encontrou e como os eliminou.

Para cada usuário, encontre: O número de chamadas feitas e minutos usados por mês, o número de mensagens de texto enviadas por mês e o volume de dados por mês

A receita mensal para cada usuário.

## Etapa 3. Analise os dados

Descreva o comportamento do cliente: Encontre os minutos, mensagens de texto e volume de dados que os usuários de cada plano necessitam por mês.

Calcule a média, a variância e o desvio padrão.

Construa histogramas. Descreva as distribuições.

## Etapa 4. Teste as hipóteses
Primeira hipótese: As receitas médias para os usuários dos planos Ultimate e Surf são diferentes.

Segunda hipótese:A receita média dos usuários da área de NY-NJ é diferente da receita dos usuários de outras regiões.

## Etapa 5. Escreva uma conclusão geral

# Descrição dos planos
Observação: A Megaline arredonda segundos para minutos e megabytes para gigabytes. Para chamadas, cada chamada individual é arredondada para cima: mesmo que uma chamada tenha durado apenas um segundo, um minuto será contado. Para tráfego da web, sessões individuais da web não são arredondadas para cima. Ao invés disso, o total do mês é arredondado para cima. Se alguém usar 1.025 megabytes no mês, a cobrança será de 2 gigabytes.

Aqui está uma descrição dos planos:

**Surf**

Preço mensal: $20

500 minutos mensais, 50 mensagens de texto e 15 GB de dados. 

Após exceder os limites do pacote:

1 minuto: 3 centavos

1 mensagem de texto: 3 centavos

1 GB de dados: $10

**Ultimate**

Preço mensal: $70

3.000 minutos mensais, 1.000 mensagens de texto e 30 GB de dados

Após exceder os limites do pacote:

1 minuto: 1 centavo

1 mensagem de texto: 1 centavo

1 GB de dados: $7