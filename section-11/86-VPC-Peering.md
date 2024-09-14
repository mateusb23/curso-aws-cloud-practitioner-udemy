# VPC Peering

 --> PERGUNTA: 
    Um Host dentro de uma SubNet, que fica dentro de uma VPC 1 consegue acessar um outro host que 
    fica dentro de uma SubNet que fica dentro de uma VPC 2?
        --> Por default não consegue.
        --> Mas conseguimos resolver esse problema criando um ***VPC Peering***, que vai permitir
            que os hosts se falem entre si. O VPC Peering vai ser como uma ponte entre esses dois VPCs.