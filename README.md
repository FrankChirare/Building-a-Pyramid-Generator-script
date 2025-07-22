# Pyramid Generator

This project generates a text-based pyramid (standard or inverted) in your browser's console using JavaScript.  
Great for learning the basics of arrays, loops, and string manipulation!

## How to Run

1. **Clone or Download the Repository**  
   Make sure you have a `script.js` file on your computer.

2. **Open the Browser Console**  
   - Press <kbd>F12</kbd> or <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>I</kbd> (Windows/Linux)
   - Or <kbd>Cmd</kbd>+<kbd>Option</kbd>+<kbd>I</kbd> (Mac)
   - Select the **Console** tab.

3. **Set Your Parameters**
   - In `script.js`, adjust these variables to change the pyramid:
     - `character` — the symbol or emoji used to build the pyramid (e.g. `"#"`, `"!"`, `"*"`, `"💎"`).
     - `count` — number of rows (positive integer).
     - `inverted` — set to `true` for an upside-down pyramid or `false` for a standard pyramid.

4. **View the Output**
   - Save your changes and refresh the browser.
   - The pyramid will appear in the console as formatted text.

## Example

If you set:
```js
const character = "*";
const count = 5;
let inverted = false;

Your console will display:
    *    
   ***   
  *****  
 ******* 
*********

If you set:
const character = "@";
const count = 4;
let inverted = true;

Your console will display:
*******
 *****
  ***
   *
```
## Tips

 **Play with different characters, counts, and the inverted setting for fun results.**

**This project is a simple, hands-on way to practice JavaScript fundamentals!**
