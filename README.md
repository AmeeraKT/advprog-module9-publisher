# Advanced Programming Module 9

## Module 09 - Software Architectures

### Reflection

1. How much data your publisher program will send to the message broker in one run? 
```
In one run, five messages were sent to the message broker.
```

2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
```
The reason the urls are the same so that the publisher and subscriber can
connect to the same message broker on port 5672 locally on localhost. This
allows the the publishe and subscriber to communicate with each other.
```

###### RabbitMQ Running
![RabbitMQ running](images/RabbitMQ_Run.jpg)