# d3-assignment

An assignment completed as part of my 4th-year Visualization course meant as an introduction to the d3 library.

## Information

As an introduction to d3, my 4th year Visualization course tasked us with recreating a provided image using d3, JavaScript, HTML and CSS. The provided image is included in the repository (Digital-Transform-Infographic.jpg). In addition to replicating the image, we were also tasked with adding interactive elements, for which I included highlighting for mouseovers and bars that resize on mouseover. 

This was my first time working with d3, and with little experience of how to properly use the library I did make some odd decisions. Namely, instead of creating HTML elements and selecting them in a JavaScript file to add d3 elements, I instead only created the body and did the rest in JavaScript. I appended divs to the body using d3, and created all other HTML elements via d3 appends. In my code I did at least make sure these appendings were organized well, but I realized in hindsight after learning more about how to use d3 that this method is highly unorthadox. These bizarre choices were ammended when creating my final d3-based project for the course (https://github.com/JamesGunby/d3-project-public). Regardless, the assignment still functions as intended. 

The grade for this assignment was an A+.

## Set up

This project requires Node.js to be installed.

1. In your terminal or command prompt, run `npm install http-server -g`
1. In your terminal or command prompt, navigate to the fole folder where the project is stored and run the command `http-server`
1. In your preferred browser, go to the URL `localhost:8080`.




