What problems does the Observer Pattern seek to solve?

The Observer Pattern helps with keeping a consistant set of data avalible to access from multiple calls. Having one single data reference keeps everything in sync.

What are the three mechanisms of the observer pattern?

The Event Observer consitst of the Subscribe Method (to add events), the Unsubscribe Method(to remove events) and the Broadcast Method(to call all events).

Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

The Controller, the Service and the State template really help to break up the work order. Hold a fix data store in the state is easily accessed from both the controller and the service keeping Draw functions and coding consitanly using the same information. 




https://github.com/dallenpyrah/sporting-goods-store