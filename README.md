# JavaScript Abstract Syntax Tree Diagram

This shell script uses Google Closure Compiler and Graphviz to draw a
diagram of the AST of any JavaScript file.

For instance for a file called `hello.js` that contains these two lines of code:

    let hiWorld = 'hello world!';

    console.log(hiWorld);

The script would produce the following AST diagram as a PNG file named `./hello.js_ast_diagram.png`

<img src="https://i.imgur.com/z3JHFmr.png" alt="the abstract syntax tree of the JavaScript code shown above">
