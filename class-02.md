# Class Reading note 2 
- This enatilas all that has to do with the second reading assignment given in class 201. 

## Chapter 2: **Text** (pg. 40-61)
- tags are known as markup langauge. 
1. **Structural Markup**: The element that you can use to describe both headings and paragraphs. 
2. **Semantic Markup**: This provides extra info; such as when emphasis is placed in a sentence, or if somehting you writeen has quotations, also meaning of acronyms, etc.
- HTML has 6 levles of headings, use this when structuring what heading are to stand out more than the others. Viusally you want to make sure this looks easy on the eyes. 
```
<h1>, <h2>, <h3>, etc. 
```
- The paragraphs that you make in HTML have the (p) tag that is shown below.
```
<p>hello world!</p>
```
- Used to house the body text that you have written out for lets say an article or working after you heading. 

**Bold** & *itlaics*:
- Pretty straight forward for this one make sure to use the i or b beginning and closing tags like this: 
``` 
<b>this is bold</b> 
<i>This would be italics</i>
```
### Superscript & Subscript
- the tag for a superscript is used for words like 4th but with elevating the "th" to the top right of the number. 
- Also below a subscript would be used a lot for numbers that need to sink below the text, kind of like H2O. 
```
<p>My name is Connor Boyce I was born on the 7<sup>th</sup> of Mrach</p>
<p>Water is really good, the real name for it is H<sub>2</sub>O, isn't that cool?</p>
```
**White Space** 
- a lot of the time white space is used only when in the HTML of the page to make it easier to follow. Even if you put a lot of pscaes the result of the page will just show as a space rather than just making toom uch spacing for no reason. 

### Line Breaks & Horizontal Rules
- This will be super useful for you when you want to add a line break between text in your paragraphs. 
```
<p>Today was a good day to code<br />Maybe one day I'll be an expert in this.
``` 
- When using the tag below it will make a horizontal line that will cut between the lines of text that you are making. Useful when changing topics in sentences. 
``` 
<p>The day was super bright</p>
<hr />
<p>This would not last sicne night was coming</p>
```

### More on Semantic Markup
- There is the tag "strong" this will add bolding to whatever is bewteen that tag. Strong = big strong letters. 
- then there is the "em" tag this will hsow emphasis on working and portray a different meaning. by default show a italic lettering. 
- Quotations are important as well. This is defined by "q" or by "blockquote" which will show a quote in the paragraph while a "blockquote" will show just the quote indented by itself. 
```
<em></em> and then there is <strong></strong>
``` 

### More Semanitc write up
- using addresses to be able to have clickable ways to ge your emails to show as a link to use. 
```
<address>
Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```
- There is then changes you can make that will cross out the word you don't want in text and underline the wording that was suppose to be inserted. 
```
<p>My favorite color is <del>blue</del> <ins>red</ins>!</p> 
```
- There is then the "s" tag that is used to makr off what was originally used and replace the text with correct values. 
```
<p><s>Only 50 tickets left!</s></p>
<p>SOLD OUT!</p>
```

## Chapter 10 Introducing CSS (pg. 226-245)
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
- Make sure to looks at Pg 238 to see what selectors looks like and what they can do. 
- CSS Rules for Cascading and Inheritance are good things to remember as well. Look to pg. 239-240. 

## Shapter 2 Basic Javascript Instructions (pg. 53-84) 
- All statements should end with a semicolon to indicate the end of a statment in javascript. 
- Javascript is Case sensitive so be careful when referring to certain things since that will effect how the computer interprets it. 
- Comments in javascript are super useful to explaining what the code is trying to accomplish. Usually represented by "//". 
- In the example below we see what a variable is and what it is assigned in a value. 
``` 
var quantity;
quantity = 4; 
``` 
**Data Types** 
- There are different types of data types like boolean, numbers and string. (Pg.62)

Cureently a WIP
