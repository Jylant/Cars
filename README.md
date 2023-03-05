# Cars
Rästitehtävä

create table car(
id_car int primary key auto_increment,
branch varchar(20),
model varchar(20)
);

insert into car(branch,model) values('Toyota','Avensis');
insert into car(branch,model) values('Ford','Focus');
insert into car(branch,model) values('Lada','Samara');
