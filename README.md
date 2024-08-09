# LiveTransit
Async code in C++ to handle thousands of events from different sources. 

LiveTranscript co. is looking to disperse the number of passengers across their value chain to balance their network load. 

Lets create a program that receives live information about passengers' trips and produces travel suggestions that will help keep the network balanced.

### Project Requirements:
- Work with WebSockets, both at the client and server level, using the Boost.Asio library.
- Use the C++ concurrent APIs (futures, task-based programming, lambdas, task pools).
- Get familiar with the nuances of task-based programming, including launch policies and futures lifetime.
- Optimize the performance of an asynchronous event handler and measure it against your benchmark tests.
- Learn to benchmark the slow paths of a C++ application to drive your optimization strategy.
- Write unit tests for concurrent programs and create proxies and mocks to imitate real-time event sources.
- Create a modular software architecture that allows to plug and play different data sources when the software grows.
