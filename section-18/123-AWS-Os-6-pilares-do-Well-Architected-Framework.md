# Os 6 Pilares do AWS WELL ARCHITECTD FRAMEWORK

    --> Estrutura criada pela AWS para ajudar na construção de infraestruturas e aplicações cada vez mais seguras, eficientes e escaláveis.

## 1 - Excelência operacional: 
 - Monitorar
    - Resumindo: Tudo que você conseguir monitorar para qualquer tipo de falha ou melhorar todo processo, isso será uma **excelência operacional**.

## 2 - Segurança:
 - Proteger todos os:
   - Dados
   - Sistemas
   - Ativos
     - **essa segurança pode ser feita utilizando os Security Groups, ACL, AWS Keymanagement System, AWS IAM.**

## 3 - Confiabilidade:
 - Manter tudo funcionando:
   - funcionando mesmo que ocorra uma falha (redundância).
     - Exemplo 1: Manter a estrutura em **AZ (Availability Zones)** diferentes. Ou seja, manter em múltiplas zonas de disponibilidade. Garantindo assim a alta disponibilidade.
     - Exemplo 2: Usar o serviço **Route 53**

## 4 - Eficiência e performance:
 - Não gastar recursos acima daquilo que é necessário:
   - Exemplo 1: quando temos instâncias EC2 que estão tendo pouco tráfego, mas que apresentam um recurso muito alto, podemos resolver isso com **Autoscaling** para subir e descer o número de instâncias de acordo com a necessidade vigente. Ou implementando o cache de dados com o **Elastic Cache**.

## 5 - Otimização de custos:
 - Quanto menos gastar, melhor (mantendo a qualidade):
   - Exemplo 1: Temos um servidor EC2 crucial para a empresa, onde sabemos que ele precisará ficar ligado sempre (sempre mesmo). Sabendo disso, ao invés de utilizarmos a instância no regime On Demand, que é bem mais caro, podemos utilizar no regime Reserved Instance, que é bem mais barato.

## 6 - Sustentabilidade:
 - Foca em redusir o impacto ambientalÇ
   - reduzir consumo de energia
   - regiões que utilizam mais energia limpa.