# INFRAESTRUTURA GLOBAL DA AWS:

## REGIÕES
    - Zonas de Disponibilidade (Availability Zones - AV)
        - DataCenters (DC) que fazem parte da estrutura grande e principal
        - Local Zone --> Data Center menor em uma cidade que está dentro da Availability Zone 
        - Wavelength Zone --> Focadas para desenvolvedores. É uma oferta otimizada para aplicações 
          móveis de computação de borda. Permite que as aplicações tenham latências de um dígito 
          para dispositivos móveis e usuários finais.
        - AWS Outposts --> Leva produtos, infraestrutura e modelos operacionais nativos da AWS a 
          praticamente qualquer DataCenter, espaço de colocalização ou instalações on-premises.
          Podendo usar as mesmas APIs, ferramentas e infraestrutura da AWS no local e na Nuvem AWS
          para oferecer uma experiência híbrida verdadeiramente.

 - EXEMPLO:     Região de Oregon (US-West-2)
    - Zonas de Disponibilidade: 2A, 2B, 2C, 2D (Que estão sempre interconectadas)
    - Local Zones: Costumam ser Data Centers menores e localizados em cidades que estão mais afastadas das cidades
                   onde estão os Data Centers Principais nas Zonas de Disponibilidade.
                   Eles Possuem ligação direta com as Zonas de Disponibilidade.
    - Wavelength Zones 
    - AWS Outposts: São ainda menores que uma Local Zone, pois aplica-se a pequenos povoados, por exemplo, onde a AWS
                    não tem um Zona de Disponibilidade, nem uma Zona Local própria também.
