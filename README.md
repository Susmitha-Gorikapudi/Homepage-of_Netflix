# Homepage-of_Netflix
<!DOCTYPE html>
<html>
<head>
  <title>Netflix Homepage</title>
  <style>
    /* Reset some default styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Set background color and font */
    body {
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
    }

    /* Header */
    header {
      padding: 20px;
    }

    /* Logo */
    .logo {
      color: #e50914;
      font-size: 24px;
      font-weight: bold;
    }

    /* Navigation */
    nav {
      margin-top: 10px;
    }

    nav ul {
      list-style: none;
      display: flex;
    }

    nav ul li {
      margin-right: 15px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-size: 16px;
      font-weight: bold;
    }

    /* Main section */
    .main-section {
      padding: 50px;
      text-align: center;
    }

    .main-section h1 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    .main-section p {
      font-size: 18px;
      margin-bottom: 40px;
    }

    /* Featured movies */
    .featured-movies {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    .movie-card {
      width: 200px;
      margin: 10px;
    }

    .movie-card img {
      width: 100%;
      height: auto;
    }

    /* Footer */
    footer {
      padding: 20px;
      text-align: center;
      background-color: #141414;
    }

    footer p {
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Netflix</div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">TV Shows</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">My List</a></li>
      </ul>
    </nav>
  </header>

  <div class="main-section">
    <h1>Welcome to Netflix</h1>
    <p>Watch unlimited movies and TV shows anytime, anywhere.</p>

    <div class="featured-movies">
      <div class="movie-card">
        <img src="https://cdn.glitch.global/05567a28-8622-432c-ab9a-c025899e2fc8/rrr.jpg?v=1691074883214" alt="Movie 1">
      </div>
      <div class="movie-card">
        <img src="https://cdn.glitch.global/05567a28-8622-432c-ab9a-c025899e2fc8/bahubali.jpg?v=1691075262263" alt="Movie 2">
      </div>
      <div class="movie-card">
        <img src="https://cdn.glitch.global/05567a28-8622-432c-ab9a-c025899e2fc8/alav.jpg?v=1691074903586" alt="Movie 3">
      </div>
      <div class="movie-card">
        <img src="https://cdn.glitch.global/05567a28-8622-432c-ab9a-c025899e2fc8/var.jpg?v=1691075381534" alt="Movie 4">
      </div>
      <!-- Add more movie cards here -->
    </div>
  </div>

  <footer>
    <p>&copy; 2023 Netflix. All rights reserved.</p>
  </footer>
</body>
</html>

body{     font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
}

section {
    padding: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
}
