# jQuery 
jQuery is a javascript file that u add to your web pages it allows us to find elements using css selectors and perform tasks on them 
exapmle : 
```
$('someID');

```
the dollar sign is how we iniate a jQuery object then we add the id of the element we want to select
we can also choose diffrent elements without spicifying an id 
selector rules from the css and how to get the elements we want apply here.

using jQuery u can add , remove , apply animations or simple events to an element 
u can get values from html elements like 
```
var x = $('p').html();
```
in the last snippit of code we brought a single p element and stored the value it shows inside the varabiable that we named x 
u can get mutiple elements not just one 
``` 
var y = $('li').html(); 
```
with this we got all the values from the list elements inside the html file 

jQuery also have a nice method named ".ready()" 
it checks if the page element is ready or not before excuting any code 
### LOADING JQUERY FROM A CDN 

```
<script src=" //ajax .googl eapi s . com/ ajax/l i bs/ jquery / 1.10 . 2/ jquery .min. js ">
</ script>

<script>
window .jQuery 11 document. write (' <script src=" j s/j query- 1.10 . 2 . j s 11 ><\jscri pt> ' )
</script>

```
(this code was copied from the book for later use) 

# Pair Programming 
pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code. 

### Why pair program? 
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness
 
(this was copied from the site provided by read materials for lack of the ablility to explain it any more than this 
just watned to menthon that i fully understand and read the form just dont want to copy past everything)
