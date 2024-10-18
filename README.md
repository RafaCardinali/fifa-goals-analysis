# Análise Comparativa de Gols em Partidas da Copa do Mundo de Futebol Masculino e Feminino

## Visão Geral
Este projeto realiza uma análise comparativa do número médio de gols marcados em partidas da Copa do Mundo de futebol masculino e feminino, utilizando um teste de hipótese estatístico.

O objetivo é verificar se o número de gols nas partidas de futebol feminino é maior que nas partidas de futebol masculino. Para isso, utilizamos o teste de Mann-Whitney, com um nível de significância de 10%.

## Estrutura do Projeto

- `men_results.csv`: Contém os dados das partidas de futebol masculino.
- `women_results.csv`: Contém os dados das partidas de futebol feminino.
- `fifa-goals-analysis.ipynb`: Notebook com o código que executa a análise comparativa e a visualização dos resultados.

## Pergunta de Pesquisa
O projeto busca responder à seguinte pergunta:

**"Mais gols são marcados em partidas pela Copa do Mundo de futebol feminino do que em partidas de futebol masculino?"**

## Hipóteses

- **Hipótese Nula (H₀)**: O número médio de gols em partidas de futebol feminino é igual ao número médio de gols em partidas de futebol masculino.
- **Hipótese Alternativa (H₁)**: O número médio de gols em partidas de futebol feminino é maior do que em partidas de futebol masculino.

## Metodologia

1. **Filtro de dados**: As partidas utilizadas são limitadas àquelas realizadas após 1º de janeiro de 2002, em torneios oficiais da FIFA (excluindo qualificatórias).
2. **Cálculo do total de gols**: Para cada partida, somamos os gols das equipes da casa e visitante.
4. **Visualização**: A soma de gols dos homens foi apresentada em um histograma para garantir que o teste a ser feito deve ser paramétrico ou não.
3. **Teste de Mann-Whitney**: Aplicamos o teste de Mann-Whitney para verificar a diferença entre as distribuições de gols.

## Resultados
O teste resultou em um valor-p de **0.00510**. Com base no nível de significância de 10%, a hipótese nula foi **rejeitada**.

## Bibliotecas Utilizadas

- `pandas`: Manipulação de dados
- `scipy`: Teste de Mann-Whitney
- `matplotlib`: Visualização de dados

## Como Rodar o Projeto

1. Clone este repositório: 
   ```bash
   git clone https://github.com/RafaCardinali/fifa-goals-analysis.git
    ```
2. Instale as dependências:
    ```bash
    pip install pandas scipy matplotlib
    ```
3. Execute o script Python:
    ```bash
    jupyter notebook fifa-goals-analysis.ipynb
    ```
## Contato

Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

[LinkedIn](https://www.linkedin.com/in/rafael-cardinali-213899296/)

[Email](mailto:rflcardinali@gmail.com)