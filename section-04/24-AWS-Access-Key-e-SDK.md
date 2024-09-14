# AWS Access Key e SDK

## Onde usamos e para que servem as duas?
    FAZENDO UM SIMPLES PARALELO:
    - No Console Web da AWS é necessário para logarmos:
        - username
        - password
        - MFA (quando o habilitamos)
    - No Terminal local da AWS com o CLI é necessário:
        - username
            - gerar uma Private Key
            - gerar uma Access Key

 - Quando precisamos trabalhar na AWS pelo terminal local em nosso desktop com o AWS CLI.
   É necessário utilizarmos as credenciais, que são alguma chave de acesso e alguma chave privada.
    - ***COMO FAZEMOS ISSO?***
        - Lá na console da AWS seguimos os seguintes passos:
            - pesquisamos e clicamos no serviço AWS IAM (Identity Access Management)
            - em seguida, vamos nos usuários do serviço IAM e selecionamos um deles(no meu caso eu selecionei a alice)
            - dentro do usuário da alice, nós vamos na opção *Credenciais de segurança* 
            - vamos na parte de *Chave de Acesso* e clicamos em *Criar chave de acesso*

## Onde se encaixa um SDK na AWS?
    Exemplo: Ela se encaixa em cenários onde eu existe uma aplicação dentro de algum servidor local dentro da empresa A.
             E essa aplicação precisa acessar alguns serviços que estão na AWS, ou seja, ela precisa comunicar-se 
             com algum serviço que está dentro da AWS.
    - Para isso é necessário criarmos:
        - username
            - gerar um Private Key 
            - gerar uma Access Key
    - o nome de todo essa organização para fazer com que a aplicação consiga conectar-se com os serviços da AWS chama-se 
      SDK (Software Development Kit)


