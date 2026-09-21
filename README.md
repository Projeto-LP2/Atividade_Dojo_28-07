# Sistema Acadêmico de Estudantes

A atividade desenvolvida para disciplina de **Linguagem de Programação II (LP2)**.

## Sobre a atividade

O sistema permite cadastrar, buscar, listar, editar e excluir estudantes através de um menu no terminal.

Cada estudante possui:

- Nome;
- CPF;
- Matrícula;
- Curso;
- Semestre.

O projeto utiliza conceitos de Programação Orientada a Objetos, como herança, classe abstrata, interface e encapsulamento.

## Funcionalidades

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

Exibe os estudantes cadastrados.

### Edição

Permite alterar os dados de um estudante através da matrícula.

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
```

## Classes

### Main.java

Classe principal do programa. É responsável pelo menu e pela interação com o usuário.

### Pessoa.java

Classe abstrata que possui os atributos:

- Nome;
- CPF.

### Estudante.java

Representa o estudante e herda os atributos da classe `Pessoa`.

Possui também:

- Matrícula;
- Curso;
- Semestre.

### Faculdade.java

Responsável pelo gerenciamento dos estudantes.

Utiliza um `ArrayList` para armazenar os estudantes e possui operações para:

- Incluir;
- Excluir;
- Pesquisar;
- Listar;
- Editar.

### Ipersistencia.java

Interface que define as operações de gerenciamento dos estudantes:

- `incluir()`;
- `excluir()`;
- `pesquisar()`;
- `lista()`;
- `editar()`.

## Tecnologias utilizadas

- Java;
- Programação Orientada a Objetos;
- `ArrayList`;
- `Scanner`;
- Herança;
- Classe abstrata;
- Interface;
- Encapsulamento.

## Como executar

### Requisito

É necessário ter o Java instalado.

Para verificar:

```bash
java -version
```

### Compilar

Abra o terminal na pasta do projeto e execute:

```bash
javac *.java
```

### Executar

Depois da compilação:

```bash
java Main
```

## Menu do sistema

Ao iniciar o programa, será apresentado o seguinte menu:

```text
--- SISTEMA ACADÊMICO DE ESTUDANTES ---

1. Cadastrar Estudante
2. Buscar Estudante por Matrícula
3. Listar todos os Estudantes
4. Editar Estudante
5. Excluir Estudante
0. Sair
```

## Armazenamento dos dados

Os estudantes são armazenados em memória utilizando um `ArrayList`.

Os dados não são armazenados permanentemente em um banco de dados ou arquivo. Ao encerrar o programa, os dados cadastrados são perdidos.

## Objetivo

O projeto tem como objetivo praticar conceitos de Programação Orientada a Objetos em Java, incluindo:

- Herança;
- Abstração;
- Interfaces;
- Encapsulamento;
- Coleções;
- Cadastro;
- Consulta;
- Edição;
- Exclusão de dados.
