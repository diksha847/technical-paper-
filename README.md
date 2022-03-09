# Table Of Contents 
1.What are messaging queues?

2.Why are messaging queues used ?

3.What are popular tools ?

4.What is Enterprise message bus ?

References
## What are messaging queues?
1. Message queuing allows apps to connect with one another by sending messages.When the destination programme is busy or not connected, the message queue provides interim message storage.
2. A message queue's basic architecture is straightforward:producers are client programmes that create messages and send them to the queue.A consumer connects to the queue and retrieves the messages that need to be processed. Messages are stored in the queue until they are retrieved by the consumer.
3. Asynchronous communications protocol is provided by a message queue, which is a system that places a message on a queue and does not require an immediate response to continue processing. Asynchronous communication is best exemplified by email.When an email is sent, the sender can move on to other tasks without waiting for a response from the recipient.This method of managing messages separates the producer and the consumer,allowing them to interact with the message queue independently.
 ![](https://github.com/diksha847/technical-paper-/blob/main/thumb-mq.jpg)

## Why are messaging queues used ?
 1. Asynchronous communication is enabled through message queues,
  which means that the endpoints that produce and consume messages engage with the queue rather than with each other.
   Requests can be added to the queue without having to wait for them to be processed.
    Messages are only processed by consumers when they are available.
   The data flow is optimised since no component in the system is ever blocked while waiting for another.

 2. Message queues eliminate dependencies between components and make decoupled application coding much easier.
    Instead of being burdened down by communications code,
     software components can be tailored to fulfil a specific business purpose.
     Whether you're utilising monolithic applications, microservices, or serverless architectures, 
     message queues provide an incredibly simple approach to decouple distributed systems.
## What are popular tools ?
1.MuleSoft Anypoint Platform.
2.IBM MQ.
3.Apache Kafka.
4.Azure Scheduler.
5.Apache Qpid.
6.RabbitMQ.
7.TIBCO Rendezvous.
8.Azure Queue Storage.
## What is Enterprise message bus ?
A software platform called an enterprise service bus (ESB)
 is used to distribute work among connected components of an application. 
 Its purpose is to provide a consistent method of moving work by allowing apps 
 to connect to the ESB and subscribe to messages using simple structural and business policy criteria.
As a result, it can be used for remote computing as well as component integration. 
The/:best way to think of this tool is as a series of switches that can route a message across 
application components based on the contents of the message and the implementation of business policies.
## References 
1.https://www.cloudamqp.com/blog/what-is-message-queuing.html

2.https://aws.amazon.com/message-queue/benefits/#:~:text=Message%20queues%20enable%20asynchronous%20communication,only%20when%20they%20are%20available.

3.https://www.techtarget.com/searchapparchitecture/definition/Enterprise-Service-Bus-ESB#:~:text=An%20enterprise%20service%20bus%20(ESB,structural%20and%20business%20policy%20rules.

4.https://www.g2.com/categories/message-queue-mq
    

