# Section-12-Space Invaders (Posted: 4/26/2019)

## Introduction

Today you will be using the same Space Invaders code
base from Section 9. You will be modifying the solution 
file to use lambdas instead of private classes. 

## Assignment

### Setup
Clone this repository, and add it to your local eclipse workspace.

Before starting, run the SpaceInvaders file as a Java Application to 
ensure that there are no errors, which will have the full functionality
as the previous section upon completion. 

### Editing the Code
For this section, you will need to modify the code, so that lambdas are 
used in place of mouse event handlers. Because the EventHandler classes
are primarily concerned with the handle method, you will need only 
pass an "event" parameter through your lambda, using the following style.
```canvas.setOnMouseMoved((event)->{...});```, where the internal of 
the curly braces is the code you would normally find in a handle method. 
Use this so that the two classes you wrote last section are no longer 
needed. 

Note that there is an additional privatized class, which will need to 
remain in order for the animation to work appropriately. The code which 
deals with the Timeline will need to remain the same, however it is appropriate
for this code to be moved. 
