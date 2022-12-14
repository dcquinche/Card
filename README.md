# Card Component
Make It Real - This is a solution to the Stats Preview Card Component Project of the Make It Real course.


## Table of contents
 1. [The challenge](#the-challenge)
 2. [Screenshot](#screenshot)
 3. [My process](#my-process)
 4. [Built with](#built-with)
 5. [What I learned](#what-i-learned)
 6. [Useful resources](#useful-resources)
 7. [Author](#author)
 8. [Acknowledgments](#acknowledgments)


### The challenge

Users should be able to:
Watch the different display depending on the size of the device (mobile or desktop)


### Screenshot

#### Mobile design
![Mobile design](https://github.com/dcquinche/Card/blob/main/design/Mobile.png)

#### Desktop design
![Desktop design](https://github.com/dcquinche/Card/blob/main/design/Desktop.png)


### My process

First we organized the HTML structure for the mobile design, then we added the layouts and put a @media to make the changes asked for the desktop design.


### Built with

- HTML
- CSS
- Mobile-first workflow
- Media Query


### What I learned

- flex direction property to order and display the items as needed.

```
 display: flex;
 flex-direction: row-reverse; 
		
```
- filter property to change the color of the image.

```
 filter: opacity(0.6) drop-shadow(0 0 0 hsl(277, 64%, 61%));	

```


### Useful resources

[Flex Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Ordering_Flex_Items) - This helped me to know how to change the order of different items for the desktop design.

[Filter Properties](https://www.w3schools.com/cssref/css3_pr_filter.asp) - This helped me to know how to change the color of the image.


### Author

Diana Carolina Quinche Velez -
[Linkedin](https://www.linkedin.com/in/diana-carolina-quinche-v%C3%A9lez-06b9791b3/)


### Acknowledgments

Special acknowledgments to Julian Gomez (team partner) and Cristian Moreno (our teacher).