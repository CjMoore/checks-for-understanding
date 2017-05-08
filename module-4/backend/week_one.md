## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
<p>Getting through the sorting suite was extremely helpful in figuring out how to switch between ruby and javascript. The strategy I used to work through it helped me make some connections between similarities and differences between the languages. This has proven to be very useful for the work we've done so far.</p>
2. What are some tools to help debug JavaScript code?
<p>debugger in the client console, and pryjs for node. </p>
3. What are some tools you need in order to unit test your JavaScript?
<p>Mocha is a testing library and Chai is an assertion library.</p>
4. What is the syntax for invoking a function?
```
function someFunction() {
}

var someFunction = function() {
}
```
5. What's the difference between `==` and `===` in JavaScript?
<p>'3'== 3 will evaluate to true whereas only '3'===3 will evaluate to false.</p>
6. What's the difference between asynchronous and synchronous JavaScript? 
<p>Asynchronous JavaScript will move on to other tasks if an action is going to take longer. For example if you are making an API call, and don't use a callback or promise, your code might execute in such a way that it will finish before the API call is complete. Synchronous JavaScript executes in exactly the order it is written. </p>
7. What's a callback function and what are some reasons when we use/need callback functions?
<p>A callback function is a function that is passed to another function as a parameter.</p>
8. What's the biggest difference between a promise and a callback?
<p>A promise and a callback are related but not the same. A callback is used in a promise. You can use promises to manage asynchronicity, and tell your program what to essentially do next after a task has been completed.</p>
9. How do we setup a route when creating an API with Node and Express?
<p>Well first we have to set up the server. Then app.(verb)('/', function(request, response) {}
</p>
10. What's `npm` and what do we use it for?
<p>npm is the node package manager, packages are similar to gems. You use npm to install packages and their dependancies.</p>

#### Review  
11. What's the MVC design pattern? Describe each part of MVC?
<p>MVC stands for model view controller. When a user sends a request to your application it goes to the controller, which essentially takes in a request and directs it. The controller talks to the Model which in turn talks to the database. The model may return information or change stuff in the database depending on the request. Information is returned to the controller and the controller renders a view.</p>
12. What is AJAX? What are some benefits of using AJAX?
<p>AJAX is a part of the jQuery library. It is used to send API calls from the client side. A benefit of using AJAX is that you can request information and manage the returned data on the client side.</p>
13. What's a background worker? When would we want to use a background worker?
<p>A background worker does stuff in the background. A request triggers a queue, and then other code is executed while your application works on the queue in the background. </p>
