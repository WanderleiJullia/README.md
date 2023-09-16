# README.md
# Lista de Exercicios, Códigos e Diagramas AC1. 

# Sobre o projeto

O projeto tem o objetivo principal de exibir os códigos e diagramas, que foram utilizados para, demonstrar oito situações dessemelhantes. 

Os diagramas consiste em, obter uma melhor visualização de um projeto futuro, tornando os dados mais acessivel e compreensivel para todos os envolviodos. 

## Exercicio 1 (Diagrama: Alunos)

Possui o objetivo de armazenamento de dados dos alunos.

![Alunos](https://github.com/WanderleiJullia/README.md/assets/144744092/6bb18510-327f-449e-a88f-f34f24ba7a7d)

  #### Código: 
  
    create table Alunos(
  
    Nome varchar (50),
    RA int,
    Data_Nasc date, 
    Email varchar (50),
    Endereco varchar (50)
    );
  
    INSERT INTO Alunos (Nome, RA, Data_Nasc, Email, Endereco) VALUES('Jullia', '123456', '2005-02-18', 'Julliawanderlei@gmail.com', 'Rua Washington Pensa');
    INSERT INTO Alunos (Nome, RA, Data_Nasc, Email, Endereco) VALUES('Guilherme', '321456', '2003-07-18', 'Guilherme@gmail.com', 'Rua laurinha matttos');
    INSERT INTO Alunos (Nome, RA, Data_Nasc, Email, Endereco) VALUES('Maria', '123658', '1973-05-30', 'Maria@gmail.com', 'Rua da penha');
    INSERT INTO Alunos (Nome, RA, Data_Nasc, Email, Endereco) VALUES('Claudia', '789456', '2002-02-02', 'Claudia@gmail.com', 'Rua Mariafifi');
    INSERT INTO Alunos (Nome, RA, Data_Nasc, Email, Endereco) VALUES('Roberto', '785632', '2007-09-30', 'Roberto@gmail.com', 'Rua claudio');
  
  

## - Exercicio 2 (Diagrama: Colaborador) 
Armazenamentos de colaboradores de uma empresa. 

![Colaboradores](https://github.com/WanderleiJullia/README.md/assets/144744092/8924dc66-0493-4913-bbb7-923983abe817)

#### Código: 

    create table Colaboradores (
    
    Nome varchar(150),
    ID int,
    CPF varchar (150),
    Cargo varchar (150),
    Salario float
    
    );
    
    insert into Colaboradores (Nome, ID, CPF, Cargo, Salario) Values ('Camila', '1234', '02356978966', 'Produção', '4.896');
    insert into Colaboradores (Nome, ID, CPF, Cargo, Salario) Values ('Paula', '4567', '78945612300', 'RH', '8.965');
    insert into Colaboradores (Nome, ID, CPF, Cargo, Salario) Values ('Pedro', '8910', '12345678999', 'TI', '1.8965');
    insert into Colaboradores (Nome, ID, CPF, Cargo, Salario) Values ('Bruna', '1112', '74185296300', 'Vendas', '1.236');
    insert into Colaboradores (Nome, ID, CPF, Cargo, Salario) Values ('Luana', '1314', '96385274111', 'Limpeza', '7.896');

   

## - Exercicio 3 (Diagrama: Biblioteca)
Controle de Registro de Autores e Livros. 

![Biblioteca](https://github.com/WanderleiJullia/README.md/assets/144744092/356ad415-c605-4c9e-8fdc-62d923c7e1e3)

#### Código:

    create table Livros( 
    Titulo varchar(80),
    Quan_pag int, 
    Acabamento varchar(80), 
    Editora varchar(100)
    );
    
    insert into Livros (Titulo, Quan_pag, Acabamento, Editora) values ('A seleção', '200', 'Flexivel', 'Pearson');
    insert into Livros (Titulo, Quan_pag, Acabamento, Editora) values ('After', '280', 'Canoa', 'Grupo Planeta');
    insert into Livros (Titulo, Quan_pag, Acabamento, Editora) values ('A garota do Lago', '300', 'wire', 'Bertelsmann');
    insert into Livros (Titulo, Quan_pag, Acabamento, Editora) values ('Elite', '140', 'Hardbanck', 'Hachette Livre');
    insert into Livros (Titulo, Quan_pag, Acabamento, Editora) values ('A Escolha', '400', 'Hardcover', 'Wolters Kluwer');
    
    select * from Livros; 
    
    
    
    create table Autores(
    
    Nome varchar(80),
    Data_nasc date, 
    Nacionalidade varchar (80),
    Email varchar (50)
    ); 
    
    insert into Autores (Nome, Data_nasc, Nacionalidade, Email) values ('Sabrina', '2003-05-18', 'Brasileira', 'Sabrina@gmail.com');
    insert into Autores (Nome, Data_nasc, Nacionalidade, Email) values ('Paula ', '2000-07-20', 'Brasileira', 'Paula@gmail.com');
    insert into Autores (Nome, Data_nasc, Nacionalidade, Email) values ('Elena', '2002-09-18', 'Brasileira', 'Elena@gmail.com');
    insert into Autores (Nome, Data_nasc, Nacionalidade, Email) values ('Madalena', '1999-12-18', 'Brasileira', 'Elena@gmail.com');
    insert into Autores (Nome, Data_nasc, Nacionalidade, Email) values ('Angela', '1974-05-18', 'Brasileira', 'Angela@gmail.com');

## - Exercicio 4 (Diagrama: Automóveis) 
Controle de locadora. 

![Automoveis](https://github.com/WanderleiJullia/README.md/assets/144744092/6c9c1de1-8d30-4a54-8803-7772ea14fe1a)

#### Código: 

    create table Automoveis(
    Nome_Monta varchar(200),
    Site varchar(200),
    Logotipo varchar(200),
    Placa varchar (200),
    Modelo varchar (200),
    Ano int
    );
    
    insert into Automoveis (Nome_Monta, Site, Logotipo, Placa, Modelo, Ano) values ('Toyota', 'Toyota.com', 'Toyota', 'WFV6321', 'Corolla', '2023');
    insert into Automoveis (Nome_Monta, Site, Logotipo, Placa, Modelo, Ano) values ('Volkswagen ', 'Volkswagen .com', 'Volkswagen ', 'JVK2023', 'Nivus', '2023');
    insert into Automoveis (Nome_Monta, Site, Logotipo, Placa, Modelo, Ano) values ('Mercedes-Benz', 'Mercedes-Benz.com', 'Mercedes', 'MCN2364', 'A200', '2020');
    insert into Automoveis (Nome_Monta, Site, Logotipo, Placa, Modelo, Ano) values ('BMW Group ', 'BMW.com', 'BMW', 'AEA1236', 'X3', '2023');
    insert into Automoveis (Nome_Monta, Site, Logotipo, Placa, Modelo, Ano) values ('Honda Motor', 'Honda Motor.com', 'Honda', 'JGT789', 'Civic', '2020');


## - Exercicio 5 (Diagrama: Produto) 
Cadastro de produtos para supermercado.

![Produto](https://github.com/WanderleiJullia/README.md/assets/144744092/b57bf854-9678-4094-86d7-58acc6be82c4)

#### Código: 

    create table Supermercado(
    Nome varchar(100),
    Preço decimal (200),
    Quant_Estoq int, 
    Nome_Marca varchar(100),
    SAC varchar(2000),
    Nacionalidade varchar(2000)
    );
    
    insert into Supermercado (Nome, Preço, Quant_Estoq, Nome_Marca, SAC, Nacionalidade) values ('Achocolatado', '7.15', '80', 'Nescau', '0800-580', 'Brasil');
    insert into Supermercado (Nome, Preço, Quant_Estoq, Nome_Marca, SAC, Nacionalidade) values ('Macarrão instantanel ', '5.80', '120', 'Nissin', '0800-777', 'Brasil');
    insert into Supermercado (Nome, Preço, Quant_Estoq, Nome_Marca, SAC, Nacionalidade) values ('Chocolate', '18.90', '40', 'Ferrero Rocher ', '0800-453', 'Italia');
    insert into Supermercado (Nome, Preço, Quant_Estoq, Nome_Marca, SAC, Nacionalidade) values ('Café', '11.88', '60', 'Tres corações ', '0800-973', 'Brasil');
    insert into Supermercado (Nome, Preço, Quant_Estoq, Nome_Marca, SAC, Nacionalidade) values ('Leite', '9.23', '88', 'Pirancajunba', '0800-236', 'Brasil');
    

## - Exercicio 6 (Diagrama: Games) 
Controle para produtora de games. 

![Games](https://github.com/WanderleiJullia/README.md/assets/144744092/1e9a0b28-d675-4cfa-b33c-0fea2a9f40e6)

#### Códigos: 

    create table Projetos ( 
    Nome varchar(80),
    Data_Lan date, 
    Genero varchar (80),
    FaixaEtaria varchar(80)
    ); 
    
    insert into Projetos (Nome, Data_Lan, Genero, FaixaEtaria) Values ('GTA', '2013-09-17', 'Acão', '18');
    insert into Projetos (Nome, Data_Lan, Genero, FaixaEtaria) Values ('Forza', '2005-05-03', 'Acão', '18'); 
    insert into Projetos (Nome, Data_Lan, Genero, FaixaEtaria) Values ('Call of duty', '2003-10-29', 'Ação', '18');
    insert into Projetos (Nome, Data_Lan, Genero, FaixaEtaria) Values ('Resident Evil', '2002-03-22', 'Acão', '18');
    insert into Projetos (Nome, Data_Lan, Genero, FaixaEtaria) Values ('God of war', '2018-04-20', 'Ação', '18'); 
    
    select * from Projetos; 
    
    Desevolvedores 
    
    create table Desenvolvedores(
    Nome varchar(80),
    CPF varchar(80),
    Data_Nasc date
    );
    
    insert into Desenvolvedores (Nome, CPF, Data_Nasc) values ('Ricardo', '12365478900', '2003-08-18');
    insert into Desenvolvedores (Nome, CPF, Data_Nasc) values ('Paulo', '78945612300', '1999-02-22');
    insert into Desenvolvedores (Nome, CPF, Data_Nasc) values ('Sabrina', '74185296300', '2000-08-20');
    insert into Desenvolvedores (Nome, CPF, Data_Nasc) values ('Bruno', '36985214700', '2001-09-10');
    insert into Desenvolvedores (Nome, CPF, Data_Nasc) values ('Gabrila', '45612378900', '2002-11-10');

    
## - Exercicio 7 (Diagrama: Pet Shop) 
Um PetShop deseja manter cadastrado seus clientes como seus pets. 

![Pet Shop](https://github.com/WanderleiJullia/README.md/assets/144744092/10b3495f-951a-454a-8b27-31312838383a)

#### Códigos: 

    create table Clientes (
    Nome varchar(50),
    CPF varchar(11),
    Email varchar(50),
    TEL varchar(30)
    );
    
    insert into Clientes (Nome, CPF, Email, TEL) Values ('Jullia', '12345678900', 'Julliawanderlei@gamil.com', '15973735098');
    insert into Clientes (Nome, CPF, Email, TEL) Values ('Paulo', '78945612300', 'Paulo@gamil.com', '15960778954');
    insert into Clientes (Nome, CPF, Email, TEL) Values ('Andre', '45612378900', 'Andre@gamil.com', '15945184046');  
    insert into Clientes (Nome, CPF, Email, TEL) Values ('Sergio', '14785296300', 'Sergio.gmail.com', '15973735496');
    insert into Clientes (Nome, CPF, Email, TEL) Values ('Paula', '369852147', 'Paula@gmail.com', '15960778564');
    
    select * from Clientes; 
    
    Pet. 
    
    create table PETS ( 
    
    Nome varchar(50),
    Especie varchar (60),
    Nascimento date
    );
    
    insert into PETS (Nome, Especie, Nascimento) values ('Bailey', 'SRD', '2023-09-23');
    insert into PETS (Nome, Especie, Nascimento) values ('Thor', 'SRD', '2023-01-20');
    insert into PETS (Nome, Especie, Nascimento) values ('Belinha', 'SRD', '2020-05-06');
    insert into PETS (Nome, Especie, Nascimento) values ('Esmeralda', 'SRD', '2021-08-23');
    insert into PETS (Nome, Especie, Nascimento) values ('Snoppy', 'SRD', '2023-01-19');



## - Exercicio 8 (Diagrama: Videoteca) 
Uma locadora precisa Registrar algumas informaçoes, para o controle de cada filme. 

![Videoteca](https://github.com/WanderleiJullia/README.md/assets/144744092/26a15177-a01b-4b0a-8159-e16f0f36b8e8)

#### Código: 

    create table Filme(
    Titulo varchar(2000),
    Duração varchar(2000), 
    Idioma varchar(2000),
    Preço decimal
    );
    
    insert into Filme (Titulo, Duração, Idioma, Preço) values ('Alice nos pais das Maravilha', '01:40:00', 'Ingles', '25.00');
    insert into Filme (Titulo, Duração, Idioma, Preço) values ('Moana', '01:25:00', 'Ingles', '17.00');
    insert into Filme (Titulo, Duração, Idioma, Preço) values ('Rapunzel', '01:40:00', 'Ingles', '15.00');
    insert into Filme (Titulo, Duração, Idioma, Preço) values ('IT a coisa ', '02:20:00', 'Ingles', '25.00');
    insert into Filme (Titulo, Duração, Idioma, Preço) values ('Vingadores', '03:40:00', 'Ingles', '25.00');
    
    select * from Filme; 
    
    create table Elenco(
    Nome varchar (2000),
    Data_Nasc date, 
    Nacionalidade varchar (2000)
    ); 
    
    insert into Elenco (Nome, Data_Nasc, Nacionalidade) values ('Jhonny Depp', '1963-06-09', 'Americano');
    insert into Elenco (Nome, Data_Nasc, Nacionalidade) values ('Dwayne Johnson', '1972-05-02', 'Americano');
    insert into Elenco (Nome, Data_Nasc, Nacionalidade) values ('Luciano Hulk', '1971-09-03', 'Brasileiro');
    insert into Elenco (Nome, Data_Nasc, Nacionalidade) values ('Bill Skarsgård', '1990-08-09', 'Americano');
    insert into Elenco (Nome, Data_Nasc, Nacionalidade) values ('Chris Evans', '1981-06-13', 'Americano');
    
    select * from Elenco; 
    
    create table Diretores(
    Nome varchar (2000), 
    Data_Nasc date, 
    Nacionalidade varchar(2000)
    );
    
    insert into Diretores (Nome, Data_Nasc, Nacionalidade) values ('Tim Burton', '1958-08-25', 'Americano');
    insert into Diretores (Nome, Data_Nasc, Nacionalidade) values ('Ron Clements', '1953-04-25', 'Americano');
    insert into Diretores (Nome, Data_Nasc, Nacionalidade) values ('Nathan Greno', '1975-03-22', 'Americano');
    insert into Diretores (Nome, Data_Nasc, Nacionalidade) values ('Andy Muschietti', '1973-08-26', 'Americano');
    insert into Diretores (Nome, Data_Nasc, Nacionalidade) values ('Joe Russon', '1971-07-18', 'Russo');
    
    select * from Diretores; 
    



# Autor

Jullia Santos Wanderlei 

Bancos de Dados, 15/09/2023


