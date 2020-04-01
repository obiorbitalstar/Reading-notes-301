# Grid Layout
The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.
A grid layout consists of a parent element, with one or more child elements.

An HTML element becomes a grid container when its display property is set to grid or inline-grid.

exapmle : 

```
.grid-container {
  display: grid;
}
// or 
.grid-container {
  display: inline-grid;
}
```
when using grip the sites kinda switchs the a big table with columns and rows 
the space between the boxes of the grid are called gaps 
there is column gaps and row gaps 

you can adjust the size of said gap using grip css properties like this 
```
.grid-container {
  display: grid;
  grid-column-gap: 50px;
}
// there is also grid-row-gap and just grid-gap 

```
The lines between columns are called column lines.
The lines between rows are called row lines.
Refer to line numbers when placing a grid item in a grid container like this 

``` 
.item1 {
  grid-column-start: 1;
  grid-column-end: 3;
}
```


(w3 was used to get more info on the subject and the code sinppts)

