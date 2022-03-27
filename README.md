# Agenda
Manipulação do Banco de Dados "teste_db", tabela "agenda":

CREATE TABLE 'agenda' (
'codigo' int(11) NOT NULL AUTO_INCREMENT,
'nome' varchar(100) DEFAULT NULL,
'telefone' varchar(50) DEFAULT NULL,
'email' varchar(100) NOT NULL,
PRIMARY KEY ('codigo')
);
INSERT INTO 'agenda' ('codigo', 'nome', 'telefone', 'email') VALUES
(1, 'Marcos,' '(99)99999-9999', 'marcos@gmail.com'),
(2, 'Ana', '(88) 88888-8888', 'ana@hotmail.com'),
(3, 'Paulo'; '(77)77777-7777', 'paulo@gmail.com'),
(4, 'Maria'; '(66)66666-6666', 'maria@gmail.com');
