### REFLECTION MODUL 8
1. AMQP, or Advanced Message Queuing Protocol, is a standardized way for software components to communicate by sending messages. It defines rules and formats for exchanging messages between different systems, allowing applications written in different languages and running on different platforms to communicate reliably.
   <br></br>
2. In the connection URL amqp://guest:guest@localhost:5672:

"guest:guest" refers to the default username and password used for authentication when connecting to the RabbitMQ message broker. These default credentials ("guest" username and "guest" password) are often used for testing or development purposes.
"localhost:5672" specifies the host and port of the RabbitMQ server. "localhost" means the RabbitMQ server is running on the same machine. The port number 5672 is the default port for AMQP connections.
So, connecting to amqp://guest:guest@localhost:5672 means establishing a connection to a RabbitMQ server running on the local machine using the default "guest" credentials for authentication.