## what is amqp?
AMQP, which stands for Advanced Message Queueing Protocol, is an open standard application layer protocol used for passing business messages between applications or organizations. AMQP connects systems, feeds business processes with the information they need and reliably transmits instructions to achieve their goals.

## what it means? guest:guest@localhost:5672, what is the first guest, and what is the second guest, and what is localhost:5672 is for?
`guest:guest@localhost:5672` is a string representing the connection parameters for an AMQP server. The first `guest` represents the username, the second `guest` represents the password, and `localhost:5672` represents the hostname of the server and its port number (5672 is the default port number for AMQP connections).

![Slow Subscriber](img\rabbitmq_slowsubscriber.jpg "Slow Subscriber")

The total number of queue in my machine was also 20, which is accurate to how many times I called cargo run on the publisher during this slow subscriber test.

