# jQuery

### What is jQuery?
jQuery is one of the most popular JavaScript libraries.

### Why jQuery?
Each browser's JavaScript is a little bit different. A line of JavaScript might
behave differently on a FireFox browser than a Chrome browser. It's a pain to
write the same line of code for different browsers. This is where jQuery comes
in, we write it once and jQuery handles the browser compatibility issues for us.
It also allows us to use simpler syntax for common JavaScript tasks.

### What can we do with jQuery?
* DOM manipulation
    $('h1').text('I can change the text of all headings with one line');
* Event Listeners
    $('button').click(function() {
      console.log('Button was clicked');
    });
* Ajax
    $.ajax({
      url: 'http://swapi.co/api/people/1/',
      method: 'get'
    })
    .success(function(res) {
      console.log(res);
    });

### What are callbacks and why do we need them?
* document.ready example
    // If we put our code in the head we have to use document.ready
    $(document).ready(function() {
      // do stuff
    });
    // If we put our code at the bottom of our body we don't need to
    // do stuff

* hide example
    $('p').hide(5000);
    alert("what");

    $('p').hide(5000, function() {
      alert("what");
    });

# Homework
Build a website using the Star Wars API.
