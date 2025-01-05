<link rel="stylesheet" href="src/_all.css">

MyCSS.style
===========

The idea behind this is a very basic CSS theme.

...like, *really* basic. On the bright side, it uses the latest CSS features:

- set theme color(s) directly using CSS varaibles
- light / dark support
- flex box layouts

It overrides the default HTML elements styles, no need to add classes.

Variables
---------

Typography
----------

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

> Some quote

Some paragraph with *italic*, **bold** and ***italic bold***. 

----

Buttons
-------

<div>
    <button>Default Button</button>
    <button neutral>Neutral Button</button>
    <button info>Info Button</button>
    <button success>Success Button</button>
    <button warning>Warning Button</button>
    <button danger>Danger Button</button>
</div>

```html
<button>Default Button</button>
<button neutral>Neutral Button</button>
<button info>Info Button</button>
<button success>Success Button</button>
<button warning>Warning Button</button>
<button danger>Danger Button</button>
```

---

Inputs
------


<form>
    <label for="text-input">Input:</label>
    <input type="text" id="text-input" name="text-input">

    <label for="checkbox-input">Checkbox:</label>
    <input type="checkbox" id="checkbox-input" name="checkbox-input">

    <label for="radio-input">Radio Input:</label>
    <input type="radio" id="radio-input" name="radio-input">
    <input type="radio" id="radio-input" name="radio-input">

    <label for="select-input">Select Input:</label>
    <select id="select-input" name="select-input">
        <option value="option1">Option 1</option>
        <option value="option2">Option 2</option>
        <option value="option3">Option 3</option>
    </select>

    <label for="textarea-input">Textarea Input:</label>
    <textarea id="textarea-input" name="textarea-input"></textarea>
</form>

```html
<form>
    <label for="text-input">Input:</label>
    <input type="text" id="text-input" name="text-input">

    <label for="checkbox-input">Checkbox:</label>
    <input type="checkbox" id="checkbox-input" name="checkbox-input">

    <label for="radio-input">Radio Input:</label>
    <input type="radio" id="radio-input" name="radio-input">
    <input type="radio" id="radio-input" name="radio-input">

    <label for="select-input">Select Input:</label>
    <select id="select-input" name="select-input">
        <option value="option1">Option 1</option>
        <option value="option2">Option 2</option>
        <option value="option3">Option 3</option>
    </select>

    <label for="textarea-input">Textarea Input:</label>
    <textarea id="textarea-input" name="textarea-input"></textarea>
</form>
```