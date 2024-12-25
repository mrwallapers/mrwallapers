<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wallpaper Gallery</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Wallpaper Gallery</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#categories">Categories</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="hero">
            <div class="container">
                <h2>Explore Stunning Wallpapers</h2>
                <form id="search-form">
                    <input type="text" placeholder="Search wallpapers...">
                    <button type="submit"><i class="fas fa-search"></i></button>
                </form>
            </div>
        </section>

        <section id="categories" class="container">
            <h2>Categories</h2>
            <div class="grid">
                <div class="card">
                    <img src="images/nature.jpg" alt="Nature">
                    <h3>Nature</h3>
                </div>
                <div class="card">
                    <img src="images/abstract.jpg" alt="Abstract">
                    <h3>Abstract</h3>
                </div>
                <div class="card">
                    <img src="images/technology.jpg" alt="Technology">
                    <h3>Technology</h3>
                </div>
                <div class="card">
                    <img src="images/animals.jpg" alt="Animals">
                    <h3>Animals</h3>
                </div>
            </div>
        </section>

        <section id="gallery" class="container">
            <h2>Featured Wallpapers</h2>
            <div class="grid">
                <div class="card">
                    <img src="images/wallpaper1.jpg" alt="Wallpaper 1">
                </div>
                <div class="card">
                    <img src="images/wallpaper2.jpg" alt="Wallpaper 2">
                </div>
                <div class="card">
                    <img src="images/wallpaper3.jpg" alt="Wallpaper 3">
                </div>
                <div class="card">
                    <img src="images/wallpaper4.jpg" alt="Wallpaper 4">
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Wallpaper Gallery. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>

