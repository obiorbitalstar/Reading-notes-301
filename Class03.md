# Mustache.js with Node and Express
Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object 
It is often referred to as “logic-less” because there are no if statements, else clauses, or for loops. Instead, there are only tags

mustache.js is an implementation of the mustache template system in JavaScript. It is often considered the base for JavaScript templating 

example of using mustach:

```
Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn
// this was copieed from the provided site about the subject

``` 
note:Mustache is NOT a templating engine. Mustache is a specification for a templating language 

## Mustache-Express 
to use mustach with node and express with use mustach express, Mustache Express lets you use Mustache and Express together easily.
after installing mustach we can start using it on our html files 
example: 
```
res.render('hello', {"name": "Sherlynn"})

```
Whereby the first parameter ‘hello’ refers to the hello.html file (no need to include the extension (e.g. hello.html) as it has been previously set as html.
The second parameter would be the JSON data itself. We can also pass in a variable representing the data, for example:

```
var nameObject = {"name": "Sherlynn"}
res.render('hello', nameObject)

```

# flexbox
The Flexbox Layout aims at providing a more efficient way to lay out, align and distribute space among items in a container, even when their size is unknown and/or dynamic (thus the word “flex”).
A flex container expands items to fill available free space or shrinks them to prevent overflow.
Most importantly, the flexbox layout is direction-agnostic as opposed to the regular layouts (block which is vertically-based and inline which is horizontally-based)

(the rest of the article is flexbox properties and commands, i bookmarked the article as a cheatsheet but didnt find a point in also copying them here ).
