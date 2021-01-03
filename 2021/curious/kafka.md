## What is Kafka?
Apache kafka is an open-source stream-processing software platform written in Scala and Java. The project aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds.

Apache Kafka is a distributed messaging system who is implement of Publish-Subscribe model. Producer publish the message through broker, and consumer subscribe the message from the broker.

### Feature
1. Multi producers and consumers
  - Multiple producers can publish message to specific topic at one time
  - Also Multiple consumers can subscribe the same topic
2. Write to file system
  - They write to file system so that the message is much more safer and consumers can read their topic anytime
3. Scalability
4. High Throughput
5. Consumer Pull their topic
  - Usually broker push the topic to the subscribed consumer, but the broker just tell the consumer which one to pull

## Reference
- https://en.wikipedia.org/wiki/Apache_Kafka
- https://soft.plusblog.co.kr/3
