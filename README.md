Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

# Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
```

1. **const:** const should be used whenever a function expression is assigned to a variable.
2. **The function name:** The name you choose for the function.
3. **Parameters:** Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
4. **The arrow syntax:** Indicates that this will be a function.
5. **The body:** The statements that make up the function itself. Surrounded by curly braces.

**_Example:_**

```javascript
const greet = (name) => {
  console.log('Hello, ' + name + '!')
}
```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does.
>
> > Examples include
> >
> > > `fetchData( )`,
> > > `calculateArea( )`,
> > > or `printReport( ).`

# Calling a function

To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

**_Example:_**

`greet('Alice');` // Outputs: Hello, Alice!

# Return values

Functions can process data input and output a value using the _return_ keyword.

**_Example:_**

```javascript
const addNums = (numA, numB) => {
  return numA + numB
}
```

`const total = addNums(2, 4);`

`console.log(total)` // Expected value: 6

For more information on functions and how they are used in JS, check out the MDN docs.
[MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

![Image](https://www.google.com/imgres?q=javascript%20image&imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2F9%2F99%2FUnofficial_JavaScript_logo_2.svg%2F1200px-Unofficial_JavaScript_logo_2.svg.png&imgrefurl=https%3A%2F%2Fsimple.wikipedia.org%2Fwiki%2FJavaScript&docid=0LxdHiOIFqO5iM&tbnid=xJB_tNCymTHzpM&vet=12ahUKEwjcqv-vnPCIAxVzS_EDHYHJKIsQM3oECBgQAA..i&w=1200&h=1200&hcb=2&ved=2ahUKEwjcqv-vnPCIAxVzS_EDHYHJKIsQM3oECBgQAA)

# h1

## h2

### h3

#### h4

##### h5

###### h6

This text is **bold**. This text is also **bold**.

This text is in _italics_. This text is also in _italics_.

This text is **_bold and italicized_**. This text is also **_bold and italicized_**.

- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
    - Subitem 2.2.1

1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
