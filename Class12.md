# EJS Partials
Partials come in handy when you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.

usually we put it inside a folder named partials inside the veiws folder , and in this partials file we put the snippts of code that we want to use inside .ejs files 
lets say u have a header for your website (the usual case of every website) it dose not make sense to rewrite the same code for the header in every page or ur site 
u create a header.ejs file and put the html code for a website header inside it and all it in the other pages where u want to apply this header 
to use partials we use the command 

```
<%- include( PARTIAL_FILE ) %>  // dont forget the dash at the start

```



