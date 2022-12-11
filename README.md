
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS0hR55oLmudAUGPLtYaoT6FninNxRAvv2XxdKWE0LMuQ&s" align="center">
<br/>

# This repo is made to learn JEST framework

## What is **JEST**?
Jest is the testing framework build by fackbook. It is used to test React App and most commonly javascript with focus of simplicity.

<details><summary>Click here to see a Screenshot of JEST testing:</summary>

<center>
    <img src="./image/Screenshot.png" width="330px">
</center>

</details>

## Pros of testing approch using JEST:
<ol>
<li> FAILING TEST = MOST LIKELY A BUG
<li> Easy to read and understand module / functions
<li> Survives major refactoring
<li> Tests entire app
</ol>

## What is Eslint?
Eslint is the tool that checks your code, analize it and finds common patterns, let's have an example of eslint.
```js
// for example
const a = '1'
// eslint will say "Missing samicolon"
```

<u>

**Eslint is the great example for testing test utilites**
</u>

Eslint support custom rules so you can define your own rule to define a good approch of writing a code in `JavaScript`. Just has an ability called `Eslint Rule Tester`.

<details>
<summary> Click here to see an example of Eslint Rule Tester:</summary>

```js
ruleTester('semicolon', {
    valid: ['var a = 1;','var b = 2;'],
    invalid: [{
        code: 'var a = 1',
        error: 'Missing semicolon'
    }]
})
```
</details>

## Snapshot testing with `JEST`
<dl>
<dt>What is snapshot?</dt>
<dd> - Snapshot means a blue print of component ( part of UI) or we can say an Blueprint of object of data that can be predefined.</dd>

<dt>What is snapshot testing?</dt>
<dd>A Snapshot test renders the UI and takes snapshot of it then we can compare with reference snapshot file and compare both in test so UI does not change unexpectedly! 
</dd>
</dl>

