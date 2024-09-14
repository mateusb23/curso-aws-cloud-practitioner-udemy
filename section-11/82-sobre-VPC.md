# VPC (Virtual Private Cloud)

    --> REDES DENTRO DA AWS

---> Vamos ao seguinte exemplo:
    - Temos uma VPC, e dentro dela temos algumas instâncias
    - Essas instâncias EC2 são webservers que ganham endereçamentos IP dentro de uma ***SUBNET***
    - Dentro dessa subnet as instâncias conseguem se comunicar normalmente.
    - Essa Subnet está dentro de uma ZONA DE DISPONIBILIDADE(AZ - Availability Zone)
    - Normalmente a SubNet e a VPC não possuem acesso à internet, para que isso seja possível Adicionamos um ***INTERNET GATEWAY***
    - O Internet Gateway vai permitir acesso para fora e acesso para dentro.
    - Podemos definir quais SubNets irão acessar a internet e quais não irão
      - Por exemplo: Temos uma SubNet com algumas instâncias EC2 e outra SubNet com instâncias com bancos de dados,
                     onde as instâncias precisam acessar a internet permitindo acessso para fora e para dentro delas,
                     mas a SubNet com os bancos de dados precisa ficar privada, pois não hã necessidade de que ela se
                     comunique com a internet. Com isso, não devemos adicionar a SubNet com os bancos ao INTERNET GATEWAY. 