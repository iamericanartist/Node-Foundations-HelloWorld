# Hello, World!
## Node Foundations / Hello World


![Hello World!](helloWorldScreen.jpg?raw=true "Hello World! Screenshot")
***

## Introduction

[Node.js](https://nodejs.org/) is a runtime environment for developing
applications in JavaScript outside of the browser. Node.js is most commonly used
in a
[command-line interface](https://en.wikipedia.org/wiki/Command-line_interface)
to build command-line applications or web servers. After installing Node.js, you
are able to execute a JavaScript file with Node.js using the `node` command
followed by the name of the file.

Example:

```bash
node myJavaScriptFile.js
```

The JavaScript contained in the file executed in a Node.js environment should
similar to a JavaScript file written for the browser. You have access by default
to all of JavaScript's primitives, standard libraries like `Math` and `Date`,
and newer versions of Node.js include many
[ES6/ES2015+ features](http://node.green/) like Template Literals, Arrow
Functions, and Destructuring.

However, since there isn't a visual interface defined in Node.js, there are some
things that you may be used to being available in a browser, but are not
available in Node.js. These features are called
[Web APIs](https://developer.mozilla.org/en-US/docs/Web/Reference/API).

For example, in a browser environment, there is a global `document` object that
has methods for interfacing the Document Object Model (DOM). Without an visual
interface, a DOM is not available so this object does not exist.

Additionally, in a browser, you can create a alert popup box with
`alert('This is an alert message')`. Again, since there is no ability to "popup"
in the terminal, the alert function is not available.

One feature that is commonly used for feedback of command-line applications
written in Node.js is the
[`console`](https://developer.mozilla.org/en-US/docs/Web/API/Console) methods
like `console.log`. While the global `console` object is considered a
[Web API](https://developer.mozilla.org/en-US/docs/Web/Reference/API), it has
been reimplemented in Node.js for convenient access to the terminal output.

In a browser, the global `console` object provides access to the developer tools
console. It is used to add information for debugging purposes and is not
normally visible visitors unless they open the web console. In Node.js, there is
a global `console` object as well but is used to output text to the terminal.
However, rather than using a web console, it uses the terminal's [standard
output stream](https://en.wikipedia.org/wiki/Standard_streams).

Adding the operation `console.log('This is a log message')` will output
`This is a log message` to the terminal through the stdout interface along with
an invisible [Newline](https://en.wikipedia.org/wiki/Newline) character `\n`
for any additional commands that may follow.

## Topics Covered

-   Node.js environment
-   Command Line applications
-   Global `console` object

## Requirements

For this exercise you will create a
[Hello World program](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program).

Create a JavaScript file to act as a Node.js program named `01.js`. The file
should contain JavaScript code to output the phrase "Hello, World!" to the
terminal through the stdout stream.

Expected:

```bash
$ node 01.js
Hello, World!
```

## Additional Reading

-   [Node.js](https://nodejs.org/)
-   [Command-line interface](https://en.wikipedia.org/wiki/Command-line_interface)
-   [Node.js ES2015 Support](http://node.green/)
-   [JavaScript Web APIs](https://developer.mozilla.org/en-US/docs/Web/Reference/API)
-   [Console object](https://developer.mozilla.org/en-US/docs/Web/API/Console)
-   [Standard streams](https://en.wikipedia.org/wiki/Standard_streams)
-   [Newline](https://en.wikipedia.org/wiki/Newline)
-   [Hello World program](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program)


***
[Original Exercise Link](https://github.com/nashville-software-school/node-milestones/blob/master/01-foundations/exercises/01-hello_world.md)
