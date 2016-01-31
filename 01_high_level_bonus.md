# Higher Level Overview

### How do you build real-time applications?
* We can build real-time applications using WebSockets
* Node server can act both as a http server and also a socket server,
  multi-threaded servers are ideal for handling this protocol
* Other frameworks can leverage WebSockets by using multi-threaded servers. For
  example Rails' ActionCable uses a multi-threaded server

### So how might Facebook have set up their infrastructure?
* Facebook has multiple clients. They have an iOS app, Android app, a website
  and so on. No matter which client the user uses, as long as they are logged
  into their account, they should have a similar experience.
* These clients make requests to Facebook servers. These servers can take
  requests from any client.
* Facebook has a server specifically configured to handle normal pages. A
  multi-threaded server isn't optimized for serving thing like static assets.
  They also have another server specifically configured to to handle real-time
  communication. When real-time activity such as live chat is needed this server
  would be used.

### What are front-end frameworks?


### What is client side rendering vs. server side rendering?


### How might we scale our website?



# Workout Level 2
Finish tic tac toe game with scores and reset button

# Workout Level 3
Build connect 4
