# Project4
Nandogree Front-End Web Developer Project 4

Optimizations made for Part 1 - index.html to get PageSpeed higher than 90
1) Updated the <link href="css/print.css" rel="stylesheet"> to <link href="css/print.css" rel="stylesheet" media="print">
2) Added "async" to <script src="http://www.google-analytics.com/analytics.js"></script> to make it <script asyncsrc="http://www.google-analytics.com/analytics.js"></script>
3) Compress the profilepic.jpg to 67%
4) Added a pizzeriasm.jpg that is already resized smaller 115 x 86
5) Inline the CSS code of style.css to the index.html
6) Inline the CSS code of fonts.googleapis.com/css?family=Open+Sans:400,700 to the index.html

Optimizations made for Part 2 - main.js to get FPS of 60
1) dx and newwidth is placed outside the for loop. 
2) Created randpizzaCont to equal the value of the randomPizzaContainer[0]
3) pizzasDiv is placed outside the for loop. 
4) using http://www.html5rocks.com/en/tutorials/speed/animations/
Created onScrollTick to keep track of the last scroll and only update the last scroll data 
5) resized the pizza.png to 70px x 70px 
6) Change the number of sliding pizza created from 200 to 25
