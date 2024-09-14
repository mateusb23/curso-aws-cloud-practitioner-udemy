# Resumo - Infra Global

A infraestrutura global da AWS é a base sobre a qual os serviços da AWS são construídos. Ela consiste em uma 
série de Regiões e Zonas de Disponibilidade espalhadas pelo mundo, projetadas para fornecer um serviço seguro, confiável e escalável.

    - Regiões: Uma região da AWS é uma área geográfica que contém pelo menos duas Zonas de Disponibilidade. 
      Cada região é completamente independente das outras regiões, o que ajuda a isolar falhas e evitar a 
      propagação de problemas de uma região para outra. Em setembro de 2021, a AWS tinha 25 regiões geográficas ao redor do mundo.

    - Zonas de Disponibilidade (AZs): Cada região da AWS é dividida em Zonas de Disponibilidade. Cada AZ é 
      um centro de dados separado dentro de uma região, mas todas as AZs dentro de uma região estão conectadas 
      através de redes de alta velocidade, de baixa latência e totalmente redundantes. As AZs fornecem uma maneira 
      de construir aplicativos altamente disponíveis e tolerantes a falhas.

    - Zonas Locais: As zonas locais da AWS aproximam a computação, o armazenamento, o banco de dados e outros produtos da AWS 
      selecionados dos usuários finais. Com as zonas locais da AWS, você pode executar facilmente aplicativos altamente exigentes 
      que exigem latências em milissegundos de um dígito para seus usuários finais, como criação de conteúdo de mídia e entretenimento, 
      jogos em tempo real, simulações de reservatórios, automação de projetos eletrônicos e machine learning.

    - Wavelenght: O AWS Wavelength permite que os desenvolvedores criem aplicações com latências de um dígito para dispositivos móveis 
      e usuários finais. Os desenvolvedores da AWS podem implantar seus aplicativos nas Zonas do Wavelength, implantações de infraestrutura 
      da AWS que incorporam serviços de computação e armazenamento da AWS aos datacenters dos provedores de telecomunicações na borda das 
      redes 5G e acessam facilmente a variedade de serviços da AWS na região. Isso permite que os desenvolvedores forneçam aplicativos que 
      exigem latências inferiores a 10 milissegundos, como streaming de jogos e vídeos ao vivo, inferência de machine learning na borda e 
      realidade aumentada e virtual (AR/VR).

    - OutPosts: O AWS Outposts leva produtos, infraestrutura e modelos operacionais nativos da AWS a praticamente qualquer datacenter, 
      espaço de colocalização ou instalações on-premises. Você pode usar as mesmas APIs, ferramentas e infraestrutura da AWS no local 
      e na Nuvem AWS para oferecer uma experiência híbrida verdadeiramente consistente. O AWS Outposts foi projetado para ambientes 
      conectados e pode ser usado para oferecer suporte a workloads que precisam permanecer on-premises devido à baixa latência ou às 
      necessidades de processamento de dados locais.

A infraestrutura global da AWS permite que os usuários implantem seus aplicativos e serviços de maneira flexível, resiliente e eficiente 
em termos de latência, onde quer que seus clientes estejam localizados no mundo. Isso significa que, como usuário da AWS, você pode oferecer 
uma experiência de usuário mais rápida e melhor para seus clientes, independentemente de sua localização geográfica.
