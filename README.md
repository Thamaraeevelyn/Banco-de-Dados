# Banco-de-Dados
## Projeto Individual - Módulo 4 Sistema Resília
Projeto Baseado em Modelagem de Banco de Dados contendo Entidades e Atributos.

## Modelo conceitual 

![Modelo_Conceitual](https://user-images.githubusercontent.com/112868695/213471566-d199f2ad-b721-4728-862f-357cbfe632c3.png)

## Modelo lógico

![modelo_Logico (2)](https://user-images.githubusercontent.com/112868695/213471613-e24b3050-8ba3-4e16-bfa3-b7ecf2e136de.png)


- Existem outras entidades além das exigidas ?


Sim,mais duas entidades: Disciplina e Professor

- Quais são os principais Campos e tipos?


Int
Varchar
Date

curso(Cod_Curso(PK), Nome, Tipo 
aluno (Cod_Aluno, Matricula, Nome, Endereco, Tel)
turma (Cod_Turma,Cod_Aluno(FK) Cod_disc (FK), Cod_Curso(FK),Data_Inicio
disciplina (Cod_Disc (PK),Ementa,Cont_Prog,Cod_Prof(Fk)) professor (Cod_Prof(PK), Nome, Sexo, Especialidade)

- Como Estão Relacionadas?


curso(Cod_Curso(PK), Nome, Tipo 
aluno (Cod_Aluno, Matricula, Nome, Endereco, Tel)
turma (Cod_Turma,Cod_Aluno(FK) Cod_disc (FK), Cod_Curso(FK),Data_Inicio
disciplina (Cod_Disc (PK),Ementa,Cont_Prog,Cod_Prof(Fk)) professor (Cod_Prof(PK), Nome, Sexo, Especialidade)



## :hammer_and_wrench: Ferramentas utilizadas
- Mysql Workbench 
- XAMPP
- Apache
- App.diagrams (construção do Diagrama) 
- Git e Github
