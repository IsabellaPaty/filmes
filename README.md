1- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO = 'SÉRIE'
2- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO = 'SÉRIE' ORDER BY NOME ASC
3- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO = 'SÉRIE' ORDER BY NOME DESC
4- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO = 'FILME'
5- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO = 'FILME'AND ANO_LANCAMENTO < 2000
6- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO = 'SERIE'AND ANO_LANCAMENTO > 2015
7- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO = 'FILME' AND GENERO LIKE 'Ação%' ORDER BY GENERO
8- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO = 'FILME' AND DURACAO_MINUTOS > 120
9- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO = 'SÉRIE' AND ANO_LANCAMENTO >= 2012 AND  ANO_LANCAMENTO <= 2016 ORDER BY ANO_LANCAMENTO, NOME;
10- SELECT * FROM `ENTRETERIMENTO` WHERE TIPO="Filme" AND ATOR_PRINCIPAL="Brad Pitt " ORDER BY ANO_LANCAMENTO ASC;
11- SELECT NOME, DIRETOR, ATOR_PRINCIPAL FROM ENTRETERIMENTO WHERE GENERO LIKE '%crime%' AND ATOR_PRINCIPAL = 'John Travolta';
12- 
13- SELECT * FROM ENTRETERIMENTO WHERE GENERO NOT LIKE '%comédia%' AND GENERO NOT LIKE '%drama%';
14- SELECT * FROM `ENTRETERIMENTO` WHERE ANO_LANCAMENTO NOT IN (2000, 2001, 2002); 
15- SELECT * FROM ENTRETERIMENTO WHERE ATOR_PRINCIPAL IN ('Wagner Moura', 'Leonardo DiCaprio', 'Keanu Reeves');
