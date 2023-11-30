**Spring Boot Kafka Reactive Project**

Producer Project: The producer project leverages the Spring Boot Reactive framework to extract a data stream from [Wikimedia Recent Changes](https://stream.wikimedia.org/v2/stream/recentchange). This project is designed to efficiently read the streaming data and subsequently transmit the messages to a Kafka broker.

Consumer Project: The consumer module complements the producer by retrieving messages from the Kafka topic and logging the received messages into the console for demonstration purposes.

