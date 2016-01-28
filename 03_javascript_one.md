# JavaScript One

### Why are we learning JavaScript?
* Only programming language that the browser can run
* Doesn't really matter which language you learn first all languages can do the
  same thing

### What is the difference between interpreted and compiled language?
* JavaScript, Ruby, PHP are all interpreted languages
* C and Swift are compiled languages (Java is somewhere in the middle)
* Interpreted is slower, but ok for websites because the language is never the
  bottleneck
* Compiled languages are faster and used for native applications (iOS, Android)

### What can all programming languages do?
* Make decisions depending on the conditions: If this is true then do something
  else. While this condition is true keep doing this. As long as we haven't done
  this 10 times yet, keep doing it.
* Hold onto stuff: Put all of these letters into a cabinet. Take something out
  of the 5th cabinet. Put all of these items into cabinets not named by numbers
  but with real names.
* Execute specific lists of tasks: Sometimes we want to run the same lines of
  code in sequence in many places. We can name this sequence, store it, and use
  the name of the sequence to execute it

### Why do some people like one language over the other?
* Familiarity: The more you understand a particular language and its frameworks,
  the more you will like it. For example I enjoy writing in Ruby the most so if
  there is no clear favorite, I will go with Ruby because that's what makes me
  happy.
* Libraries/Frameworks: Libraries/Frameworks is a chunk of reusable code someone 
  else wrote in a particular language that other programmers can use. Some
  people might say they love JavaScript when in reality they love AngularJS. Some
  people might say they love Ruby when in reality they love Rails.
* Industry: Some languages are more used in a particular language. For example
  Python and R is heavily used by the scientific community so if you want to be
  a data scientist someone might say Python and R is superior to other languages
  because of its libraries (not because the language itself is necessarily
  superior)

### What is JavaScript used for?
* Event listeners: When a button is clicked trigger this bit of code.
* Back end (server): We can use JavaScript on the back end as well. Some people
  might claim that JavaScript is the best because you can just learn one
  language to build a full featured application.
* Database: There are JavaScript databases that we can use where we store
  everything as a JavaScript Object.
* Communication medium: When we think of a website or a complex application it
  is never comprised of one application. They are multiple applications all
  written in different languages. However, all of these applications can
  communicate data with one another by using JSON (Javascript Objects) and any
  application can understand it.

### How can we start using JavaScript?
* Browser, in script tags
* JSbin
* node

### What is a variable?
* Hold stuff, for now let's say it holds numbers and text
    var variableOne = 1;
    var variableTwo = "Hello";

### What does the var keyword mean?
* Create space to store something

### What happens if we don't use the var keyword?
    variableOne = 1;
    var variableTwo = 2;
    variableTwo = 3;

### How do we hold onto a collection of things?
* Arrays
    [1,2,3,4,5]
* Objects (Hash table)
    {word: 'definition'}

### What is a loop? What's the difference between a while loop and a for loop?
* Loop when you want to repeat something over and over again
* Use a for loop when you know before hand how many times to repeat
    // Say hello 10 times written in 3 different ways
    for(var i = 0; i < 10; i++) {
      console.log('hello', i);
    }
    for(var i = 1; i < 11; i++) {
      console.log('hello' i);
    }
    for(var i = 1; i <=10; i++) {
      console.log('hello', i);
    }
* Use a while loop if you have no idea how many times it should run but just
  know it should run as long as a condition is true (or false)
    // This is an infinite loop
    var success = false;
    while(success == false) {
      console.log("Battle");
    }
    // This loop will stop after one time
    var success = false;
    while(success == false) {
      console.log("Battle");
      success = true;
    }
