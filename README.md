# Javascript-day-2
So, today the nest Exercises from javascript like HTML, CSS, Review, Console.log and Variables.

HTML, CSS Exercises.
a. Create a button with the text 'Click' inside.

Click
```
<button>Click</button>
```
b. Create 2 buttons. 1 with your name and 1 with your favorite food.

Simon  chocolate
```
<button>Umar</button> <button>Chocolate</button>
```
c. Create a paragraph with the text 'Hello, world!' inside.

Hello, world!
```
<p> Hello, World!</p>
```
d. Continuing from exercise 4c, create a paragraph below the previous paragraph and write something you did today.

Hello, world!
Today I went to the grocery store to buy some eggs and vegetables.
```
<p>Hello, World!<\p>
<p>I am doing JS exercises today<\p>
```
e. Create 2 buttons 'Add to cart' and 'Buy now'. Use CSS to give them yellow and orange background colors:

Add to cart  Buy now
```
<style>
      .yellowbutton{
        background-color:yellow;
      }
      
      .orangebutton{
        background-color:orange;
      }
    </style>
  <body>
    <button class="yellowbutton">Add to cart</button>
    <button class="orangebutton">Buy Now</button>
  </body>
```
f. Add the HTML structure to exercise 4e (add <!DOCTYPE html>, <html> <head>, <body>) and put the elements into the <head> or <body>. (For more practice, add the HTML structure to exercises 4a - 4d).
```
<!DOCTYPE html>
<html>
  <head>
    <style>
      .yellowbutton{
        background-color:yellow;
      }
      
      .orangebutton{
        background-color:orange;
      }
    </style>
  </head>
  <body>
    <button class="yellowbutton">Add to cart</button>
    <button class="orangebutton">Buy Now</button>
  </body>
</html>
```
g. Continuing from 4f, change the title at the top of the tab to 'Buttons'.
```
<!DOCTYPE html>
<html>
  <head>
    <title>Buttons</title>
    <style>
      .yellowbutton{
        background-color:yellow;
      }
      
      .orangebutton{
        background-color:orange;
      }
    </style>
  </head>
  <body>
    <button class="yellowbutton">Add to cart</button>
    <button class="orangebutton">Buy Now</button>
  </body>
</html>
```
h. Continuing from 4g, add a <script> element so that when the page loads, it displays the message 'Welcome!' in the Console.
```
<script>
  alert('Welcome');
</script>
```
i. Using HTML and CSS, try to copy the design on the right. (Make sure to follow the HTML structure.)

Add to cart
Buy now
```
<style>
      .yellowbutton{
        background-color:yellow;
      }
      
      .orangebutton{
        background-color:orange;
      }
    </style>
  <body>
    <p><b>Adults Plain Cotton T-shirts</b></p>
    <p> </p>
    <p>Price: $7.99 </p>
    <button class="yellowbutton">Add to cart</button>
    <button class="orangebutton">Buy Now</button>
  </body>
```
j. Continuing from 4i, add onclick="..." attributes to the two buttons:

• When clicking 'Add to cart', create a popup with the text 'Added'.

• When clicking 'Buy now', display the message 'Loading...' in the Console, and then create a popup with the text 'Purchased'.
```
<style>
      .yellowbutton{
        background-color:yellow;
      }
      
      .orangebutton{
        background-color:orange;
      }
    </style>
  <body>
    <p><b>Adults Plain Cotton T-shirts</b></p>
    <p> </p>
    <p>Price: $7.99 </p>
    <button class="yellowbutton" onclick="alert('Added');">Add to cart</button>
    <button class="orangebutton" onclick="alert('Loading');
    alert('Purchased');
    ">Buy Now</button>
  </body>
```
