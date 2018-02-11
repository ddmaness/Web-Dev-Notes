# Shay Howe Advanced CSS and HTML

## performance and Organization

What are three major concerns when considering the strategy and structure of the development code base?

whats one common strategy for seperating styles based on intent?

seperating styles into directories based on intent instead of by page is helpful because it forces you to 
think of sites a ________________ instead of individual pages.

what three directories can most css files be seperated into?

what should the base directory of css styles include?

what should the components directory of css include?

what should the modules directory of css styles include?

What are the two main principles behind OOCSS?

What methodology works well alongside SMACSS?

What are three reasons for keeping css selectors short?

Define "key selector"

why should you avoid prefixing a class with and element selector?

What are two methods for reducing the size of html, css files being sent from the server?

why should you not scale down a larger image with the height and width attributes?

What are four ways to reduce the number of http requests a page makes when loading?

Whats on reason js files should be included at the bottom of html before the closing body tag?

What are two situations when the js file should actually be included at the top along with the css files?

Describe the practice of image spriting and why it is helpful in reducing the # of http requests?

What are the advantages and disadvantages of using a data uri for images?

what file must be included to both gzip and cache files

what files are commonly cached for a month?

what files are commonly cached for a year?

Why must version numbers be used if you change a file you set to cache?


## Positioning

Describe the reasons for clearing floats and the advantages/disadvantages of each method

Compare and contrast absolute relative, and fixed positioning

the higher the value of the z index the ___________ the element is positioned.

## Complex Selectors

Describe the decendent selector and how to utilize it.

Describe the direct child selector and how to utilize it.

Describe the general sibling selector and how it is used.

Describe adjacent sibling selector and how it is used.

Describe the attribute present selector and describe how it is used.

Describe the atrribute equals selector and describe how it is used.

Describe the attribute contains selector and how to use it.

Describe the attribute begins with selector and how to use it.

Describe the attribute ends with selector and how to use it.

Describe the attribute spaced selector and how to use it.

Describe the attribute hyphenated selector and how to use it.

Decribe the link psuedo-classes and how they are used.

Decribe the Action psuedo-classes and how they are used.

Decribe the user action psuedo-classes and how they are used.

Decribe the user interface state psuedo-classes and how they are used.

Decribe the structural and position psuedo-classes and how they are used.

Describe the difference between the -child and -of-type pseudo selectors.

what is the equation that can be used in the nth psuedo selector and what does each variable represent?

Describe the target psuedo class and how it is used.

Decribe the empty psuedo-class and how it is used.

Describe the negation pseudo-class and how it is used.

What are "psuedo-elements"?

Decribe the textual psuedo-elements and how they are used.

Decribe the Generated Content psuedo-elements and how they are used.

Decribe the fragment psuedo-element and how they are used.

## Responsive Web Design

what is the equation for calculating a fixed length unit(px) and converting it to relative length units while
maintaining the proportions

What are the three logical operators that can be included in media queries?

what css3 assets tend to be slow to render on mobile devices and one may consider reducing/excluding their use
to desktop browsers via media queries?

What is one quick way to insure that media scales down as its container shrinks?

Describe the workaround for getting embedded media (iframes) to respond to changes in its parent elements size.

## Preprocessors

What is haml and why is it useful?

What is sass and why is it useful?

what is the similarities/differences between mixins and extends in sass?


## Transforms

What values are accepted by the transform property?

What is the "transform-origin" property?

Double check for desired outcome when using transform-origin along with __________________ .

the perspective property is comparable to the idea of a _______________________ in a 3d drawing.

when should you apply the perspective property to individual elements vs parent elements?

the higher the perspective length value the __________________ the percieved depth.

What property allows you to change the location of the vanishing point when using the perspective property?

What values of the transform property allow you to rotate a element on a 3d plane?

what transform values allow you to scale and translate in 3d?

What is the one transform property that does not have a 3d equivalent?

Shorthand 3d transforms require a knowledge of ________________.

To ensure that a child element that is being 3d transformed inside of a parent element that is also being 3d transformed
appear in their own 3d plane you must use _______________________.

How do you prevent the back of an element from showing when rotated backwords?


## Transitions & Animations

What are the four transition related properties?

WHat are the various keywords of the transition-timing-function and what do each mean?

how do you create custom timing functions?

what properties are declared along with animation and what does each do?

What is the animation-play-state property and how is it used?

What is the animation-fill-mode property and how is it used?

What are the order of values when using the animation shorthand?


