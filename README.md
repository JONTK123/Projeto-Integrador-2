Título: Projeto Integrador 2 - Desenvolvimento Full-Stack com Node.js, TypeScript, Oracle SQL e Tecnologias Web

ENTREGA 1 - ADM

Introdução:
O Projeto Integrador 2 incorpora tecnologias como Node.js, TypeScript, JavaScript, HTML, CSS e Oracle SQL para criar um sistema completo de gerenciamento de voos. Este projeto abrangeu o desenvolvimento de um servidor Node.js e a integração de um banco de dados Oracle SQL, permitindo a realização de solicitações HTTP por meio de métodos GET, PUT e DELETE. Além disso, a construção de um front-end envolvendo HTML, CSS e JavaScript facilitou a interação do administrador com o sistema, incluindo a inserção de informações relacionadas a aeronaves, voos e outras tabelas.

Fase 1: Configuração do Servidor Node.js
Na primeira fase do projeto, nosso foco estava na configuração de um servidor Node.js. Instalamos módulos essenciais, como o Express, que nos permitiu criar rotas para manipular solicitações HTTP. Em seguida, configuramos o ambiente de desenvolvimento TypeScript para facilitar a manutenção do código. Finalmente, instalamos o módulo OracleDB para conexão e utilização de funções do banco de dados.

Fase 2: Desenvolvimento do Backend com TypeScript e criação do Banco de Dados - modelo lógico
A segunda etapa do projeto concentrou-se no desenvolvimento do backend em TypeScript. Utilizamos rotas e controladores para criar endpoints que permitissem a interação com o banco de dados Oracle SQL. Desenvolvemos um modelo de dados e um esquema MER (Modelo Entidade-Relacionamento) para estruturar o banco de dados, incluindo tabelas para aeronaves, trechos, aeroportos, cidades, assentos e voos.

Fase 3: Integração do Backend com o Banco de Dados
Na terceira fase, realizamos a integração entre o backend e o banco de dados Oracle SQL. Criamos consultas SQL para buscar, atualizar e excluir dados. Testamos essas operações utilizando o Postman, garantindo que as rotas estivessem funcionando corretamente e que o banco de dados fosse atualizado de acordo com as solicitações.

Fase 4: Desenvolvimento do Front-end e integração com o back-end
A quarta e última fase envolveu o desenvolvimento do front-end, voltado para o lado do administrador. Criamos telas HTML interativas. Através de scripts e funções JavaScript, integramos o front-end com o backend, permitindo ao administrador inserir informações sobre aeronaves, voos e outros detalhes relacionados ao sistema de gerenciamento de voos. O front-end chamava as rotas do backend, que, por sua vez, realizavam operações no banco de dados.

ENTREGA 2 - CLIENTES

Nesta segunda entrega, concentramo-nos no desenvolvimento de telas e funcionalidades voltadas para o lado do cliente, aprimorando a experiência de compra de passagens com melhorias significativas no design utilizando CSS. 

Fase 5: Desenvolvimento do Front-end para Clientes
Na quinta fase do projeto, direcionamos nossos esforços para criar uma experiência intuitiva para os clientes. Desenvolvemos telas HTML interativas que simulam o processo de compra de passagens aéreas. Os clientes podem navegar por diferentes opções de voos, visualizar detalhes das aeronaves, escolher assentos e proceder ao pagamento.

Utilizando JavaScript, integramos essas telas com o backend em TypeScript. Implementamos métodos de requisições HTTP com Node.js para enviar dados ao servidor e receber atualizações em tempo real sobre disponibilidade de voos, preços e informações relacionadas. Essa interação entre o front-end e o back-end permite uma experiência dinâmica e responsiva para os clientes durante o processo de compra.

A integração entre o front-end e o back-end, com destaque para o método HTTP POST, foi crucial nessa fase, pois os dados inseridos pelos clientes são enviados ao servidor de maneira segura e eficiente. O servidor realiza validações, verifica a disponibilidade de assentos e processa o pagamento de acordo com as informações fornecidas. As respostas do servidor são então refletidas instantaneamente no front-end, proporcionando uma experiência fluida e transparente para os clientes.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

DELIVERY 1 - ADMIN

Introduction:
Integrator Project 2 incorporates technologies such as Node.js, TypeScript, JavaScript, HTML, CSS, and Oracle SQL to create a comprehensive flight management system. This project included the development of a Node.js server and the integration of an Oracle SQL database, enabling HTTP requests using methods like GET, PUT, and DELETE. Furthermore, the construction of a front-end using HTML, CSS, and JavaScript facilitated administrator interaction with the system, allowing for the insertion of information related to aircraft, flights, and other tables.

Phase 1: Node.js Server Configuration
In the first phase of the project, our focus was on configuring a Node.js server. We installed essential modules such as Express, enabling us to create routes for handling HTTP requests. Additionally, we set up the TypeScript development environment to streamline code maintenance. Finally, we installed the OracleDB module for database connection and utilization of database functions.

Phase 2: Backend Development with TypeScript and Logical Database Design
The second stage of the project concentrated on backend development using TypeScript. We utilized routes and controllers to create endpoints for interacting with the Oracle SQL database. We developed a data model and an Entity-Relationship (ER) schema to structure the database, including tables for aircraft, routes, airports, cities, seats, and flights.

Phase 3: Backend Integration with the Database
In the third phase, we integrated the backend with the Oracle SQL database. We created SQL queries to retrieve, update, and delete data. We rigorously tested these operations using Postman to ensure that the routes functioned correctly and that the database was updated in accordance with the requests.

Phase 4: Front-end Development and Integration with the Backend
The fourth and final phase involved front-end development focused on the administrator's side. We designed interactive HTML screens. Through JavaScript scripts and functions, we integrated the front-end with the backend, enabling administrators to input information about aircraft, flights, and other details related to the flight management system. The front-end called the backend's routes, which, in turn, performed operations on the database.

DELIVERY 2 - CLIENTS

In this second delivery, our focus shifted to developing screens and functionalities for the client's side, enhancing the ticket purchasing experience with significant improvements in design using CSS.

Phase 5: Front-end Development for Clients
In the fifth phase of the project, we directed our efforts toward creating an intuitive experience for clients. We developed interactive HTML screens that simulate the process of purchasing airline tickets. Clients can navigate through different flight options, view aircraft details, choose seats, and proceed to payment.

Using JavaScript, we integrated these screens with the backend in TypeScript. We implemented HTTP request methods with Node.js to send data to the server and receive real-time updates on flight availability, prices, and related information. This interaction between the front-end and the back-end allows for a dynamic and responsive experience for clients during the purchasing process.

The integration between the front-end and the back-end, with a notable emphasis on the HTTP POST method, was crucial in this phase. This method ensures that client-entered data is sent to the server securely and efficiently. The server performs validations, checks seat availability, and processes payment according to the provided information. Server responses are then reflected instantly on the front-end, providing a smooth and transparent experience for clients.
