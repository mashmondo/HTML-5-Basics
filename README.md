<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Simple Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f0f0;
    }
    header, nav, main, footer {
      padding: 20px;
      margin: 10px;
      background-color: #ffffff;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    nav {
      background-color: #333;
    }
    nav a {
      color: #ffffff;
      text-decoration: none;
      margin-right: 15px;
    }
    nav a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
  <main>
    <section>
      <h2>About This Page</h2>
      <p>
        This webpage is a demonstration of using semantic HTML elements. It includes a header, navigation menu, main content, and a footer.
        Using proper HTML5 structure not only improves accessibility and SEO but also makes your code easier to understand and maintain.
      </p>
    </section>
    <section>
      <h2>More Information</h2>
      <p>
        The semantic elements used in this page include <code>&lt;header&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;main&gt;</code>, 
        <code>&lt;section&gt;</code>, and <code>&lt;footer&gt;</code>. These elements convey clear meaning and structure to both browsers 
        and screen readers.
      </p>
    </section>
  </main>
  <footer>
    <p>Contact us at: <a href="mailto:contact@example.com">contact@example.com</a></p>
  </footer>
</body>
</html>
