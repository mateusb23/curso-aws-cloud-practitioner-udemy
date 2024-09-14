# IAM   (Identity and Access Management)

 - ***Gerencia acesso aos recusos da AWS***
   - usuários
   - grupos de usuários
   - funções
   - políticas
   - provedores de identidade
   - configurações de conta
   - E muito mais
  
 - ***AWS Account (Root)***
   - cria ***usuários*** (exemplos):
     - marcos
       - pertence ao grupo Admin
     - alice
       - pertence ao grupo Admin
     - joão
       - pertence ao grupo Developer
     - andré
       - pertence aos grupos Admin e Developer
   - cria ***grupos*** (exemplos):
     - group Admin
       - grupo com acesso aos serviços EC2 e S3
     - group Developer
       - grupo com acesso ao serviço Lambda
   - cria ***roles*** (roles não emitem permissões a usuários, mas sim a serviços) (exemplos):
     - Temos um servidor windows no serviço EC2 que precisa acessar arquivos que estão dentro
       do sistema de armazenamento de um Storage no serviço S3. A partir disso, damos acesso 
       a essa máquina no serviço EC2 para acessar os arquivos que estão no storage no serviço S3.
    

OBS: A senhas dos usuários que foram criados:
    - marcos: M@rcos2024
    - alice: Alic&2024
    - joão: Jo@o2024
