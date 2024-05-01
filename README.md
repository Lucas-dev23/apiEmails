# API de Emails

A API de Emails é uma aplicação Spring Boot que oferece funcionalidade de envio de Email. 

## Pré-requisitos

Antes de iniciar, certifique-se de ter os seguintes requisitos instalados:

- Java JDK 17
- Maven
- Spring Boot

## Configurações

No `application.properties`, você encontrará as configurações da porta em que a API está rodando junto com o Email utilizado para envio e sua respectiva senha. Fique à vontade para usar o email de sua preferência, mas o ideal é que seja uma conta Outlook.

## Teste e Documentação da API

Esta API utiliza o Swagger para facilitar o teste e a documentação dos endpoints. Com o Swagger, você pode:

- **Documentação Automática:** Todos os endpoints da API estão documentados automaticamente usando a especificação OpenAPI (anteriormente conhecida como Swagger Specification).
  
- **Interface Interativa (Swagger UI):** Explore e teste os endpoints da API diretamente no seu navegador usando a interface interativa gerada pelo Swagger UI.
  
- **Teste de Funcionalidades:** Além da documentação, você pode testar todas as funcionalidades da API de forma interativa e fácil de usar.

Para acessar a documentação e o Swagger UI, inicie a aplicação e navegue até o seguinte endpoint no seu navegador: http://localhost:8085/swagger-ui/index.html.
