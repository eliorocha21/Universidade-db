# 🎓 Projeto de Banco de Dados - Universidade

## 📌 Sobre
Projeto de modelagem de banco de dados para um sistema acadêmico de universidade, desenvolvido para praticar conceitos de modelagem Entidade-Relacionamento (ER) e aplicação de regras de negócio.

## 🖼️ Diagrama
![Diagrama Universidade](https://github.com/eliorocha21/Universidade-db/blob/main/univ_refinado.png)

## 🎯 Regras de Negócio
* Pessoas podem ser cadastradas como **Aluno** ou **Professor**;
* Professores estão vinculados a um **Departamento**;
* Alunos podem se matricular em **Cursos** e em **Disciplinas**;
* Cursos pertencem a um **Departamento** e possuem datas de início e término;
* Disciplinas podem ter **pré-requisitos** e são ofertadas em diferentes **períodos** (com datas de início e término);
* Alunos podem participar de atividades de **Extensão**;
* Cada disciplina é ministrada por um professor e pode estar vinculada a vários cursos;
* O relacionamento **Matriculado** registra nota e status (aprovado, reprovado ou cursando);
* O sistema possui controle de acesso via entidade **Usuário**, que pode ser Aluno, Professor ou Admin.

## 🔧 Refinamentos Aplicados
* Entidade **Curso** com atributos de data de início e término;
* Entidade **Período** com atributos de data de início e término;
* Entidade associativa **Matriculado** com nota e status;
* Inclusão da entidade **Usuário** para controle de acesso (Aluno, Professor ou Admin);
* Entidade genérica **Pessoa** para evitar duplicação de dados;
* Especialização em **Aluno** e **Professor**;
* Entidade própria para **Pré-requisitos** das disciplinas;
* Entidade **Oferta de Disciplina** para controlar professor e período;
* Entidade **Extensão** para atividades extracurriculares.

## 🛠️ Ferramentas
* MySQL Workbench  
* MySQL  
* Git & GitHub  

## 🚀 Objetivo
Aplicar conceitos de modelagem de dados em um cenário acadêmico, consolidando conhecimentos de banco de dados e estruturação de regras de negócio em sistemas universitários.

---

### Autor
**Elio Rocha**  
* LinkedIn: [linkedin.com/in/eliorochadata](https://linkedin.com/in/eliorochadata)  
* GitHub: [github.com/eliorocha21](https://github.com/eliorocha21)
