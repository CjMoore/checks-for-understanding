## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What is Webpack and why is it useful?
<p>Webpack is a tool used to translate javascript html and css into something that your browser can easliy interpret.</p>
2. When do you want to use event delegation?
<p>When you have an event listener on something that isn't on the page when its first loaded. For example in QS when we create a food, the delete button for that food is not on the page initially. The event listener won't be tied to the new food delete button unless you set up the listener with an event delegator.</p>
3. What's one difference between ES5 and ES6?
<p>You can use hash rocket syntax when declaring a callback function.</p>
4. What's the deal with semi-colons in JavaScript?
<p>When JS is minified and compressed, all the white space is removed. Semi-colons help the browser know when an expression is finished. They are less necessary when using ES6, not entirely sure why.</p>
5. How are you using the MVC design pattern in your Quantified Self project?
<p>We have seperated responsibility and created models, in which all the database interaction takes place, and controllers which return the correct data.</p>
6. How do you execute raw SQL in node?
<p>In QS we are using knex. There is a function you can call on your database called .raw(), in which you can use an SQL statement to communicate with the database.</p>
7. What is CORS?
<p>Cross Origin Resource Sharing. It is built into the http request response cycle. It prohibits http requests to an application from an outside source.</p>
8. What are some steps to avoid CORS?
<p>Node has a package that handles it for you. You can also manually override it by setting 'allow-access-control' headers.</p>

#### Review  

9. Why do people say "HTTP is stateless"?
<p>Because no data is stored throughout the request response cycle</p>
10. What is a RESTful API?
<p>REST is a set of conventions for building api endpoints. One convention I'm aware of is that ideally every endpoint will always return the same information.</p>
11. What are some main characteristics of a team following an agile workflow?
<p>Communicaiton with clients, testing throughout, feedback</p>
12. What are some advantages/disadvantages to using OAuth to authenticate a user?
<p>Advantages: an outside resource might have more a more secure Authorization process than we are able to build. Disadvantage: You rely on an outside source, if something happens to that source your app is affected.</p>
