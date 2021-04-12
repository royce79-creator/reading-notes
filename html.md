# html Learning
## Chapter 18
- html stands for hypertext markup language. 

## Site maps
- Usually begins with a homepage that will lead to other pages that are linked to the home page. 
- Used to ensure that you are focusing on the things that your visitors will be coming to see yuor site for. 

## Wireframe example: 
- [wire frame](https://www.codementor.io/@nicolesaidy/getting-started-with-wireframes-du107vuh7)
- This will show the basics of a wire frame when using html, shows an exoskeleton of the site and hopw thigns will look within the boxes. 

## Getting Messages accross
### Content
-  Ensuring that people will be able to interact with the site and allow you to organize the content you need. 
1. A masthead or logo
2. Links to navigtate 
3. Login or memebrship
4. Ability for user comments

### Prioritizing
- Create a visual heirarchy, easliy digestable content.

### Organizing
- Make sure to use grouping in order to have content that is easy to follow and alows grouping with certain boxes that will relate to one anohter. 

## Chapter 17
- Traditional HTML layouts usually show 
- Below is an example of what a usualy html formatted page would look like. 

```
<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>

<h2>CSS Layout Float</h2>
<p>In this example, we have created a header, two columns/boxes and a footer. On smaller screens, the columns will stack on top of each other.</p>
<p>Resize the browser window to see the responsive effect (you will learn more about this in our next chapter - HTML Responsive.)</p>

<header>
  <h2>Cities</h2>
</header>

<section>
  <nav>
    <ul>
      <li><a href="#">London</a></li>
      <li><a href="#">Paris</a></li>
      <li><a href="#">Tokyo</a></li>
    </ul>
  </nav>
  
  <article>
    <h1>London</h1>
    <p>London is the capital city of England. It is the most populous city in the  United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
    <p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.</p>
  </article>
</section>

<footer>
  <p>Footer</p>
</footer>

</body>
</html>
```
### Headers & Footers
- exampoles of headers and footers. 
``` 
<footer>
    &copy; 2021 Connor's Kitchen
</footer>
``` 
```
<header> 
    <h1>Connor's kitchen</h1>
</header>
```
### Navigation 
- Navigation tage would be used for link to send you to another page that you would be able to head to. 
