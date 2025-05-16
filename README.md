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

###### Result of Running Subscriber and Publisher
![Subscriber Result](images/subscribernew.jpg)
![Publisher Result](images/publisher.jpg)

###### Result of Running Publisher Repeatedly
![RabbitMQ Publisher](images/RabbitPublisher.jpg)
There is one tall spike in the chart with the rate of two messages per second
because I ran publisher twice in succession. The purple spikes show the rate
of messages sent within a minute time frame.