# Amazon Neptune DB

    --> Um banco de dados voltando para uma grande quantidade de conexões de links, como nas Social Networks Wikipédia, 
        Instagram, Facebook, etc, que possuem diversos links entre arquivos entre si.

 1. *Quando o implementamos, ele está da seguinte forma:*
    1. está disponível em 3 AZ(Availability Zones), no mínimo
    2. 15 *READ REPLICAS*, caso necessário, com bilhões de relações, mensagens, informações
    3. Latência muito baixa - miliseconds
    4. Dificult queries (pesquisas complexas na base de dados etc)
    5. Graph dataset