### javascript fund

1. var is global scope, let is block scope
2. passing callback function as param

```javascript
function processUserInput(callback) {
  const name = "Alice";
  callback(name);
}

function greet(name) {
  console.log(`Hello, ${name}!`);
}

processUserInput(greet); // Hello, Alice!
```

### closure
Closure is a feature where innerfunction able to access outerfunction variables,  even after outer function completed.
```javascript
import "./styles.css";

function setupClickHandler() {
    let clickCount = 0;

    // Set up the click event listener
    document.getElementById("myButton").addEventListener("click", function () {
        clickCount += 1;
        console.log(`Button clicked ${clickCount} times`);
    });
}

// Initialize the click handler when the page loads
setupClickHandler();
```

### Why React


