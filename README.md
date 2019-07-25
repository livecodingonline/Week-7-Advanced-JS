# Week-7-Advanced-JS
## Advanced Javascript and DOM Manipulation

##### In week seven we will discuss the following topics:
- Event listeners
- Higher order functions
- Play sounds on a website
- Advance Objects (methods, dot notation)
- Switch statements
- Keyboard event listeners
- Callbacks, respond to events
- Animations

### Event listeners

+ Although you can start functions when your page loads, many times you'll want to start functions when a user clicks a link, enters a form, scrolls, moves his or her mouse over an object, or does something else. These actions are called events. You can set specific functions to run when the user performs an event. These functions "listen" for an event and then initiate the function.

- To understand how event listeners actually works let's check out a simple example:
```javascript
     //creating a button 
     const btn = document.createElement('button')
     document.body.appendChild(btn)
     btn.innerText = 'this button has event listener'

    // Assigning event handlers to the button
    btn.onclick = secondFunction;

    // Defining custom functions  
    function secondFunction() {
        btn.style.backgroundColor = 'yellow';
        console.log('second function executed');
    }
```

- [more about event listeners](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)


### Higher order functions

+ Higher-order functions are functions that take other functions as arguments or return functions as their results.

+ Taking an other function as an argument is often referred as a *callback function*, because it is called back by the higher-order function. This is a concept that Javascript uses a lot.

+ For example, the *map* function on arrays is a higher order function. The *map* function takes a function as an argument.

- a simple example:

```javascript
const double = n => n * 2;

const numbers = [1, 2, 3, 4]

numbers.map(double)

// output: [ 2, 4, 6, 8 ]
```

- [more about higher order functions](https://dev.to/damcosset/higher-order-functions-in-javascript-4j8b)

---

## Sections of this week

- Section 12: [Advanced Javascript and DOM Manipulation](https://www.udemy.com/the-complete-web-development-bootcamp/learn/lecture/12383928#overview)

--- 

#### Kind note:

*We expect you to **always** come prepared to the class on Sunday.*

---