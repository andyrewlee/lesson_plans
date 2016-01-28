What happens when you search nooma.tv on the browser?
* Makes a request to the DNS Server that converts domain name to IP Address
* Go to the computer (server) associated with the IP Address
* The server responds back with a file requested back to the client

What is a request?
* A client makes a request. Sometimes the client is the browser that makes a
  request for a file located at a particular URL
* Sometimes the client is a native app on our phone that makes a request for a
  file located at a particular URL

What is a domain?
* We can't expect our users to remember to type in our exact IP Address to
  access our website (i.e. 128.32.12.1) but nooma.tv might be easier to remember
* Domain name is something that you purchase to have ownership of a name and we
  can redirect our users to an IP Address that we want when they type in our
  domain name

What is an IP Address?
* If we need to go somewhere, we find out the address and put it into our Google
  maps
* IP Addresses work the same way, it is just the address represented by a
  series of numbers that locate where our server is

What is a server?
* If our web browser, or our phones (for native applications) are clients then
  what is a server?
* Clients ask the server for specific files whether that is an image,
  javascript, html, video, or css file. The server finds the appropriate files,
  assembles it together and responds with the specified files

What is a database?
* Sometimes the client will ask the server for information that is stored in a
  database
* We use a database to store things like a table of all of our users, a table of
  all of the classrooms and so on
* If the client asks for a page that lists all the classrooms, the server will
  get all the classrooms from the database, package them up nicely, and return
  back with a page that lists all the classrooms

What is HTML?
* The web was first used to share research papers. Think of any research paper
  you had to write, it's pretty simple formatting. There are headings,
  paragraphs, links, bullet points, tables, etc.
* To make the research papers show up properly, there needed to be a way to tell
  the browser that this segment of text is a heading, the next segment is a
  paragraph and so on
* HTML was created for this issue. Wrap the text in h1 tags if you want it to be
  shown as a heading and wrap the text in p tags if you want it to be shown as a
  paragraph, and so on.

What is CSS?
* Then people wanted to do more than just show research papers. However HTML
  wasn't designed for complex layouts, and styling. Then CSS was born.
* With CSS you can target specific HTML elements and put styling on them. For
  example we can tell that h1 (Heading) to have a font size of 18px and have it
  text aligned to the center.

What is JavaScript?
* People wanted to do more. What if they wanted to manipulate HTML elements
  without any restrictions?
* It doesn't matter if you build a website using Ruby, the browser only
  understands three things: HTML, CSS and JavaScript
* JavaScript is a language we can use to interact with each HTML elements and
  use bring them to life. For example when a button is clicked we can move the
  h1 down by 50px
