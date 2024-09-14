# Sobre o MFA

  ## Suponhamos que estamos em um cenário onde precisamos aumentar a segurança 
  ## das nossas contas criadas na aula 13 com o serviço do IAM:

    - Para isso, precisamos ativar um sistema chamado MFA (Multi Factor Autentication)
    - precisamos ativá-lo, pois agora queremos que o usuário, ao logar na AWS, não precise
      apenas colocar usuário e senha para entrar na AWS.
        - Com isso, por motivos de SEGURANÇA queremos habilitar uma terceira camada
          proteção. 
            ---> E é justamente essa terceira camada que chamamos por MFA.
        - Essa terceira camada chamada MFA gera uma sequência de 6 números, a cada 6 segundos.
            OBS: esse código sempre vai ser enviado através do aplicativo Google Authenticator
            (ou qualquer outro app de autenticação que optarmos) pelo nosso celular ou ipad.

- User { fulano }
- password {  ****  }
- MFA {  6 dígitos  } --> Muda a cada 30 segundos


