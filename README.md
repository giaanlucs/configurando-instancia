# configurando-instancia

# Desafio: Configuração de uma Instância de Banco de Dados no Microsoft Azure

## 💡 Objetivo

Este repositório foi criado como parte de um desafio prático da plataforma DIO. O foco desta atividade é a configuração de uma instância de banco de dados na nuvem utilizando o **Microsoft Azure**, além da documentação da experiência com resumos, anotações e dicas. O conteúdo deste repositório visa auxiliar nos estudos e servir como material de referência para futuras implementações em projetos reais.

## 🎯 Objetivos de Aprendizagem

Ao concluir este desafio, os seguintes objetivos foram alcançados:

- Aplicação prática dos conceitos aprendidos em aula, diretamente no ambiente Azure;
- Registro e documentação técnica de maneira clara e organizada;
- Utilização do GitHub como repositório técnico para compartilhamento de conhecimento.

## 🛠️ Etapas Realizadas

### 1. Acesso e Preparação no Azure

- Acesso ao [Azure Portal](https://portal.azure.com/);
- Navegação até a opção **"SQL databases"** ou **"Instâncias Gerenciadas de SQL"**;
- Criação de um **grupo de recursos** e definição do nome da instância.

### 2. Criação da Instância do Banco de Dados

- Escolha do tipo de banco de dados: **Azure SQL Database (Single ou Gerenciado)**;
- Definição de configurações como:
  - Nome do servidor lógico;
  - Nome de usuário e senha para autenticação SQL;
  - Localização (região do datacenter);
  - Camada de desempenho (vCore ou DTU);
- Habilitação do firewall para acesso público e liberação do IP local.

### 3. Testes e Validação

- Acesso ao banco de dados por meio do **Azure Query Editor** (dentro do portal);
- Testes de conexão utilizando ferramentas externas, como **SQL Server Management Studio (SSMS)** ou **Azure Data Studio**;
- Criação de tabelas e execução de comandos SQL para validar o funcionamento da instância.


## 📚 Recursos Úteis

- [Documentação Oficial: Criar Instância Gerenciada de SQL no Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/sql-managed-instance-get-started)
- [Guia Markdown GitHub](https://www.markdownguide.org/basic-syntax/)
- [Documentação GitHub](https://docs.github.com/pt)

## ✅ Conclusão

A atividade proporcionou uma ótima introdução ao gerenciamento de bancos de dados na nuvem. Com o uso do Azure SQL Database, foi possível configurar uma instância funcional, compreender o modelo de acesso seguro e utilizar ferramentas externas para gerenciamento de dados. Esta documentação serve como apoio prático e teórico para desenvolvedores que desejam iniciar na utilização de bancos de dados na nuvem.

📌 **Dica**: Pratique a automatização da criação de instâncias com **Azure CLI** ou **PowerShell** para maior eficiência em ambientes de produção.
