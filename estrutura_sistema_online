CREATE TABLE Usuarios (
  usuario_id INT PRIMARY KEY,
  nome VARCHAR(150) NOT NULL,
  email VARCHAR(150) NOT NULL,
  data_cadastro DATE NOT NULL
);
CREATE TABLE Professores (
  professor_id INT PRIMARY KEY,
  nome VARCHAR(150) NOT NULL,
  especialidade VARCHAR(100) NOT NULL,
  salario_base DECIMAL(10,2)
);
CREATE TABLE Cursos (
  curso_id INT PRIMARY KEY,
  titulo VARCHAR(255) NOT NULL UNIQUE,
  descricao TEXT,
  carga_horaria INT,
  data_lancamento DATE
);
CREATE TABLE Aulas (
  aula_id INT PRIMARY KEY,
  titulo_aula VARCHAR(255) NOT NULL,
  duracao_minutos INT NOT NULL,
  tipo_conteudo VARCHAR(50)
);

ALTER TABLE Professores
ADD COLUMN email_corporativo VARCHAR(150);

ALTER TABLE Cursos
MODIFY COLUMN carga_horaria DECIMAL(10,2);

DROP TABLE Aulas;

CREATE TABLE Aulas (
  aula_id INT PRIMARY KEY,
  titulo_aula VARCHAR(255) NOT NULL,
  duracao_minutos INT NOT NULL,
  tipo_conteudo VARCHAR(50)
);
