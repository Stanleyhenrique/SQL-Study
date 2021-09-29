create table FILMES(codigo int, filmes varchar(100), ano int, valor float);

insert into FILMES values(324324, 'O sobrevivente', 2006, 23.3);

select codigo,filmes,ano,valor from FILMES;

/////////////////////////////////////////////////////////////////////////////////


create table TIMES(pais varchar(100), nome varchar(100),ano int);

insert into TIMES values('BRASIL', 'SANTA CRUZ', 1914);

select pais,nome,ano from TIMES;

/////////////////////////////////////////////////////////////////////////////////


create table GAMES(nome varchar(100), genero varchar(100), ano int);

insert into GAMES values('LEAGUE OF LEGENDS', 'MOBA', 2009);
insert into GAMES values('Fortnite', 'BATTLE ROYALE', 2017);
insert into GAMES values('FIFA', 'esportes', 2017);

select nome,genero,ano from GAMES;

