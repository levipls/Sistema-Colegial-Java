# 🏫 Sistema Colegial em Java

Este projeto foi desenvolvido como parte da disciplina de **Programação Orientada a Objetos (POO)** na faculdade. Ele simula um sistema colegial simples, com funcionalidades voltadas para o cadastro de alunos e professores, gerenciamento de notas e frequências, e autenticação básica via arquivos CSV.

---

## 📚 Funcionalidades

- Cadastro de **alunos** e **professores**
- Registro e consulta de **notas** e **frequência**
- Validação de **login** por ID e senha
- Persistência de dados em **arquivo CSV**
- Interface baseada em **JOptionPane** (GUI simples)

---

## 🧩 Estrutura do Projeto

```plaintext
├── main.java              # Classe principal (entrada do sistema)
├── aluno.java             # Classe que representa o aluno (extends pessoas)
├── professor.java         # Classe que representa o professor (extends pessoas)
├── pessoas.java           # Classe base com atributos comuns (ID, nome, senha)
├── addAlunos.java         # Tela de adição de alunos (GUI)
├── addAlunosAux.java      # Lógica auxiliar para cadastro
├── verificador.java       # Interface para verificação de cadastro
├── verificadorAux.java    # Implementação da verificação de arquivo
├── dadosContas.csv        # Arquivo onde os dados dos usuários são armazenados
├── poo.iml                # Arquivo de projeto do IntelliJ IDEA
