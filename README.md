# ceaser-sass
Sass function that returns various Ceaser easing methods

##Usage

SCSS
```.selector {\n
  transition-timing-function: ceaser("easeInOutQuad");\n
}```

CSS Output
```.selector {\n
  transition-timing-function: cubic-bezier(0.455, 0.03, 0.515, 0.955);\n
}```
