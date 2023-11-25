# prework-study-guide

<html>
<head>
  <style>
    /* CSS code for styling the webpage */
    body {
      font-family: Arial, sans-serif;
      background-color: white;
    }

    h1,p {
      color: white;
      text-align: center;
    }

    header, footer {
      background-color: darkblue;
      padding: 20px;
    }

    .box {
      width: auto;
      height: auto;
      margin: 20px;
      border: 1px solid black;
      box-shadow: 5px 5px 5px grey;
      display: inline-block;
      vertical-align: top;
    }

    .box h2 {
      text-align: center;
    }

    .box ul {
      list-style-type: none;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Prework Study Guide</h1>
  </header>
  <div class="container">
    <!-- HTML code for creating four boxes with titles and notes -->
    <div class="box">
      <h2>HTML</h2>
      <ul>
        <li>HTML stands for HyperText Markup Language</li>
        <li>HTML is used to create the structure and content of a webpage</li>
        <li>HTML elements are made of tags and attributes</li>
        <li>HTML elements can be nested inside each other</li>
      </ul>
    </div>
    <div class="box">
      <h2>CSS</h2>
      <ul>
        <li>CSS stands for Cascading Style Sheets</li>
        <li>CSS is used to style and layout the webpage</li>
        <li>CSS rules are made of selectors and declarations</li>
        <li>CSS can be applied inline, internally, or externally</li>
      </ul>
    </div>
    <div class="box">
      <h2>Git</h2>
      <ul>
        <li>Git is a version control system</li>
        <li>Git is used to track changes and collaborate on projects</li>
        <li>Git commands are used to create and manage repositories</li>
        <li>Git branches are used to work on different features or versions</li>
      </ul>
    </div>
    <div class="box">
      <h2>JavaScript</h2>
      <ul>
        <li>JavaScript is a programming language</li>
        <li>JavaScript is used to add interactivity and functionality to the webpage</li>
        <li>JavaScript code can be written inside script tags or in external files</li>
        <li>JavaScript variables, data types, operators, and functions are some of the basic concepts</li>
      </ul>
    </div>
  </div>
  <footer>
    <p>© 2023 All rights reserved.</p>
  </footer>
  <script>
    // JavaScript code for displaying the topics and a suggestion in the console
    var topics = ["HTML", "CSS", "Git", "JavaScript"];
    console.log("The topics you learned are:");
    for (var i = 0; i < topics.length; i++) {
      console.log(topics[i]);
    }
    console.log("You should study JavaScript first as it is the most important topic for web development.");
  </script>
</body>
</html>

