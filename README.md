# twitterv2-auth-service
- The user service is responsible for handling Authorization & Authentication operations.
- Has its own database in which it stores a username and a password in order to be able to function in the event of the user service going down.
- Receives API calls through an API gateway.
- Uses Kafka to consume messages in the scenario of a user CRUD operation being executed.

![Architecture Diagram](https://github.com/daniil2231/twitterv2-auth-service/blob/main/c4_auth.png)
