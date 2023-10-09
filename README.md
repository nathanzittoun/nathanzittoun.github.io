<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <style>
    /* Add appropriate styles for highlighting */
    .highlight {
      background-color: yellow;
    }
  </style>
  <script defer src="script.js"></script>
  <title>Portfolio</title>
</head>
<body>
  <header>
  <div class="toolbar">
    <div class="nav-links">
      <ul>
        <li><a href="#aboutMe">About Me</a></li>
        <li><a href="#projects">My Projects</a></li>
        <li><a href="#contactMe">Contact Me</a></li>
      </ul>
    </div>
    <div class="spacer"></div> <!-- Added spacer to push items to the left -->
      <div class="search-bar">
        <input type="text" id="searchInput" placeholder="Search">
        <button onclick="toggleSearch()" id="searchButton">Search</button>
      </div>
      <div class="logo">
        <img src="Nate.png" alt="Logo">
      </div>
    </div>
  </header>
  <main>
    <section id="aboutMe" class="section">
      <h1>About Me</h1>
      <p>In progress ;)</p>
    </section>

    <section id="projects" class="section">
      <h1>My Projects</h1>
      <div class="project-slider">
        <div class="slide"><img src="Mcgill.webp" alt="Project 1"></div>
        <div class="slide"><img src="Nathan.JPG" alt="Project 2"></div>
        <div class="slide"><img src="project3.jpg" alt="Project 3"></div>
        <!-- Add more slides as needed -->
      </div>
    </section>
    
    <section id="contactMe" class="section">
      <h1>Contact Me</h1>
      <p>This is the section for contacting me.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Nathan ZITTOUN | Portfolio</p>
  </footer>
</body>
</html>
