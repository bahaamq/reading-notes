**Research**
**What’s the difference between a FIFO and a standard queue?**
**Standard queues** FIFO queues** ensure a message **is** delivered exactly once

**How can the server be assured a message was properly received?**
Adding a callback after the emit as acknowledges 

*EX:
socket.emit("update item", "1", { name: "updated" }, (response) => {  
 console.log(response.status);* 

**What classic design pattern is best represented by event driven programming?**
*observer pattern*

**Definitions**
FIFO Queue:
designed to enhance messaging between applications when the order of operations and events is critical, or where duplicates can't be tolerated. Example:
making sure that user-entered commands are run in the right order.

Pub/Sub enables you to create systems of event producers and consumers, called  **publishers**  and  **subscribers.**  Publishers communicate with subscribers asynchronously by broadcasting events, rather than by synchronous remote procedure calls (RPCs).


**Prepare**
-   SQS does not push messages to the consumers, instead, consumers have to poll the queue, and as soon as one of them receives a message, the message is out of the queue and no other consumer can access it. This polling inevitably introduces a certain latent delay in message delivery.
-   SNS pushes the messages to all its subscribers as soon as it receives it, hence there is no latency and you can easily add subscribers down the line.
-   SQS is mainly used to decouple applications or integrate applications.
-   SNS is used to broadcast messages and it’s up to the receivers how they interpret and process those messages.

Resources:
https://hevodata.com/learn/sns-vs-sqs/
Google.com
Stackoverflow.com
Amazon.aws.com
Socket.io