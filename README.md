# Background-Task-in-Js

## Introduction
<<<<<<< HEAD
The utility of using a background task is: <br>
=======
The utility of using a background task is:<br>
- Preventing the UI from freezing because of running intensive tasks. <br>
- Improving the performance of your JavaScript application. <br>
>>>>>>> e1006092aac9edacd8db58985e32b2f72f6d7393

- preventing the UI from freezing because of running intensive tasks. <br>
- improving the performance of your JavaScript application. <br>

## Using the Code
### A) Operating Process
In the following example, we will learn how to handle the main concept of Web Worker API through :<br>

- Initialization of a Worker (using Worker(url) class) ,
- Execution of a Web Worker (using postMessage(data) method) ,
- Exchanging messages between Web Worker and Main thread ,
- Ending of a Web Worker (using terminate() method).

The implemented demo allows users to:

- Start animation: This action initializes the web worker and sends to it a command to start the animation,  
The worker will choose a color code from a table, and will return it to the main thread for drawing, 
finally, the drawing process will change the background color of the 'Hello Web Worker' text.
- Stop animation: This action ends the worker, and stops animation.
