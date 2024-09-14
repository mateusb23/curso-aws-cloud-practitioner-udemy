# Serviço AWS Glue (ETL)

 ---> ***ETL (Extract Transform Load)*** --> intrinsecamente ligado a *Analytics*


  RDS    -------->   Glue    -------> Redshift
  S3
 (EXTRACT)        (TRANSFORM)       (LOAD)


 - Basicamente, o Glue organiza e limpa os dados que podem vir de um S3 ou RDS, por exemplo, e 
   em seguida já faz o load em um readshift, por exemplo.
