# Animation + Invisibal-Card
In this project I will use parallax effect Animation to build nice profile card and have multiple background capabilities. Project will be built based on HTML and CSS.
* Hover the astronaut image for 3s, 
* So when the 1st transition of with color of box shadow end. 
* Then after 0.5s the card will move down. 
* Card will display nicely. 
* Animate multiple background each layer is set to move different distances.
* Start background the furthest layer in the back is moving slowest.
* Then the start on top of that layer is moving a little bit faster.
* The planet rolls a long it's moving faster then both of start layers.
* Cool 3D depth perception.

* [Link to project hosted on Netlify](https://css-animate-card-profile.netlify.com/)
* [Link to project hosted on Github](https://github.com/kanjamad/Parallax-effect-Animation)

![website-gif](images/animate.gif "website-gif")

### Invisible-card repo:
Modify this project by change background to be parallax effect Animation. 
* [Link to Invisible-card project hosted on Github](https://github.com/kanjamad/Invisible-Card)

### @keyframes rule
@keyframes animate-background{ from {} to {} }
* horizontal (lef-right) set to 120% : that way the planet starts off the screen.
* vertical axis (up-down) set to 70px : down in to the div 
* Render : animate it "from" original coordinates, Set background-position: 120% 70px
* "to" Where you want to animate it to, Set background-position: -20% mean to go from the right-left will move it all the way across screen and will keep this at 70px


```
#banner{
backgroung-image: url(plant.png);
background-position: 120% 70px;
background-repeat: no-repeat;
animation: animate-background linear 50s infinite;
}

@keyframes animate-background {
  from {
      background-position: 120% 70px;
  }

  to {
    background-position: -20% 70px;
  }
}
```

### Additional Resources
1. <a href="https://www.kisspng.com/free/roket.html" target="_blank">images roket</a>
2. <a href="https://www.w3schools.com/cssref/css3_pr_animation-keyframes.asp" target="_blank">CSS @keyframes Rule</a>
3. <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes" target="_blank">@keyframes</a>

