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

/////////////////////////////////////////////////////////////////////////////////

create table separar(xxx varchar(50));
insert into separar values("-------------------------------");
select * from separar;
create table calc(x int, y int);
insert into calc values (10, 25);
select x,y,(x+y) from calc;

select * from separar;

create table SERIES(nome varchar(100),genero varchar(100),ano int);
insert into SERIES values('BROKYLLYN NINE NINE', 'COMEDIA', 2013);
select nome,genero,ano from series;

select * from separar;

create table ANIMAIS(especie varchar(100));
insert into ANIMAIS values('macaco');
insert into ANIMAIS values('cachorro');
insert into ANIMAIS values('gato');
select especie from ANIMAIS;

