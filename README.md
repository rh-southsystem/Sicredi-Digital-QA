## Desafio Automação de Testes - API
Este é o documento com as orientações do desafio de automação da API que
está neste repositório.

#### O que você deve fazer:
- Primeiro você deve clonar a aplicação back-end contida neste repositório e executá-la, conforme
orientações abaixo, pois utilizaremos ela como alvo dos nossos testes. (tópico “Como executar
a aplicação”)
- Segundo você deverá criar um projeto baseado em Maven na sua IDE desenvolvimento
favorita utilizando a linguagem de programação Java.
- Terceiro você deverá realizar a leitura das regras listadas abaixo e elaborar seus
cenários de testes. (tópico “Regras”)
- Quarto você deverá realizar a automação dos testes dos cenários a serem cobertos
conforme sua escolha.

#### Forma de Entrega
Você deverá comitar em seu Gitlab pessoal o projeto de teste automatizado em um
projeto Privado adicionando o usuário “sicredi_user” como “developer. (Para realizar isso
basta acessar o menu Settings -> Members, procurar por “sicredi_owner” e adicionar ao
projeto)

#### Requisitos
- Java 8+ JDK deve estar instalado
- Maven deve estar instalado e configurado no path da aplicação

- Como executar a aplicação:
Na raiz do projeto, através de seu Prompt de Commando/Terminal/Console execute o
comando
mvn clean spring-boot:run
A aplicação estará disponível através da URL http://localhost:8080
Você pode trocar a porta da aplicação, caso a 8080 já estiver em uso, adicionando a
propriedade JVM server.port.
mvn clean spring-boot:run -Dserver.port=8888

#### Documentacão técnica da aplicação
A documentação técnica da API está disponível através do OpenAPI/Swagger em
http://localhost:8080/swagger-ui.html
