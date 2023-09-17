# AsyncProgramming
Asynchronous programming with Java

Understand Node.js event loop

Difference between aync and concurrent(multithreading)

Understanding Blocking and Non-Blocking calls

Understand Java NIO features

Callback implementation in Java

Parallel programming
x
# Virtual Threads 
Java new feature in Java 21 and it is experimental feature since Java 19.

Platform thread/Virtual thread

Running million threads in user machine

This provides non-blocking capability. When JVM identifies a thread is blockign then it swaps the thread memory 
(network call or sleeping or waiting for other threads)

Easy to address scalabilty problem due to threads

Thread per request model - Traditional servlet approach, Tomcat provides 200 concurrent connections by default

Node.js, Python Tornedo, akka scala and Spring Webflux (reactive style of programming)

Reactive style is hard to read/understand and debug - Not dev friendly
