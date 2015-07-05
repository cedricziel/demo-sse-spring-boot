# Simple Spring SSE Demo

SSE is for Server Sent Events.

## Requirements

* jdk8
* Maven3

## Run

```
mvn spring-boot:run
```

Open localhost:8080

## Takeaways

* the timeout for the SSE - Emitters needs to be raised.
* emitters need to be manually removed when the listener dies or on completion
* SSE with Spring Boot is practically a no-brainer
