<h1 align="center">:file_cabinet: Exemplo de README.md</h1>

## :memo: Descrição
Este projeto é destinado ao desafio Cientista de Dados da Indicium.
O projeto diz respeito a um cliente que o core business é compra e venda de veículos usados.
Essa empresa está com dificuldades na área de revenda dos automóveis usados em seu catálogo.
Para resolver esse problema, a empresa comprou uma base de dados de um marketplace de compra 
e venda para entender melhor o mercado nacional, de forma a conseguir precificar o seu catálogo 
de forma mais competitiva e assim recuperar o mau desempenho neste setor.

O objetivo é analisar os dados  para responder às perguntas de negócios feitas pelo cliente 
e criar um modelo preditivo que precifique os carros do cliente de forma que eles fiquem o mais 
próximos dos valores de mercado.


## :wrench: Tecnologias utilizadas
* Linguagem Python no Google Colab

## :rocket: Rodando o projeto
Para rodar o repositório é necessário clonar o mesmo e rodar na IDE de preferência.
Os dados podem ser importados diretamente deste repositório
```
<train = 'https://raw.githubusercontent.com/JoaoDiamantino/CarsPricePredict_LightHouse/main/cars_train.csv'
test = 'https://raw.githubusercontent.com/JoaoDiamantino/CarsPricePredict_LightHouse/main/cars_test.csv'

df = pd.read_csv(train , sep=";" )
dfTeste = pd.read_csv(test , sep=";" )>
```
