# Sistema de Gestão de Pessoas

Este repositório contém um sistema simples de gestão de pessoas, incluindo as classes `Pessoa`, `Aluno`, `Professor` e `Funcionario`. O objetivo é demonstrar o uso de herança e encapsulamento em PHP.

## Estrutura do Projeto

### Classes

#### 1. Classe `Pessoa`

A classe `Pessoa` é a classe base que contém atributos e métodos comuns a todas as pessoas.

- **Atributos:**
    - `nome`: Nome da pessoa.
    - `idade`: Idade da pessoa.
    - `sexo`: Sexo da pessoa.

- **Métodos:**
    - `fazerAniversario()`: Aumenta a idade da pessoa em 1.
    - `getNome()`: Retorna o nome da pessoa.
    - `setNome($nome)`: Define o nome da pessoa.
    - `getIdade()`: Retorna a idade da pessoa.
    - `setIdade($idade)`: Define a idade da pessoa.
    - `getSexo()`: Retorna o sexo da pessoa.
    - `setSexo($sexo)`: Define o sexo da pessoa.

#### 2. Classe `Aluno`

A classe `Aluno` estende a classe `Pessoa` e adiciona atributos e métodos específicos para alunos.

- **Atributos:**
    - `matricula`: Número da matrícula do aluno.
    - `curso`: Curso em que o aluno está matriculado.

- **Métodos:**
    - `cancelarMatricula()`: Exibe uma mensagem informando que a matrícula será cancelada.
    - `getMatricula()`: Retorna o número da matrícula.
    - `setMatricula($matricula)`: Define o número da matrícula.
    - `getCurso()`: Retorna o curso do aluno.
    - `setCurso($curso)`: Define o curso do aluno.

#### 3. Classe `Professor`

A classe `Professor` também estende a classe `Pessoa` e inclui atributos e métodos relacionados a professores.

- **Atributos:**
    - `especialidade`: Área de especialização do professor.
    - `salario`: Salário do professor.

- **Métodos:**
    - `receberAumento($aumento)`: Aumenta o salário do professor pelo valor especificado.
    - `getEspecialidade()`: Retorna a especialidade do professor.
    - `setEspecialidade($especialidade)`: Define a especialidade do professor.
    - `getSalario()`: Retorna o salário do professor.
    - `setSalario($salario)`: Define o salário do professor.

#### 4. Classe `Funcionario`

A classe `Funcionario` estende a classe `Pessoa` e adiciona atributos e métodos para funcionários.

- **Atributos:**
    - `setor`: Setor em que o funcionário trabalha.
    - `trabalhando`: Indica se o funcionário está trabalhando (booleano).

- **Métodos:**
    - `mudarTrabalho()`: Alterna o estado do atributo `trabalhando`.
    - `getSetor()`: Retorna o setor do funcionário.
    - `setSetor($setor)`: Define o setor do funcionário.
    - `getTrabalhando()`: Retorna o estado do atributo `trabalhando`.
    - `setTrabalhando($trabalhando)`: Define o estado do atributo `trabalhando`.

## Como Usar

1. **Instalação**: Certifique-se de que o PHP está instalado em sua máquina.
2. **Uso**: Você pode criar instâncias das classes `Aluno`, `Professor` e `Funcionario`, utilizando os métodos disponíveis para gerenciar seus dados.

## Autor
**Feito por Railton Araujo.**

