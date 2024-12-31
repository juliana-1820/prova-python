# Sistema de Gerenciamento Acadêmico com Django

Este projeto é uma API desenvolvida em Django como parte da prova final da disciplina **Seminário Integralizador III**. Ele representa um sistema de gerenciamento acadêmico, com entidades e funcionalidades organizadas em diferentes **apps**.

## 🛠️ Funcionalidades

O sistema foi estruturado em diferentes **apps**, cada um representando uma entidade específica:

- **Aluno:** gerenciamento de alunos.
- **Curso:** gerenciamento de cursos oferecidos.
- **Disciplina:** controle das disciplinas disponíveis.
- **Detalhes de Curso/Disciplina/Turma:** com informações adicionais associadas às entidades principais.
- **Professor:** gerenciamento de professores.
- **Turma:** organização de turmas com seus respectivos detalhes.

## 🚀 Etapas de Desenvolvimento

O projeto foi construído seguindo os passos abaixo:
1. Criação do projeto com **Python** e **Django**.
2. Configuração do **Banco SQLite** e criação de um usuário administrativo.
3. Implementação e apresentação dos **apps** e seus modelos no **Django Admin**.
4. Configuração do arquivo de **Serialização (Serializers)** para conversão de dados.
5. Implementação das **Views** para lógica de manipulação de dados.
6. Configuração dos arquivos de **Rotas (urls.py)**.
7. Apresentação da interface navegável do **Django REST Framework** em `http://localhost:8000/api`.

## 🔧 Tecnologias Utilizadas

- **Django Framework**
- **Django REST Framework**
- **Banco de Dados:** SQLite3

## 📂 Estrutura do Projeto

```plaintext
prova2-main/
│
├── aluno/
├── curso/
├── detalhecurso/
├── detalhedisciplina/
├── detalheturma/
├── disciplina/
├── professor/
├── turma/
├── db.sqlite3
└── manage.py
