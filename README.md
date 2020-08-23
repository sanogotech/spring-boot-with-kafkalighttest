# spring-boot-with-kafkalighttest

Testing an Apache Kafka Integration within a Spring Boot Application and JUnit 5

## Docs
- https://blog.mimacom.com/testing-apache-kafka-with-spring-boot-junit5/

## Code

```java

@EmbeddedKafka
@ExtendWith(SpringExtension.class)
public class SimpleKafkaTest {

    @Autowired
    private EmbeddedKafkaBroker embeddedKafkaBroker;

    // ...

}

```

