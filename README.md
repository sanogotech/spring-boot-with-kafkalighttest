# spring-boot-with-kafkalighttest

Testing an Apache Kafka Integration within a Spring Boot Application and JUnit 5

## Docs
- https://blog.mimacom.com/testing-apache-kafka-with-spring-boot-junit5/
- https://forum.huawei.com/enterprise/fr/apache-kafka-pour-les-d%C3%A9butants/thread/744485-100379
- https://lakshaysuri.wordpress.com/2016/10/02/apache-kafka/
- https://datascientest.com/apache-kafka
- https://soat.developpez.com/tutoriels/bigdata/apprendre-kafka-concepts-fonctionnement/

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

