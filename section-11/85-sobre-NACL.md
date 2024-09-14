# NACL (Network Access List) - Lista de acesso de rede -- ACLs de Rede

 - Está dentro da SubNet, a protegendo.
 - Enquanto já temos o ***Security group*** protegendo as instâncias EC2, por exemplo, como segunda camada
   temos os ***NACL*** protegendo a SubNet onde está essa mesma instância.

## CONCEITO:
 1. É uma lista de regras aonde normalmente você permite tudo que queremos que passe, e nas últimas linhas
   sempre proibimos tudo. 
 2. É como se fosse um Firewall para a SubNet.
 3. A partir do momento em que criamos uma ***VPC***, automaticamente a AWS cria também uma ***ACL***, que
    vai estar lá no painel de VPC --> Segurança --> ACLs da rede

### Dentro da ACL
 1. Regras de Entrada
 2. Regras de Saída