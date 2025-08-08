<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Complete Web Page with HTML, CSS & JS</title>
  <!-- ✅ Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

  <!-- ✅ CSS Styling -->
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Body Styling */
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(to bottom, #f8f9fa, #e9ecef);
      color: #2d3436;
      line-height: 1.6;
    }

    /* Layout Container */
    .container {
      max-width: 960px;
      margin: 40px auto;
      padding: 40px;
      background-color: #ffffff;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.05);
      border-radius: 10px;
    }

    /* Headings */
    h1, h2 {
      margin-bottom: 20px;
    }

    h1 {
      text-align: center;
      font-size: 2.5rem;
      color: #2c3e50;
    }

    h2 {
      font-size: 1.8rem;
      color: #34495e;
    }

    /* Paragraphs */
    p {
      margin-bottom: 20px;
      font-size: 1.1rem;
      color: #555;
    }

    /* Image Styling */
    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 25px 0;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    }

    /* Links */
    ul {
      padding-left: 20px;
      margin-bottom: 20px;
    }

    li {
      margin-bottom: 10px;
    }

    a {
      color: #2980b9;
      font-weight: 600;
      text-decoration: none;
    }

    a:hover {
      color: #1abc9c;
      text-decoration: underline;
    }

    /* Alert Button */
    .alert-button {
      display: inline-block;
      padding: 12px 24px;
      background-color: #3498db;
      color: #fff;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
      font-weight: 600;
      cursor: pointer;
      margin-top: 20px;
      transition: background-color 0.2s ease;
    }

    .alert-button:hover {
      background-color: #2980b9;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }

      h1 {
        font-size: 2rem;
      }

      h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <!-- ✅ HTML Content -->
  <div class="container">
    <h1>Welcome to My Web Page</h1>

    <h2>About Me</h2>
    <p>Hello! I'm learning how to build and style websites using HTML and CSS. This is my fully styled and interactive web page with headings, paragraphs, images, links, and JavaScript!</p>

    <h2>My Favorite Things</h2>
    <p>I enjoy coding, reading, and exploring new technologies. Here's a scenic image I really like:</p>

    <!-- ✅ Image -->
    <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1200&q=80" alt="Beautiful Mountainscape">

    <h2>Useful Links</h2>
    <p>Here are some websites I find helpful while learning:</p>
    <ul>
      <li><a href="https://www.w3schools.com" target="_blank">W3Schools - Learn HTML</a></li>
      <li><a href="https://developer.mozilla.org" target="_blank">MDN Web Docs</a></li>
      <li><a href="https://www.freecodecamp.org" target="_blank">FreeCodeCamp</a></li>
    </ul>

    <!-- ✅ JavaScript Button -->
    <button class="alert-button" onclick="showAlert()">Click Me</button>
  </div>

  <!-- ✅ JavaScript Function -->
  <script>
    function showAlert() {
      alert("Hello! You clicked the button.");
    }
  </script>

</body>
</html>
