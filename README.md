
## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

getElementById is a js DOM method used to select single HTML element by its unique id.

 getElementsByClassName is a js DOM method used to select elements by their class name.

querySelector / querySelectorAll? are JavaScript DOM methods used to select elements using CSS selectors.


### 2. How do you create and insert a new element into the DOM?


DOM (Document Object Model) means the entire HTML structure of a webpage.
With JavaScript we can create new elements and add them to the page.

let newElement = document.createElement("p");


### 3. What is Event Bubbling? And how does it work?

document.getElementById("child").addEventListener("click", function() {
    console.log("Button clicked");
});

### 4. What is Event Delegation in JavaScript? Why is it useful?


document.getElementById("list").addEventListener("click", function(event) {
  if (event.target.tagName === "LI") {
    console.log("Item clicked:", event.target.textContent);
  }
});
### 5. What is the difference between preventDefault() and stopPropagation() methods?

---


