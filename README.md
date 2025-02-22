# PicPay Simplificado - Desafio Backend

Este projeto foi desenvolvido com base no desafio backend do PicPay: Desafio PicPay Backend.

## 🛠 Tecnologias Utilizadas

- **.NET (ASP.NET Core)**
- **SQL Server**
- **Entity Framework (EF Core)**
- **Clean Architecture**
- **Docker**

## 📥 Como baixar e executar o projeto

### 🔽 Clonando o Repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

🐳 Rodando com Docker
```bash
docker-compose up -d
```

▶️ Rodando Manualmente
Certifique-se de ter o .NET 8 SDK e SQL Server instalados.

Configure a string de conexão no appsettings.json.

Execute os seguintes comandos:
```bash
dotnet restore
dotnet ef database update
dotnet run
```
📌 Endpoints Principais
POST /transfer - Realiza transferências entre usuários.
Exemplo de requisição:
```bash
{
  "value": 100.0,
  "payer": 4,
  "payee": 15
}
```
📚 Arquitetura
O projeto segue a Clean Architecture, garantindo modularidade e facilidade de manutenção. 🚀
