# Banking-Application-using-sprint-boot-microservices
The Banking Application is built using a microservices architecture, incorporating the Spring Boot framework along with other Spring technologies such as Spring Data JPA, Spring Cloud, and Spring Security, alongside tools like Maven for dependency management. These technologies play a crucial role in establishing essential components like Service Registry, API Gateway, and more.

Moreover, they enable us to develop independent microservices such as the user service for user management, the account service for account generation and other related functionalities, the fund transfer service for various transfer operations, and the transaction service for viewing transactions and facilitating withdrawals and deposits. These technologies not only streamline development but also enhance scalability and maintainability, ensuring a robust and efficient banking system.

Service Registry: The microservices uses the discovery service for service registration and service discovery, this helps the microservices to discovery and communicate with other services, without needing to hardcode the endpoints while communicating with other microservices.

API Gateway: This microservices uses the API gateway to centralize the API endpoint, where all the endpoints have common entry point to all the endpoints. The API Gateway also facilitates the Security inclusion where the Authorization and Authentication for the Application.

👤 User Service: The user microservice provides functionalities for user management. This includes user registration, updating user details, viewing user information, and accessing all accounts associated with the user. Additionally, this microservice handles user authentication and authorization processes.

💼 Account Service: The account microservice manages account-related APIs. It enables users to modify account details, view all accounts linked to the user profile, access transaction histories for each account, and supports the account closure process.

💸 Fund Transfer Service: The fund transfer microservice facilitates various fund transfer-related functionalities. Users can initiate fund transfers between different accounts, access detailed fund transfer records, and view specific details of any fund transfer transaction.

💳 Transactions Service: The transaction service offers a range of transaction-related services. Users can view transactions based on specific accounts or transaction reference IDs, as well as make deposits or withdrawals from their accounts.
