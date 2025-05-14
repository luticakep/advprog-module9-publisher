# Kayla Soraya Djakaria - 2306256381

1. How much data your publisher program will send to the message broker in one run? 

    The publisher program will send 5 messages to the message broker in one run. Each message contains 24 bytes of data from the user_id and user_name. So in total, the publisher will send 120 bytes of data to the message broker in one run.

2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

    It specifies the protocol (AMQP), the username (guest), the password (guest), and the host (localhost) along with the port number (5672). This means that both the publisher and subscriber programs are connecting to the same RabbitMQ server using the same credentials, allowing them to communicate with each other through message queues. 

### Rabbit MQ
![](rabbit.png)
