# desafio-c-sharp

- Criar um fork deste repositorio chamado "Fulllab - Desafio C Sharp";

- Realize o desafio, até onde conseguir;

- Qualquer duvida, só perguntar por email;

- Não faça tudo em apenas um COMMIT!

Desafio:

Crie um projeto ASP .NET Web Api, que:

1)Possua uma rota que receba um termo de busca e realize uma busca em uma loja vtex, retornando assim a lista de produtos resultante desta busca em JSON.

  - Documentação do search vtex: https://documenter.getpostman.com/view/845/search-103/Hs43#8b71745e-00f9-6c98-b776-f4468ecb7a5e
  - Loja vtex 1: polishop.vtexcommercestable.com.br
  - Loja vtex 2: taco.vtexcommercestable.com.br

2)Possua uma rota que receba um id de produto e acumule uma visita para este produto no Redis.

  - Documentação do Redis: https://redis.io/documentation


3)Possua uma rota que receba um id de produto e uma data e retorne a quantidade de visitas daquele produto para a data especificada.


4)Possua uma rota que receba um body contendo título e mensagem e crie uma push notification no One Signal via rest api.

  - Documentação do One Signal: https://documentation.onesignal.com/v3.0/docs/onesignal-api
