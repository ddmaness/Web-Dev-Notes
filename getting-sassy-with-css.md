# Getting Sassy with CSS

## Section I: Why Sass?

What is Sass?

What are the issues with css that Sass addresses?

What are the two SassScript Syntaxes and what is the major difference?

## Section II: The Sass Workflow

What is the terminal command for running (compiling) Sass to Css?

What is is the terminal command to get css to watch for changes and autocompile?

What will this command do? $ sass --update source.scss:output.css

What will this command do? $ sass --watch source.scss:output.css

What will this command do? $ sass --style expanded source.scss:output.css

Why are browser dev tool source maps helpful when working with sass?

## Section III: Sass Basics

How could the following code be rewritten utilizing Sass nesting?
.navigation {
  float: right;
}

.navigation li {
  display: inline-block;
  list-style-type: none;
  margin-left: 1.5em;
}

.navigation a {
  display: block;
  text-decoration: none;
}

in general sass nesting should not go further than ____ levels deep.

What character allows you to reference the current parent selector(s) in sass?

In sass The & selector can follow other selectors. This will ________________ the parent 
element's (&) styles when it exists within the preceding selector.

in sass, The & selector can also be ____________ with strings.
PERFECT for BEM, child elements, states, and modifications.

in sass, The & contents can also be accessed as a ________________
and used in SassScript.

in Sass, namespaced properties can be ___________________.

What advantages does Sass's @import have over css's native @import

if no path is given to the Sass's @import statement, it is assumed that the file is...

What would this command in the terminal do? $ sass sass/ css/

What is a sass partial and how is it designated?

what are three common practices for sass imports?

How do you import groups of files in sass

How are variables declared and referenced in sass?








## Section IV: Advanced Sass




