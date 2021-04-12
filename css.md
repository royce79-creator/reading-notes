# CSS Learning and Notes
### Chapter 10 
- To understand CSS you have to know how to think what's inside the box. 
- CSS Associates style rules that pertain within HTML. 
For example: 
``` 
    p {
        font-family: Arial;}
    "p" is the selector and "font-family: Arial;" is the declaration. 
```
- Another thing is that CSS also affects the way elements are displayed. For example: 
```
h1, h2, h3 { 
    font-family: Arial; 
    color: blue
color is the "property" and "blue" is the value. 
}
```
### Using External CSS 
- link refers to where to find a css file and does not requires a closing tag. 
- href specifies a path for the CSS file that is usually titled as css or syle format ex: syle.css witin VS code. 
- type is an attribute specifies the type of document it is being linked to the value. 
- rel refers to the specifics of the realtionship, this should normally be called stylesheet when referring to a CSS file. 

### Using internal CSS 
- style is the way to useing a tag that can exist within HTML when wrtiing out your code. 

### CCS Selectors 
- Below is an example of the CSS selectors. 
``` 
.class	.intro	Selects all elements with class="intro"
.class1.class2	.name1.name2	Selects all elements with both name1 and name2 set within its class attribute
.class1 .class2	.name1 .name2	Selects all elements with name2 that is a descendant of an element with name1
#id	#firstname	
```