## Review, Research, and Discussion

Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
* Regardless what happend in the background and what enviroment each one take and the life cycle ,, in the end they are both used for backend stuffs.

List the AWS Database offerings and talk about the pros and cons of each
RDS, Redshift, DynamoDB and Aurora , i will introduce two properites scaling and maintanance 
*in case of scaling* 
**RDS** – Because RDS is less complex, it’s easier to scale
**Redshift** is probably the better choice, since its Concurrency Scaling featur
**DynamoDB** – DynamoDB scales seamlessly with no impact on performance

**Auroura:will** automatically start-up, scale-up, scale down and shut down in-line with your application’s needs
in case of maintanance 

**RDS & DynamoDB**  – Your RDS and DynamoDB instances will be maintained by AWS for the most part, with the user having the option to defer certain updates.

**Redshift** – Redhsift requires more maintenance

**Aurora**  – Aurora’s maintenance is synonymous with RDS’s when run with RDS. When run serverless, there is virtually no maintenance required.

  *What’s the difference between a FIFO and a standard queue?*
Standard queues **provide at-least-once delivery**, which means that each message is delivered **at least o**nce. Fifo , exactly once .


 *How can the server be assured a message was properly received?*
by triggger an event once t he user reciive the message 
## DEfinations
*Serverless API* : the ability to make AN API requests through the cloud ,, ex amazon provides a servicce to do that where you can establish your routes and using lamda which is possibly the most efficient resource available in the cloud for running application when we say servless it means you don't have to wory about the server even if it excist as AWS handles them

Trigger: Creating a response to an event is done with a  _trigger_. A trigger is a declaration that you are interested in a certain event or set of events. Binding a function to a trigger allows you to capture and act on events. , example the event could be save a record to a db the trigger will handle the saving process.

Dynamo vs Mongo
Dynamo is managed by aws so it's only available when using AWS ,
however if you use mongo you can deploy any where , 
Since mongo is for anything and dynamo for AWS , i belive the community of Mongo is  bigger

Dynamoose is a model for Dynamo  DB that can be used if you using AWS only vs Mongoose is object model for mongo that can be deployedd anywhere.
## ## Preview
**SNS**  is a distributed  **publish-subscribe**  system. Messages are  **pushed**  to subscribers as and when they are sent by publishers to SNS.

**SQS**  is distributed  **queuing**  system. Messages are  _not_  pushed to receivers. Receivers have to  **poll or pull**  messages from  **SQS**.

Additional Resources
https://stackoverflow.com/questions/13681213/what-is-the-difference-between-amazon-sns-and-amazon-sqs
Google.com 
https://cloud.google.com/functions/docs/concepts/events-triggers
https://www.justaftermidnight247.com/insights/rds-redshift-dynamodb-and-aurora-how-do-aws-managed-databases-compare/