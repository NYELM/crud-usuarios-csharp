# CRUD de Usuário em C#

Este projeto é um sistema de CRUD de usuários desenvolvido em C# e ASP.NET Core. Ele permite a criação, leitura, atualização e exclusão de usuários, com autenticação baseada em JWT para garantir a segurança das operações.

## Tecnologias Utilizadas

- **Linguagem**: C#
- **Framework**: ASP.NET Core
- **Autenticação**: JWT
- **Banco de Dados**: SQL Server

## Funcionalidades

- **Listar Usuários**: Retorna todos os usuários cadastrados.
- **Cadastrar Usuário**: Cria um novo usuário.
- **Buscar Usuário por ID**: Retorna informações de um usuário específico.
- **Atualizar Usuário**: Atualiza os dados de um usuário.
- **Deletar Usuário**: Exclui um usuário do sistema.
- **Autenticação**: Implementação de autenticação JWT para segurança das operações.

## Estrutura do Projeto

- **Usuario.cs**: Define o modelo de dados do usuário.
- **UsuariosController.cs**: Controlador que gerencia as operações de CRUD e autenticação.
- **Program.cs**: Configurações do aplicativo, incluindo o middleware de autenticação JWT.

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
