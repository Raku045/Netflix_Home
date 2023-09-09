# Netflix_Home
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #770202;
        }
        .navbar {
            background-color: #111;
            padding: 20px;
            text-align: center;
        }
        .navbar a {
            color: #d70808;
            text-decoration: none;
            margin: 0 20px;
        }
        .hero {
            background-image: url('netflix-hero.jpg');
            background-size: cover;
            background-position: center;
            height: 600px;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .featured {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 40px;
        }
        .movie {
            margin: 20px;
            text-align: center;
        }
        .movie img {
            max-width: 100%;
        }
        .footer {
            background-color: #111;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <a href="#">Home</a>
        <a href="#">TV Shows</a>
        <a href="#">Movies</a>
        <a href="#">New & Popular</a>
        <a href="#">My List</a>
    </div>
 <div class="hero">
        <h1>Welcome to Netflix</h1>
        <p>Watch unlimited movies and TV shows.</p>
    </div>
 <div class="featured">
        <div class="movie">
            <img src="movie1.jpg" alt="Movie 1">
            <h3>Movie 1</h3>
        </div>
        <div class="movie">
            <img src="movie2.jpg" alt="Movie 2">
            <h3>Movie 2</h3>
        </div>
        <div class="movie">
            <img src="movie3.jpg" alt="Movie 3">
            <h3>Movie 3</h3>
        </div>
    </div>
 <div class="footer">
        &copy; 2023 Netflix Clone
    </div>
</body>
</html>
