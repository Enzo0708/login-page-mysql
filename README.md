# Banco de dados

  create database Login;
  -- --------
  use Login;
  
  -- -----------
  create table Usuários(
  	id int(3) primary key auto_increment,
    email varchar(40),
    senha varchar(12)
  );
  -- -----------
  insert into Usuários(email,senha) VALUES
  ('rafaela@gmail.com',123); -- USUARIO QUE QUISER	
  


  select * from usuários;
