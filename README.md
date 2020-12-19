# Guide to use Lombok In Spring Boot

<a href="https://javatodev.com/lombok-spring-boot/" target="blank">
    <img align="center" src="https://javatodev.com/wp-content/uploads/2020/10/Guide-to-use-Lombok-In-Spring-Boot-800x450.png" alt="Guide to use Lombok In Spring Boot"/></a>

<p align="left">
Project Lombok, one of the coolest java library which capable of minimizing your code. This is a plugin that we could configure with your editor and build tools. Then you would not have to worry about writing getters, setters, and much more boilerplate stuff you have to write in java classes. Here I’ll discuss how we can integrate Lombok with a Spring Boot application and ways to get use from it.

Technologies Going to Use,

- Java 1.8
- Spring Boot: 2.3.4.RELEASE
- Lombok
- Gradle
- Intellij Idea for IDE

Main topics I’m going to discuss here,

- How Lombok Works?
- Adding Required Dependencies
- Practical Ways to Use Lombok
    - Using @Getter and @Setter In Lombok
    - @Data for Additional Methods
    - Lombok issue with first char lowerCase and next upperCase
- How to Use Lombok with Spring Boot
    - Constructor Based Dependency Injection Using Lombok @RequiredArgsConstructor
    - @Slf4j in Lombok For Logging
    - Using @Slf4j Inside an Interface
- Conclusion
</p>

📄 Original Tutorial [Guide to use Lombok In Spring Boot](https://javatodev.com/lombok-spring-boot/)

Related Articles 

 - [How to Create a Spring Boot Project](https://javatodev.com/how-to-create-a-spring-boot-project/)
 - [Consuming REST API Using Feign Client in Spring Boot](https://javatodev.com/consuming-rest-api-using-feign-client-in-spring-boot/)
 - [Exception Handling Spring Boot REST API](https://javatodev.com/exception-handling-spring-boot/)
 - [Database Migration Using Flyway in Spring Boot](https://javatodev.com/flyway-spring-boot/)
