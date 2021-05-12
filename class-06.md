# Reading Notes 06

## Chapter 3 (JS) Object Literals (pg 100-105)
- In an object variable will become **properties**. Properties tell us about the object and what they represent. 
- In an object a function becomes a method, reps the tasks in the object.
- There are keys and then values that are made within the object, keys being the variables and vlues being the data type.
```
var hotel = {
  name: 'Quay',
  rooms: 40,
  booked: 25, 
  checkAvailability: function() {
    return. this.rooms - this.booked;
  }
}
```
- The dot that you see is a member operator. This owuld be the same as using square brackets as well. Refer to page 103. 

## Chapter 5 Document Object Model (pg 183-242) 
- Document Object Model (DOM) specififies how browsers should create a model of an HTML page and how Javascript can access and update the contents.
- DOM tree used with HTML for structure. application programming interface (API).
- DOM tree is the model of a web page.
- There are different ways to interact with the DOM tree by entering certian commands like: 
```
getElementsById()
* uses the vlaue of an element's id attribute (usually unique within the page)
querySelector()
* Uses CSS selector, then returns the first matching element. 
getElementByClassName()
* Selects all elements that have a specific vlaue for their class attribute. 
etc. Look on page 168. 
```
- Adding and removing elements are possibel on the branches you're looking up. 
- From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques. 
- In older browsers, implementation of the DOM is inconsistent (and popular resons for using jQuery).
- Browsers offer tools for viewing the DOM tree. 
