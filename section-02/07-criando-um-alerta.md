## SERVIÇO QUE GERA ALERTAS E MONITORA A MINHA ESTRUTURA CLOUD:
 
---> ***Cloud watch:***
    - é o serviço que monitora as billings.
    - Billing (detro do serviço cloud watch conseguimos acessar a nossa parte de conta. E nessa parte
      de conta conseguimos criar um **alerta**.)
    - No nosso caso criaremos a partir do Cloud watch um alerta de $5 (dólares), onde a ação será enviar através
      de outro serviço chamado **SNS** por e-mail uma notificação.
    - Por padrão, o serviço Cloud watch vem desabilitado para Billing. Então, iremos primeiro habilitá-lo
      para que ele apareça no serviço Cloud watch.
---> ***SNS:***
    - é o serviço que envia mensagem de e-mail.
   