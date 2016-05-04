## Portfolio Homework Assignment

I decided for this project, to write the CSS from scratch. I did another version of this assignment with Bootstrap: You can find it here:

https://github.com/arnold-lei/portfolio-

For this assignment I found that I was a little rusty with CSS and it was really good practice to write the whole thing myself. There are still many things I need to learn. Part of the challenge of this assignment was to try to replicate the screenshots exactly. I took some liberties with ceartain styles but I remained as close to the original designs as possible. I mostly changed the font and text sizes. 

### Challenges

#### Footer:
The footer was paticularly challenging. I tried for a very long time to do it with pure CSS but I felt like I was getting no where with it. I tried a lot of tutorials on line but I still can't figure it out. For some reason the container div doesn't reach the bottom of the page.

I FINALLY FIGURED IT OUT!!! I'm not sure why the container for this website wasn't extending to the bottom no matter what I tried. Finally I tried setting the div I wrapped the whole site in as "position:absolute;" and then the container for the site content as "position:relative;" and then the footer to "position:absolute; bottom:0;" 
 
#####Sizing:
The sizing of the panels. I tried to make the website work with the specified dimensions for the hwk but I ended up ditching the width of the outer container. I prefer the extra space between the main content area and the social media panel. I used width percentages to accomdate for different screens and monitor sizes.

##### Heroku:
This website can be found hosted on heroku here:
http://arnold-lei-rcb-portfolio.herokuapp.com/index.html

### Things I learned



