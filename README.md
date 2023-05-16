<!DOCTYPE html>
<html>
<head>
  <title>Coding in JavaScript</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <header>
    <h1>Coding in JavaScript</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#introduction">Introduction</a></li>
      <li><a href="#syntax">Syntax</a></li>
      <li><a href="#variables">Variables</a></li>
      <li><a href="#functions">Functions</a></li>
    </ul>
  </nav>

  <main>
    <section id="introduction">
      <h2>Introduction</h2>
      <p>
        JavaScript is a popular programming language used for web development. It is primarily used to add interactivity and dynamic functionality to websites.
      </p>
      <p>
        JavaScript can be used on both the front-end and back-end of web applications. On the front-end, it can manipulate the Document Object Model (DOM) to modify web page content dynamically. On the back-end, JavaScript can be executed using platforms like Node.js to handle server-side operations.
      </p>
    </section>

    <section id="syntax">
      <h2>Syntax</h2>
      <p>
        JavaScript has a C-like syntax with curly braces and semicolons. It is a dynamically typed language, meaning you don't need to declare variable types explicitly.
      </p>
      <pre><code>
        // Example JavaScript code
        function greet(name) {
          console.log("Hello, " + name + "!");
        }

        greet("John");
      </code></pre>
    </section>

    <section id="variables">
      <h2>Variables</h2>
      <p>
        JavaScript variables are used to store data. They can hold different types of values, such as numbers, strings, booleans, arrays, and objects.
      </p>
      <pre><code>
        // Variable declaration and assignment
        let age = 25;
        const name = "Alice";
        var isLoggedIn = true;
      </code></pre>
    </section>

    <section id="functions">
      <h2>Functions</h2>
      <p>
        Functions in JavaScript allow you to group code into reusable blocks. They can be defined using the <code>function</code> keyword and can accept parameters and return values.
      </p>
      <pre><code>
        // Function declaration
        function addNumbers(a, b) {
          return a + b;
        }

        // Function invocation
        let result = addNumbers(3, 7);
        console.log(result); // Output: 10
      </code></pre>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Your Website. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html
