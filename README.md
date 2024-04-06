### Projeto SpringBoot Web Swagger 🚀

Este é um modelo de projeto para um serviço da web baseado em REST, utilizando o framework Spring Boot e integrado com o Swagger para documentação da API.

#### Tecnologias Utilizadas 💻

- **Spring Boot:** Framework Java para criar aplicativos de forma rápida e com pouca configuração.
- **Swagger:** Ferramenta para documentação de APIs RESTful, facilitando o entendimento e a interação com os endpoints.
- **Maven:** Gerenciador de dependências e construção de projetos.
- **Java 8:** Versão do Java utilizada no projeto.
  
#### Descrição 📝

Este projeto utiliza o Spring Boot Starter Parent na versão 2.5.4 como ponto de partida, fornecendo um conjunto de dependências e configurações padrão para aplicativos Spring Boot. Ele apresenta uma estrutura simples de diretórios e arquivos, seguindo as convenções do Spring Boot.

#### Funcionalidades 🛠️

- **Spring Boot Starter Web:** Fornece as dependências necessárias para criar aplicativos da web com o Spring Boot.
- **Spring Boot Starter Test:** Dependência para testes unitários e de integração com o Spring Boot.
- **Swagger 2:** Inclui as dependências do Swagger para gerar a documentação da API e a interface do usuário.

	<!-- SWAGGER DOCUMENTACAO -->
		<dependency>
			<groupId>io.springfox</groupId>
			<artifactId>springfox-swagger2</artifactId>
			<version>2.9.2</version>
		</dependency>


  ![image](https://github.com/wandrad3/springboot-api-swagger/assets/59511225/75d68646-8639-4a29-9ac6-d691e556e21a)

#### Como Executar 🏃‍♂️

Para executar o projeto, você pode utilizar a IDE de sua preferência, como IntelliJ IDEA ou Eclipse, e executar a classe principal `Application.java`.

#### Documentação da API 📖

Após iniciar o servidor, você pode acessar a documentação da API gerada pelo Swagger em `http://localhost:8080/swagger-ui.html`.

#### Construção do Projeto 🛠️

Este projeto é gerenciado com o Maven. Para construir o projeto, execute o comando abaixo na raiz do projeto:

Aproveite e explore os recursos do Swagger para melhorar a documentação e a interação com a sua API! 🚀
