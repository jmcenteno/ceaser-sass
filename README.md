# ceaser-sass
Sass function that returns various Ceaser easing methods

##Usage

SCSS
```.selector {
  transition-timing-function: ceaser("easeInOutQuad");
}```

CSS Output
will produce
```.selector {
  transition-timing-function: cubic-bezier(0.455, 0.03, 0.515, 0.955);
}```
