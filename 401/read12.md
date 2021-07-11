Research and discussion

*What is the benefit of transforming data into packets?*
minimize the transmission latency (the time it takes for **data** to pass across the network) , as  data divided into smaller segments "packets"

 ***UDP** is often refereed to as a connectionless protocol. Why is this?*
No arragments between the sender and the reciver , the device transmits the unit of data before ensuring that the receiving end’s device is ready.

Can a socket server application have multiple socket connections
yes
Can a socket connection application be connected to multiple socket servers?
no
Can an application be both a socket server and a socket connection?
yes

Definations :

**Observer Pattern:**  _is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods._

**Listener**: A function that waits for something to happen (event)

**Event Handler**: something that will be executed based on an interaction (event) that connected with it

**Event-Driven Programming**
Interactive Programming language to give you any results (output) input, process, output that’s what event-driven stands for, so when I am writing this definition, the big picture view that in the background there is an event handler which handled my click on the keys to be processed than to be seen on the screen


**Event loop** : is something responsible for taking functions that's in the ### Event Queue and push them to the stack once the stack is empty 

 **Event Queue**  when we have an asynchronous processes theses are handled via webapi.. in node js c++ apis ,so they are processeed using apis once they are ready they added to the  Event Queue once the call stack are empty , the event loop will take each one first in first out from the queue and add it to the call stack so it will be executed ..
**Callstack** : is something the order of the execution to the processes ..imagine there is a function that has a nested function .. the nested function will be executed first then the outer one
Prepare

**database**: a place where we can save our data without loosing it , it's saved based on it's type(nosql,sql) , we use it rather than file system or excel sheet for example  because the managment system , do alot of the stuff in the background ex concurrency control , indexing ,performance tuning
**Subscribe:**
Optional. Default is  `undefined`.
the function that is called when the Observable is initially subscribed to. This function is given a Subscriber, to which new values can be  `next`ed, or an  `error`  method can be called to raise an error, or  `complete`  can be called to notify of a successful completion.

**Emit/Raise/Trigger:** after hhese methods the handler will be ready to take the event 

Prepare:

**WebSocket**  is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer. When clients trigger the request to the server, it does not close the connection on receiving the response; it rather persists and waits for the Client or server to terminate the request.

**Socket.io**
is a library that enables real-time and full-duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts; both WebSocket vs Socket.io are event-driven libraries.


Resources
https://www.google.com/
https://www.wikipedia.org/
https://www.youtube.com/watch?v=8aGhZQkoFbQ
https://rxjs-dev.firebaseapp.com/api/index/class/Observable#subscribe