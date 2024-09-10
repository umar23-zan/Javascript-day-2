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
##Variables
a. Create a <script> element. Inside the <script>, create a variable called 'name', and save your name in this variable (as a string).
```
<script>
      let name='9442442233';
</script>
```
b. Continuing from 5a, display the message 'My name is: $(name)' in the console (insert the 'name' variable created in 5a into this message).
```
<script>
      let name='9442442233';
      consloe.log(`My name is: ${name}`);
</script>
```
c. At a restaurant, you order 1 coffee ($5), 2 bagels ($3 each), and 1 soup ($9). Calculate the cost and save it in a variable called 'cost'.
```
 <script>
      let cost=1*5+2*3+1*9;
</script>
```
d. Continuing from 5c, display 'Cost of food: $${cost)' in the console.
```
 <script>
      let cost=1*5+2*3+1*9;
      console.log(`Cost of the Food:$ ${cost}`);
</script>
```
e. Let's say the restaurant charges a 10% tax. Using the 'cost' variable from 5c, calculate the tax, and save the result in a variable.
```
 <script>
      let cost=1*5+2*3+1*9;
      console.log(`Cost of the Food:$ ${cost}`);
      let tax=cost*0.1;
    </script>
```
f. Continuing from 5e, display 'Tax (10%): $$(tax)' in the console.
```
<script>
      let cost=1*5+2*3+1*9;
      console.log(`Cost of the Food:$ ${cost}`);
      let tax=cost*0.1;
      console.log(`tax for the food is: $ ${tax}`);
</script>
```
g. Continuing from 5f, calculate the total (cost + tax), save it in a variable called 'totalCost', and display the message 'Total cost: $$(totalCost)' in the console.
```
<script>
      let cost=1*5+2*3+1*9;
      console.log(`Cost of the Food:$ ${cost}`);
      let tax=cost*0.1;
      console.log(`tax for the food is: $ ${tax}`);
      let totalCost=cost+tax;
      console.log(`Total cost is:$ ${totalCost}`);
</script>
```
h. In the Cart Quantity project, add 2 more buttons '+4' and '+5', which increase the quantity by 4 and 5 when you click them. Try using +=
```
<button onclick="cartquan+=4;
    console.log(`Cart Quantity is: ${cartquan}`);">+4
</button>
<button onclick="cartquan+=5;
    console.log(`Cart Quantity is: ${cartquan}`);">+5
</button>
```
i. In the Cart Quantity project, add a button 'Remove from cart', which
decreases the cart quantity by 1.
```
<button onclick="
    cartquan--;
    console.log(`Cart Quantity is: ${cartquan}`);">Remove from cart
</button>
```
j. Add 2 buttons '-2' and '-3', which decrease the quantity by 2 and 3.
```
<button onclick="
    cartquan-=2;
    console.log(`Cart Quantity is: ${cartquan}`);">-2
</button>
<button onclick="
    cartquan-=3;
    console.log(`Cart Quantity is: ${cartquan}`);">-3
</button>
```
k. Use the shortcuts -- and -= in 5i and 5j.
```
<button onclick="
    cartquan--;
    console.log(`Cart Quantity is: ${cartquan}`);">Remove from cart
</button>
<button onclick="
    cartquan-=2;
    console.log(`Cart Quantity is: ${cartquan}`);">-2
</button>
<button onclick="
    cartquan-=3;
    console.log(`Cart Quantity is: ${cartquan}`);">-3
</button>
```
l. Add the HTML structure (<!DOCTYPE html>, <html>, <head>, <body>). Add a <title> with the text 'Calculator'
```
<!DOCTYPE html>
<html>
  <head>
    <title>
      <b>
        Calculator
      </b>
    </title>
  </head>
  <body>
    
  </body>
</html>
```
m. Create these 5 buttons:
1 2 3 + =
```
<button>1</button>
<button>2</button>
<button>3</button>
<button>+</button>
<button>=</button>
```
5n. Create a <script>, create a variable called 'calculation', and save an empty string inside: let calculation = "; (This variable will store the calculation like '1 + 2' or '11 + 2 + 2')
```
<script>
      let calculations='';
</script>
```
o. When we click the '1' button:
- Add the string '1' to the calculation variable: calculation += '1';
- Display the calculation in the console: console.log(calculation);
```
 <button onclick="
      calculations+='1';
      console.log(calculations);">1
    </button>
```
p. Do the same for the '2', '3', and '+' buttons (add' + ' instead of '+').
```
 <button onclick="
      calculations+='2';
      console.log(calculations);">2
    </button>
    <button onclick="
      calculations+='3';
      console.log(calculations);">3
    </button>
    <button onclick="
      calculations +=' + ';
      console.log(calculations)">+
    </button>
```
q. When we click the '=' button, use the code: eval(calculation); (eval(...) converts the calculation string into actual math) - Save the result back in 'calculation': calculation = eval(calculation);
Display the result in the console: console.log(calculation)
```
<button onclick="
      calculations=eval(calculations);
      console.log(calculations)">=
    </button>
```
r. Create the rest of the buttons in the calculator. To create multiple rows of buttons, put the buttons inside <p> elements like this:
```
<body>
    <p>
    <button onclick="
      calculations+='1';
      console.log(calculations);">1
    </button>
    <button onclick="
      calculations+='2';
      console.log(calculations);">2
    </button>
    <button onclick="
      calculations+='3';
      console.log(calculations);">3
    </button>
    <button onclick="
      calculations +=' + ';
      console.log(calculations)">+
    </button>
    </p>
    <p>
      <button onclick="
      calculations+='4';
      console.log(calculations);">4
    </button>
    <button onclick="
      calculations+='5';
      console.log(calculations);">5
    </button>
    <button onclick="
      calculations+='6';
      console.log(calculations);">6
    </button>
    <button onclick="
      calculations +=' - ';
      console.log(calculations)">-
    </button>
    </p>
    <p>
      <button onclick="
      calculations+='7';
      console.log(calculations);">7
    </button>
    <button onclick="
      calculations+='8';
      console.log(calculations);">8
    </button>
    <button onclick="
      calculations+='9';
      console.log(calculations);">9
    </button>
    <button onclick="
      calculations +=' * ';
      console.log(calculations)">*
    </button>
    </p>
    <p>
      <button onclick="
      calculations+='0';
      console.log(calculations);">0
    </button>
    <button onclick="
      calculations+='.';
      console.log(calculations);">.
    </button>
    <button onclick="
      calculations +=' / ';
      console.log(calculations);">/
    </button>
    <button onclick="
      calculations=eval(calculations);
      console.log(calculations)">=
    </button>
    </p>
    
    <script>
      let calculations='';
    </script>
  </body>
```
