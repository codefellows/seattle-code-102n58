# Demo: JavaScript in Action

## Demo Instructions

Review the lab. Students will be adding javascript to their own pages.

Start with the html / css site you built in the last class. 

As you go add JS code, show off live JS in the console. Explain briefly what a REPL is, and show them that you can do math, string concatenation, etc very easily.

JS Examples to add to your code base:

1. input
    - Use `prompt` to grab some input from the user (Perhaps the current Hour?)

1. processing (in this case, conditional generation of dynamic content)
    - Using the Hour input, show an `if else` block.

1. output
    - Show students `document.write`
    - Show alternative method of output: `console.log()`

```js
let hourNow = prompt('Please enter the current Hour of the Day');
let message;

if (hourNow >= 18){
    message = 'Whats for Dinner';
else if (houseNow >=12){
    message = 'Whats for Lunch';
} else if {hourNow >= 8}{
    message = 'Whats for Breakfeast';
} else {
    message = 'Might be a little early to eat';
}
    console.log(message);
    // Be sure in HTML to have your script call in a h2 or h3 tag
    // <h2><script src="app1.js></script>
    document.write(message); 
}
```

Ask students how they'd like to integrate dynamic content in their site. Some ideas:

- Prompt for user's name, and show it in a greeting.
- Prompt for age or birthday, and show selective content based on age
- Prompt for the user's city or state, and, for certain values, give specific info (Ranking? Weather guess?).
