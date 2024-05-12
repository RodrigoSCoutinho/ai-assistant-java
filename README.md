<h1 align="center">
  Spring Boot with Chat GPT
</h1>

<p>
PT-BR | Este projeto tem como objetivo principal o estudo do Spring AI. Estrutura de aplicação para engenharia de IA. Seu objetivo é aplicar ao domínio de IA os princípios de design do ecossistema Spring, como portabilidade e design modular, e promover o uso de POJOs como blocos de construção de uma aplicação para o domínio de IA.
</p>

<p>
ENGLISH-USA | This project's main objective is to study Spring AI. Application framework for AI engineering. Its goal is to apply to the AI domain Spring ecosystem design principles such as portability and modular design and promote using POJOs as the building blocks of an application to the AI domain.
</p>


## Technologies

- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring Data JDBC](https://spring.io/projects/spring-ai)
- [Spring MVC](https://docs.spring.io/spring-framework/reference/web/webmvc.html)


A API poderá ser acessada em [localhost:8081](http://localhost:8081).

## API Endpoints



- GET /reviews
```
http GET :8081

HTTP/1.1 200 OK
Content-Length: 129
Content-Type: application/json

{
    "Dom Quixote",
    "Por favor, me forneça um breve resumo
    do livro {book} e também a biografia do
    seu autor.",
    "book",
}
```

- GET /stream/informations
```
http GET :8081

HTTP/1.1 200 OK
Content-Length: 129
Content-Type: application/json

{
   "Quais são os livros best sellers dos ultimos anos?"
}
```