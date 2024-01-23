
You are smart. You want a secure app. You also want to be able to setup a system where the authentication is isolated to its own environment. Low and behold, tokens. It's never been a better time to use a token-based authentication scheme, whether that be cloud-based or not. 


+ **CORS** - Say goodbye to that monolith. Haven't you always wanted to move to that new hot microservice architecture? Using tokens allows you to send network requests to any server on any domain! 
+ **Stateless** - You no longer need to keep any session information with your back-end. Just store that token in ```localStorage``` and be done with it. The token contains all the information pertinent to invalidating sessions, etc. 
+ **Decoupled** - We live in a society of SPAs and decoupling the front-end and back-end is the status quo.


As shown in the diagram below there are three main players in this example, the API, the Authentication Sever, and the Client. So, to begin ```fork``` or ```clone``` this repository. It would be ideal to setup the authentication server and the API in virtual environments. 

