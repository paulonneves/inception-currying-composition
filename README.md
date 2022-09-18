# inception-currying-composition
Proposta de arquitetura de projeto para aplicações funcionais combinando os principais conceitos como: *MapReduce*, *HighOrder Functions*, *Currying* e *composição*.


## Conceitos
Cada Projeto Currying-compose é uma biblioteca de funções e detém uma estrutura fixa de arquivos. O projeto terá o seguinte esquema:

<img src="https://user-images.githubusercontent.com/48892066/190886389-be713d68-c255-4b80-baaf-49a6a95a6574.png" style="width: 500px;"/>

Além disso há um conjunto de regras a serem seguidas:

> As funções devem ser puras e ter apenas uma única responsabilidade.

> Não deve haver laços de repetição.

> O arquivo Filters deve haver apenas funções com verificação booleana.

> Os arquivos Maps e Reducers devem lidar com um item do array e serão usadas para implementação do map e reduce no arquivo Composers.

> Os transformers são funções que lidam com o array ou objeto inteiro.


