# Sistema Acadêmico de Estudantes

Projeto desenvolvido em Java para implementação de um sistema acadêmico simples de gerenciamento de estudantes.

## Integrantes 

  - Breno Souza
  - Caio Simão
  - Cleyton Ferreira
  - Hitaro Ramos
  - Ricardo Roque

## Sobre o projeto

O sistema permite realizar operações básicas de cadastro e gerenciamento de estudantes através de um menu executado no terminal.

Cada estudante possui informações como:

- Nome;
- CPF;
- Matrícula;
- Curso;
- Semestre.

O projeto utiliza conceitos de Programação Orientada a Objetos, como herança, classe abstrata, interface e encapsulamento.

## Funcionalidades

O sistema possui as seguintes opções:

| Opção | Funcionalidade |
|---|---|
| 1 | Cadastrar estudante |
| 2 | Buscar estudante por matrícula |
| 3 | Listar todos os estudantes |
| 4 | Editar estudante |
| 5 | Excluir estudante |
| 0 | Sair do sistema |

### Cadastro

Permite cadastrar um estudante informando:

- Nome;
- CPF;
- Matrícula;
- Curso;
- Semestre.

### Busca

Permite pesquisar um estudante utilizando sua matrícula.

### Listagem

Exibe os estudantes cadastrados, apresentando matrícula, nome e curso.

### Edição

Permite alterar os dados de um estudante a partir da sua matrícula.

### Exclusão

Permite remover um estudante utilizando sua matrícula.

## Estrutura do projeto

```text
SistemaAcademico/
├── Main.java
├── Pessoa.java
├── Estudante.java
├── Faculdade.java
├── Ipersistencia.java
├── README.md
└── .gitignore
