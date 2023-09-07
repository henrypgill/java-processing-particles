# Java Processing Particle System Example

See [accompanying exercise](https://www.notion.so/weareacademy/Java-Particle-System-Code-Reading-exercise-4175446bbebb4ef5b235084c03b17744)



# Questions
## What is a `static` method?
    

## What’s Java’s equivalent of JavaScript’s for…of loop?
    

## What does `this` mean?
    

## Explain what `private float size;` means inside `public class Spark`
    

## How is it that we can call circle in Spark’s `display()` even though the PApplet object is not passed to display() as an argument?
    

## What’s a constructor? How do you define one?  How do you call one?  What’s weird with regard to return values here?
    

## Why do some number literals need a suffix of `f` ? (e.g. `0.9f`)?
    

## How do you create an array of size 10, ready to hold references to Spark objects?
    

## How do you create an ArrayList ready to hold references to Spark objects?
    

## What’s a useful difference between java’s built-in arrays and ArrayList objects?
    

## What is the impact of making `createRandomSpark` ”private”?
    

## What would a variables-and-objects diagram look like once this line of code runs in [Main.java](http://Main.java) and before `setup()` runs?  `private Spark[] sparks;`   (Use the debugger to find out.  Draw the diagram.)
    

## What would a variables-and-objects diagram look like once this line of code runs in [Main.java](http://Main.java)  `sparks = Spark.*createSparks*(this, 100, palette);`  (Use the debugger to find out.  Draw an excerpt of the diagram.)



# Tasks

- change how a spark particle **displays** itself.
    - simplest: have it draw as a square, according to its **size**
- change how a spark particle is **updated** over time
    - its **size** should decrease by some small amount every frame (e.g. 1 to 5 pixels)
    - when its **size** becomes smaller than 1 it should be reset to, say, 50 pixels
- assign a new property, `shape`, to each Spark when it is created, randomly “circle” or “square” (just a string).
    - The Processing library does not have a version of random() which picks an element at random from an array, but using search anywhere (`shift, shift`) you should be able to find a method with a name starting with `pick` .
        - hint:

          It’s provided in Utils.java

- Use this property during display of the spark, to consistently either draw that spark as a circle or square.



































bg