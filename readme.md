Objetivo
A proposta desse projeto é criar uma API capaz de retornar um fato histórico com base no ano informado. A aplicação recebe um ano entre 1920 e 2020 e retorna um fato histórico ocorrido naquele ano. Isso será feito utilizando conteúdos que aprendemos em JavaScript e Node.js.

Dessa forma você poderá colocar em prática os seguintes conceitos:

Estruturas condicionais;
Arrays e coleções;
Funções;
Aplicações em camadas;
API com Node.js e Express;
Recebendo parâmetros com Node.js.
Neste projeto veremos como utilizar recursos do JavaScript e do Node.js para construir uma API que retorna fatos históricos.

API de fatos históricos

O objetivo dessa API é retornar um fato histórico ocorrido entre 1920 e 2020, com base no ano informado pelo usuário.

Requisitos:

. O usuário da aplicação deve informar um ano entre 1920 e 2020
. A API deve buscar o fato correspondente ao ano informado pelo usuário
. Se o fato for encontrado, ele deve ser retornado para ser exibido no front-end
. Se o usuário não informar o ano, informar um ano fora da faixa permitida, ou inválido, 
como por exemplo com letras ao invés de números, o sistema deve informar que o fato não foi encontrado e retornar um código de status 400
. O sistema deve ter um fato para cada ano permitido, totalizando 101 fatos.