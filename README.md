# Desafio---Boocamp-4-edi-o
Desafio BootCamp 4 Edição

## Requisitos

- .NET Framework 4.7.2 ou superior
- Visual Studio 2019 ou uma IDE compatível com C#

## Configuração e Execução

1. Faça o clone deste repositório em sua máquina local.

2. Abra o projeto no Visual Studio ou em sua IDE preferida.

3. Restaure as dependências do projeto executando o comando `dotnet restore` na raiz do projeto.

4. Execute o projeto pressionando F5 ou utilizando o comando `dotnet run` na raiz do projeto.

## Estrutura do Projeto

- `Program.cs`: Arquivo de entrada do programa, responsável por iniciar a aplicação e configurar o host da API.

- `Models/Produto.cs`: Classe que representa o modelo de um produto, com propriedades como ID e nome.

- `Services/ProdutoService.cs`: Classe responsável pela lógica de negócio do CRUD de produtos, contendo métodos para adicionar, remover, editar e visualizar produtos.

- `Controllers/ProdutoController.cs`: Classe que implementa a API REST para realizar as operações de CRUD.

## Exemplos de Uso

Para adicionar um produto, envie uma requisição POST para `/api/produtos` com os dados do produto no corpo da solicitação.

Para remover um produto, envie uma requisição DELETE para `/api/produtos/{id}`, substituindo `{id}` pelo ID do produto que deseja remover.

Para editar o nome de um produto, envie uma requisição PUT para `/api/produtos/{id}`, substituindo `{id}` pelo ID do produto e fornecendo o novo nome no corpo da solicitação.

Para visualizar todos os produtos cadastrados, envie uma solicitação GET para `/api/produtos`.

## Recursos Adicionais

- [Documentação do .NET Framework](https://docs.microsoft.com/pt-br/dotnet/)
- [Exemplo de uso do CRUD em C#](https://github.com/exemplo-crud-csharp)
```

