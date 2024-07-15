# Java Spring Professional Desafio: Modelo de domínio e ORM


# Sobre o projeto
Este projeto é o desafio do capítulo sobre Modelo de domínio e ORM do Curso Java Spring Professional da [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").
O desafio consiste em criar um projeto no Spring Boot com Java e banco de dados H2, e implementar o modelo 
conceitual conforme especificação a seguir. Além disso, fazer o seeding da base de dados conforme diagrama de objetos que segue. 



## Especificação e Modelo Conceitual
Sistema Evento: Deseja-se construir um sistema para gerenciar as informações dos participantes das atividades de um 
evento acadêmico. As atividades deste evento podem ser, por exemplo, palestras, cursos, oficinas 
práticas, etc. Cada atividade que ocorre possui nome, descrição, preço, e pode ser dividida em vários 
blocos de horários (por exemplo: um curso de HTML pode ocorrer em dois blocos, sendo necessário 
armazenar o dia e os horários de início de fim do bloco daquele dia). Para cada participante, deseja-se 
cadastrar seu nome e email.

![Modelo Conceitual](https://github.com/GabrielSilva2310/Assets/blob/main/Images%20Modelo%20de%20Dom%C3%ADnio%20e%20ORM/Modelo%20Conceitual.png)


## Diagrama de Objetos

![Diagrama de Objetos](https://github.com/GabrielSilva2310/Assets/blob/main/Images%20Modelo%20de%20Dom%C3%ADnio%20e%20ORM/Diagrama%20de%20Objetos.png)


# Tecnologias utilizadas
- Java 17
- Spring Boot 3
- Maven
- JPA/Hibernate
- H2 Database

# Como executar o projeto

Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/GabrielSilva2310/Spring-Professional-Modelo-de-dominio-e-ORM.git

# entrar na pasta do projeto
cd Spring-Professional-Modelo-de-dominio-e-ORM

# executar o projeto
./mvnw spring-boot:run
```

# Competências avaliadas no desafio
- Implementação de entidades de domínio
- Mapeamento objeto-relacional com JPA
- Setup de projeto Spring Boot para banco H2
- Seeding de base de dados H2

# Autor

Gabriel Da Silva 

www.linkedin.com/in/gabriel-da-silva-457039193
