# Análise do Dataset de Anúncios em Redes Sociais

## Visão Geral
Este repositório contém um conjunto de dados em formato CSV chamado `Social_Network_Ads.csv`, que inclui informações demográficas e comportamento de compra de usuários em uma rede social. Esse dataset é utilizado para analisar e prever o comportamento do usuário em relação à compra de produtos com base em sua idade e salário estimado.

## Descrição do Dataset
O arquivo `Social_Network_Ads.csv` inclui as seguintes colunas:
- **Age**: A idade do usuário.
- **EstimatedSalary**: O salário estimado do usuário.
- **Purchased**: Variável binária que indica se o usuário comprou (1) ou não (0) o produto.

### Dados de Exemplo
```
Age,EstimatedSalary,Purchased
19,19000,0
35,20000,0
26,43000,0
...
35,27000,0
33,28000,0
30,49000,0
```

## Descrição dos Arquivos do Repositório
- `.gitignore`: Contém arquivos e diretórios que devem ser ignorados no controle de versão, incluindo o diretório do ambiente virtual Python `venv/`.
- `README.md`: Este arquivo, que providencia uma descrição detalhada do repositório e seu conteúdo.

### Como Utilizar
Para trabalhar com este dataset, recomenda-se a utilização de um ambiente Python isolado, como o criado pelo `venv`. O dataset pode ser importado e analisado utilizando bibliotecas como pandas, numpy e scikit-learn para realizar análises e modelar o comportamento de compra dos usuários baseado nos dados disponíveis.