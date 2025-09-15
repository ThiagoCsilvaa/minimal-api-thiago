# Minimal API - Bootcamp Avanade

Este projeto é um desafio do Bootcamp da Avanade. Trata-se de uma **API minimalista** usando .NET 7 e MySQL.

## Estrutura do Projeto
- `Api/` - Contém a API principal.
- `Test/` - Contém os testes automatizados.
- `appsettings.json` - Configurações de conexão e JWT.
- `minimal-api.sln` - Solução do Visual Studio.

## Tecnologias
- .NET 7
- Entity Framework Core
- MySQL
- JWT Authentication
- Swagger (Swashbuckle)

## Como rodar
1. Restaurar pacotes:
```bash
dotnet restore

2. Construir o projeto:
dotnet build

3. Rodar a API:
dotnet run --project Api

4. Acessar via navegador ou Postman
