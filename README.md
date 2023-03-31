# Codecademy - Flexbox-Project
Codecademy External Project - Flexbox (The Cozy Tea Website)

Objective: Build a sample homepage for a client (The Cozy Tea) and master Flexbox layout model in CSS

CSS Flexbox Model Main concepts:
Flex is a value for 'display' property.

.container {
  display: flex;
 }
 // This will give us a .container element with its children having flex behavior.
 
 .container {
   display: inline-flex;
 }
  
  // This will now give a container and its children display of flex.
  
  Most common uses for flex: organize divs (center them, space them out) instead of them taking width 100% (block by default).
  
  Important properties used with flex: 
  
  display: flex;
  justify-content: flex-start | flex-end | center | space-around | space-between ;     (horizontal position)
  
  justify-self: flex-start | flex-end | center | space-around | space-between ;        (horizontal position, self)
  
  align-items: flex-start | flex-end | center | stretch ;                              (vertical position)
  
  align-self: flex-start | flex-end | center | stretch ;                               (vertical position, self)
  
  align-content: flex-start | flex-end | center | space-between | space-around ;       (vertical alignment of children's multiple lines)
  
  flex-wrap: nowrap (default) | wrap | reverse-wrap ;                                  (controls creation of new line if container is too small)
  
  
  
  Flexbox model gives the items (and can also give the parent) two axes: main and crossing.
  We can change what is the main axis (horizontal by default) by using flex-direction or flex-flow.
  
  flex-direction: row (default) | column
  
  flex-flow: row wrap | column wrap | row nowrap ... 
  
  
  
  
