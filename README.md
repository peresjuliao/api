# Voll.med API

## Descrição
Esta é a API Rest da aplicação Voll.med, desenvolvida com Spring Boot para fornecer serviços RESTful.

## Configuração do Projeto

### Spring Initializr
O projeto foi criado usando o [Spring Initializr](https://start.spring.io/), que gera uma estrutura inicial para aplicações Spring Boot.

### Detalhes do Projeto
- **Maven Project**: selecionado
- **Language**: Java
- **Spring Boot**: 3.0.0

### Metadados do Projeto
- **Group**: `med.voll`
- **Artifact**: `api`
- **Name**: `api`
- **Description**: API Rest da aplicação Voll.med
- **Package name**: `med.voll.api`
- **Packaging**: Jar
- **Java**: 17

### Dependências
As seguintes dependências foram incluídas no projeto:
- **Spring Boot DevTools**: Para reinicialização automática da aplicação a cada alteração no código.
- **Lombok**: Para simplificação e redução da verbosidade do código através de anotações.
- **Spring Web**: Necessário para desenvolvimento de APIs RESTful.

### Geração e Importação do Projeto
1. Acesse o [Spring Initializr](https://start.spring.io/), preencha os campos necessários e clique em "Generate" para baixar o projeto.
2. Extraia o arquivo `api.zip` para um diretório de sua escolha.
3. Importe o projeto na sua IDE preferida para iniciar o desenvolvimento.

## Estrutura do Projeto
O projeto possui uma estrutura organizada, criada automaticamente pelo Spring Initializr, facilitando o desenvolvimento e a manutenção.

## Executando a Aplicação
Para executar a aplicação localmente, utilize a sua IDE ou o comando Maven:
```sh
./mvnw spring-boot:run
