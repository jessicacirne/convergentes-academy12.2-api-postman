# Projeto ERP academy - Executando testes de API com Postman

Este projeto contém coleções de testes de API para validar funcionalidades específicas dos recursos "Company" e "User". Abaixo, seguem as instruções para configurar e executar esses testes utilizando o Postman.

## Pré-requisitos

1. **Postman**: Certifique-se de ter o [Postman](https://www.postman.com/downloads/) instalado em sua máquina.
2. **Arquivos Necessários**: Verifique se possui os arquivos JSON das coleções e do ambiente:
   - `Feature - Company.postman_collection.json`
   - `Feature - User.postman_collection.json`
   - `Variáveis.postman_environment.json`
   - `workspace.postman_globals.json` (opcional, para variáveis globais)

## Estrutura do Projeto

- **`Feature - Company.postman_collection.json`**: Coleção de testes para os endpoints relacionados a "Company".
- **`Feature - User.postman_collection.json`**: Coleção de testes para os endpoints relacionados a "User".
- **`Variáveis.postman_environment.json`**: Arquivo de variáveis de ambiente necessário para a execução dos testes.
- **`workspace.postman_globals.json`**: Arquivo de variáveis globais, se aplicável.

## Configuração

### 1. Importação das Coleções e Ambiente
- Abra o Postman e clique em **"Import"** no canto superior esquerdo.
- Selecione os arquivos `Feature - Company.postman_collection.json`, `Feature - User.postman_collection.json`, `Variáveis.postman_environment.json` e `workspace.postman_globals.json` (caso aplicável) e clique em **"Import"**.

### 2. Configuração do Ambiente
- Após a importação, vá até a seção de **"Environments"** e selecione o ambiente **`Variáveis`**.
- Verifique se todas as variáveis (como URLs, tokens de autenticação, etc.) estão corretas e atualizadas. Modifique-as conforme necessário.

## Executando os Testes

### 1. Execução Individual
- Navegue até uma das coleções importadas (`Feature - Company` ou `Feature - User`).
- Selecione a requisição desejada e clique em **"Send"** para enviar a requisição e verificar o resultado da resposta e dos testes.

### 2. Execução Automática de Toda a Coleção
- Selecione uma das coleções e clique em **"Run"** para abrir o **Collection Runner**.
- Escolha o ambiente **`Variáveis`** e ajuste outras configurações, como quantidade de iterações e delay entre as requisições.
- Clique em **"Start Run"** para iniciar a execução da coleção selecionada.

## Resultados e Logs

- No Postman, os resultados dos testes são exibidos no painel de resposta após a execução.