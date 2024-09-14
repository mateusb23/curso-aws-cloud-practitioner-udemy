# IAM Identity Center

**OBS:** Para ativar esse serviço, precisamos ter previamente habilitado o serviço ***AWS Organizations***, o qual 
         será abordado na aula 19 [[.19-AWS-organizations.md]].

 - Esse Serviço é o sucessor do AWS Single Sign-On
    - Single Sign-On era um serviço da AWS que permitia a intercomunicação entre serviços
      , onde apenas com uma conta, tinha-se acesso a todos esses serviços desejados ao mesmo 
      tempo e em tempo real. Sem precisar ter uma conta para acesso para cada um dos serviços.
 - Ele gerencia o acesso de usuários da força de trabalho a várias contas e aplicativos de nuvem
 - Funciona semelhante ao IAM comum, porém, ele possui algumas funcionalidades adicionais.
 
 - ***Em resumo***: O IAM Identity Center faz tudo que o IAM já faz, com a adicional de associar
                    tudo isso a aplicações.
                    EXEMPLO: Em alguns casos nós podemos desejar dar acesso ao nosso provedor de 
                             e-mail pela conta da AWS. E o usuário que utiizamos na AWS, também 
                             podemos utilizar em nosso provedor de e-mail.
