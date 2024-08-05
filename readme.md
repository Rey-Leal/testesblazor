# Testes Blazor

![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge)

## Introdução
Este projeto demonstra o acesso a dados em uma base SQL utilizando o Framework NHibernate para o back-end e Blazor para o front-end. Abaixo estão as principais tecnologias usadas neste projeto:

* C#
* Blazor
* NHibernate
* SQL Server

## Blazor
Blazor é uma estrutura de front-end moderna que utiliza HTML, CSS e C# para criar aplicativos web interativos. Ele permite que você escreva código front-end em C# em vez de JavaScript, proporcionando uma experiência de desenvolvimento mais fluida e eficiente para desenvolvedores .NET.

## NHibernate
NHibernate é a implementação para .NET do framework Hibernate do Java. Ele é um dos mais antigos e respeitados ORMs (Object Relational Mapping), facilitando a interação entre a aplicação .NET e o banco de dados SQL Server, gerenciando mapeamentos entre objetos .NET e tabelas do banco de dados.

## Estrutura do Projeto
O projeto está organizado da seguinte forma:
* **Models**: Contém as classes de modelo que representam as tabelas do banco de dados.
* **Data**: Contém a configuração do NHibernate e as classes de repositório para acessar os dados.
* **Mapping**: Contém os arquivos de mapeamentos para cada classe utilizada.
* **Pages**: Contém os componentes Blazor que fornecem a interface do usuário para interagir com os dados.

## Configuração e Execução
Para executar este projeto localmente, siga os passos abaixo:

1. **Clone o repositório**:
   ```bash
   git clone <URL-do-repositorio>
   ```

2. **Navegue até o diretório do projeto**:
   ```bash
   cd nome-do-projeto
   ```

3. **Instale as dependências**:
   Certifique-se de que você tenha o .NET SDK instalado em sua máquina. Instale as dependências com:
   ```bash
   dotnet restore
   ```

4. **Atualize as configurações do banco de dados**:
   No arquivo `appsettings.json`, configure a string de conexão para o seu servidor SQL Server.

5. **Execute as migrações do banco de dados**:
   Configure e aplique as migrações do NHibernate para garantir que o banco de dados esteja atualizado com as últimas mudanças no modelo.

6. **Execute o projeto**:
   ```bash
   dotnet run
   ```