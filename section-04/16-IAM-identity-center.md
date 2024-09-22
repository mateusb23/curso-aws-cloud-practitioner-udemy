# IAM Identity Center

### Eu mesmo diria que é uma espécie de AD (Azure Active Directory (Azure AD)) DA AWS Cloud, mas com bastantes diferenças, claro.

  -- **OBS:** Para ativar esse serviço, precisamos ter previamente habilitado o serviço ***AWS Organizations***, o qual 
         será abordado na [aula 19](./19-AWS-organizations.md).

 - Assim como o **IAM** padrão, tem como ***função principal o gerenciamento de acesso** da força de trbalho à contas AWS e aplicações em núvem.
 - Tem algumas funcionalidades a mais, ***quando comparado ao IAM padrão que já conhecemos.***
 - Esse Serviço é o sucessor do AWS **Single Sign-On**
    - **Single Sign-On** era um serviço da AWS que permitia a intercomunicação entre serviços
      , onde apenas com uma conta, tinha-se acesso a todos esses serviços desejados ao mesmo 
      tempo e em tempo real. Sem precisar ter uma conta para acesso para cada um dos serviços.
      - EXEMPLO REAL: Lá onde eu trabalho toda a rede corporativa está na cloud da Microsoft Azure, na qual a senha para acesso ao domínio é a mesma para acesso ao e-mail corporativo, pacote office, teams, VPN, One Drive e diversos outros recursos relacionados à rede em si.
 - Ele gerencia o acesso de usuários da força de trabalho a várias contas e aplicativos de nuvem
 - Funciona semelhante ao IAM comum, porém, ele possui algumas funcionalidades adicionais.
 
 - ***Em resumo***: O IAM Identity Center faz tudo que o IAM já faz, com a adicional de associar
                    tudo isso a aplicações.
                    EXEMPLO: Em alguns casos nós podemos desejar dar acesso ao nosso provedor de 
                             e-mail pela conta da AWS. E o usuário que utiizamos na AWS, também 
                             podemos utilizar em nosso provedor de e-mail.
