# Responsive Web Design Certification: HTML and CSS
## Course: Learn Basic CSS by Building a Cafe Menu

## CSS - Cascade Style Sheets
Review and rebuild HTML code from previous sub-course. <br>

## Style Element
Inside _head_ element <br>
Can set _properties_ <br>
Example of a _type selector_: <br>
```
element {
 property: value;
}
```

Can group selectors: <br>
```
selector1, selector2 {
  property: value;
}
```

Best practice is to keep styles in separate files. <br>
Example _style.css_ <br>

```
<link rel="stylesheet" href="styles.css"/>
```

_meta_ element with _content_ attribute <br>
_div_ element is used mainly for design layout purposes <br>
CSS _width_ property <br>
_id_ selector <br>
"You can use the id selector to target a specific element with an id attribute. An id selector is defined by placing the hash symbol # directly in front of the element's id value." <br>
```
#cat {
  width: 250px;
}
```

CSS comment: <br>
```
/* comment here */
```

"A class selector is defined by a name with a dot directly in front of it" <br>
More common to use a class selector than type and id selectors to style elements <br>
```
.class-name {
  styles
}
```

_<article>_ element <br>
_article_ elements commonly contain multiple elements that have related information <br>
class name <br>
_block-level_ elements vs _inline_ elements <br>

```
.class p { }
```
...some nonsense of positioning _p_ elements side by side with no space/break in code... <br>
