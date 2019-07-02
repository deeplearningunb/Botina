# Botina 

Botina é um futuro bot que usa rede neural recorrente para prever preço de ações. :smile:🌽

## O que é uma rede neural?

São modelos computacionais inspirados pelo sistema nervoso central de uma pessoa (em particular o cérebro) que são capazes de realizar o aprendizado de máquina bem como o reconhecimento de padrões. Graficamente é representada pela seguinte imagem:

<img src="https://static.imasters.com.br/wp-content/uploads/2016/06/redes-1.png"
     alt="neural"
     width="800" height="400" />

## E a rede neural recorrente?

Uma rede neural recorrente (RNN) é uma classe de redes neurais que inclui conexões ponderadas dentro de uma camada (em comparação com as redes de feed-forward tradicionais, onde conecta alimentação apenas para camadas subsequentes).

<img src="https://static.imasters.com.br/wp-content/uploads/2017/09/2-1.png"
     alt="neural"
     width="500" height="800" />

## Como a botina funciona?

Primeiro é preciso ter os dados das ações que você deseja usar no dataset. Nesse projeto foi utilizado o papel do Facebook (FBOK34) que você pode encontrar no [Yahoo Finance](https://finance.yahoo.com/quote/FBOK34.SA/history?p=FBOK34.SA) indo em "Historical Data". Caso deseje testas com outro papel basta inserir o nome da empresa na barra de pesquisa.

Depois de baixar o cvs com os dados ele é importado no projeto para ser treinado.

É criado layers da rede neural recorrente (GRU) e dropouts para fazer o predict.

O treinamento acontece e os dados são levados para normalização e são plotados no em um gráfico.

O resultado saiu:

![download](https://user-images.githubusercontent.com/18190061/60477727-7d9be500-9c56-11e9-8e61-d824c20c0c99.png)

### Team 

| Name | GitHub |
|------|:----:|
| Ezequiel de Oliveira |  [EzequielDeOliveria](github.com/EzequielDeOliveira) |
| Gabriel Carvalho |    [GabrielOak](github.com/GabrielOak)  |
| Tayanara Carvalho | [Tayh](github.com/tayh)|


***
Referências:

https://imasters.com.br/data/um-mergulho-profundo-nas-redes-neurais-recorrentes
https://pt.wikipedia.org/wiki/Rede_neural_artificial
