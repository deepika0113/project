# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
home
```


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PROJECT</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #1e57ca; /* Light Gray for background */
        }

        .navbar {
            background-color: #d812b1; /* Navy Blue for navbar */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .navbar .navbar-brand,
        .navbar .nav-link {
            color: #6ce643 !important; /* White for navbar text */
        }

        .navbar .btn-primary {
            background-color: #d2631e; /* Teal button */
            border-color: #f01c9f;
        }

        .hero {
            background-color: #a8dadc; /* Soft Teal for hero section */
            padding: 50px 0;
            text-align: center;
            color: #0cb3dd; /* Dark Navy text */
        }

        .hero h1 {
            font-size: 2.5rem;
            font-weight: 700;
            color: #1d3557; /* Dark Navy for headline */
        }

        .hero p {
            font-size: 1.2rem;
            color: #343a40; /* Dark Gray for subtitle */
        }

        .hero .btn-primary {
            background-color: #e63939; /* Vibrant Red for button */
            border-color: #46e117;
        }

        .content-section {
            margin: 50px 0;
        }

        .content-card {
            border: none;
            box-shadow: 0 2px 4px rgba(115, 159, 19, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .content-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .content-card img {
            height: 200px;
            object-fit: cover;
        }

        .content-card h5 {
            color: #c034a4; /* Navy Blue for card title */
        }

        .content-card p {
            color: #6b4264; /* Medium Gray for card text */
        }

        footer {
            background-color: #1d3557; /* Navy Blue for footer */
            padding: 20px 0;
            text-align: center;
            color: #a1ca39; /* White for footer text */
        }
    </style>
</head>

<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg">
        <div class="container">
            <a class="navbar-brand" href="#">BRIBBBLE </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="explore.html">Explore</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="showcase.html">Showcase</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="hire.html">Hire</a>
                    </li>
                    <li class="nav-item">
                        <a class="btn btn-primary" href="signup.html">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero">
        <div class="container">
            <h1>Discover the World’s Top Designers & Creatives</h1>
            <p>Jure is the leading destination to find & showcase creative work and home to the world's best design professionals.</p>
            <a href="joinus.html" class="btn btn-primary btn-lg">Join Us</a>
        </div>
    </div>

    <!-- Content Sections -->
    <div class="container content-section">
        <div class="row">
            <!-- Explore Card -->
            <div class="col-md-4">
                <a href="explore.html" style="text-decoration: none;">
                    <div class="card content-card">
                        <img src="c:\Users\admin\Downloads\explore.jpg " class="card-img-top" alt="Explore">
                        <div class="card-body">
                            <h5 class="card-title">Explore</h5>
                            <p class="card-text">Browse an amazing collection of creative designs and portfolios.</p>
                        </div>
                    </div>
                </a>
            </div>
            
            <!-- Showcase Card -->
            <div class="col-md-4">
                <a href="project3.html" style="text-decoration: none;">
                    <div class="card content-card">
                        <img src="c:\Users\admin\Downloads\showcase.jpg"class="card-img-top" alt="Showcase">

                        <div class="card-body">
                            <h5 class="card-title">Showcase</h5>
                            <p class="card-text">Share your work and get discovered by top companies.</p>
                        </div>
                    </div>
                </a>
            </div>
            
            <!-- Hire Card -->
            <div class="col-md-4">
                <a href="hire.html" style="text-decoration: none;">
                    <div class="card content-card">
                        <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-25 161852.png" class="card-img-top" alt="Hire">
                        <div class="card-body">
                            <h5 class="card-title">digital design </h5>
                            <p class="card-text">Find the best talent for your projects, anywhere in the world.</p>
                        </div>
                    </div>
                </a>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>AISHWARIYA S</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>




```
explore
```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore - Dribbble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f4f5f7; /* Light Gray for background */
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        .navbar {
            background-color: #1d3557; /* Navy Blue for navbar */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .navbar .navbar-brand,
        .navbar .nav-link {
            color: #f1faee !important; /* White for navbar text */
        }

        .navbar .btn-primary {
            background-color: #457b9d; /* Teal button */
            border-color: #457b9d;
        }

        .content-section {
            margin: 50px auto;
            text-align: center;
        }

        .content-card {
            border: none;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .content-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .content-card img {
            height: 300px;
            object-fit: cover;
            border-radius: 8px;
        }

        .card-title {
            font-weight: bold;
            color: #1d3557; /* Navy Blue for card title */
        }

        .card-text {
            color: #495057; /* Medium Gray for card text */
        }

        footer {
            background-color: #1d3557; /* Navy Blue for footer */
            color: #f1faee; /* White for footer text */
            text-align: center;
            padding: 20px;
            margin-top: auto;
        }
    </style>
</head>

<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg">
        <div class="container">
            <a class="navbar-brand" href="#">BRIBBBLE </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Explore</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Hire</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sign In</a>
                    </li>
                    <li class="nav-item">
                        <a class="btn btn-primary" href="#">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Explore Section -->
    <div class="container content-section">
        <h2 class="text-center mb-5">Explore Creative Designs</h2>
        <div class="row">
            <!-- Explore Card 1 -->
            <div class="col-md-4 mb-4">
                <div class="card content-card">
                    <img src="c:\Users\admin\Downloads\ex.jpg" class="card-img-top" alt="Explore Design">
                    <div class="card-body">
                        <h5 class="card-title">Explore Design</h5>
                        <p class="card-text">Browse an amazing collection of creative designs and portfolios from talented artists.</p>
                    </div>
                </div>
            </div>

            <!-- Explore Card 2 -->
            <div class="col-md-4 mb-4">
                <div class="card content-card">
                    <img src="c:\Users\admin\Downloads\art.jpg"            class="card-img-top" alt="Explore art">
                    
                    <div class="card-body">
                        <h5 class="card-title">Explore Art</h5>
                        <p class="card-text">Discover unique artistic works and portfolios from creators around the world.</p>
                    </div>
                </div>
            </div>

            <!-- Explore Card 3 -->
            <div class="col-md-4 mb-4">
                <div class="card content-card">
                    <img src="c:\Users\admin\Downloads\create.jpeg" class="card-img-top" alt="Explore Creative">
                    <div class="card-body">
                        <h5 class="card-title">Explore Creativity</h5>
                        <p class="card-text">Dive into an inspiring collection of creative works, projects, and innovative ideas.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>AISHWARIYA S </p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>


```
creativity
```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Showcase - BRIBBBLE</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #a0c228; /* Light Gray for background */
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        .navbar {
            background-color: #1d3557; /* Navy Blue for navbar */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .navbar .navbar-brand,
        .navbar .nav-link {
            color: #f1faee !important; /* White for navbar text */
        }

        .navbar .btn-primary {
            background-color: #457b9d; /* Teal button */
            border-color: #457b9d;
        }

        .hero {
            background-color: #a8dadc; /* Soft Teal for hero section */
            padding: 50px 0;
            text-align: center;
            color: #1d3557; /* Dark Navy text */
        }

        .hero h1 {
            font-size: 2.5rem;
            font-weight: bold;
        }

        .hero p {
            font-size: 1.2rem;
        }

        .hero .btn-primary {
            background-color: #e63946; /* Vibrant Red for button */
            border-color: #12115b;
        }

        .content-section {
            margin: 50px auto;
        }

        .content-card {
            border: none;
            box-shadow: 0 2px 4px rgba(121, 183, 216, 0.873);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .content-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(204, 11, 11, 0.804);
        }

        .content-card img {
            height: 200px;
            object-fit: cover;
        }

        .content-card h5 {
            color: #1f5835; /* Navy Blue for card title */
        }

        .content-card p {
            color: #409266; /* Medium Gray for card text */
        }

        footer {
            background-color: #e92939; /* Navy Blue for footer */
            color: #4ebcde; /* White for footer text */
            text-align: center;
            padding: 20px;
            margin-top: auto;
        }
    </style>
</head>

<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg">
        <div class="container">
            <a class="navbar-brand" href="index.html" >   BRIBBBLE</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="explore.html">Explore</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="showcase.html">Showcase</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sign In</a>
                    </li>
                    <li class="nav-item">
                        <a class="btn btn-primary" href="signup.html">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero">
        <div class="container">
            <h1>Showcase Your Creative Work</h1>
            <p>Share your portfolio and get discovered by leading companies and creative teams worldwide.</p>
            <a href="joinus.html" class="btn btn-primary btn-lg">Get Started</a>
        </div>
    </div>

    <!-- Showcase Section -->
    <div class="container content-section">
        <div class="row">
            <div class="col-md-6 mb-4">
                <div class="card content-card">
                    <img src="c:\Users\admin\Downloads\inspire.jpg" class="card-img-top" alt="Portfolio Showcase">
                    <div class="card-body">
                        <h5 class="card-title">Inspire Others</h5>
                        <p class="card-text">Upload your creative projects and inspire a global community of designers and artists.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-6 mb-4">
                <div class="card content-card">
                    <img src=   "c:\Users\admin\Downloads\discovered.jpg"                                                class="card-img-top" alt="get discovered">
                    <div class="card-body">
                        <h5 class="card-title">Get Discovered</h5>
                        <p class="card-text">Let your talent shine and get noticed by top recruiters and clients in the industry.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>AISHWARIYA S</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>


```

# OUTPUT:


![Screenshot 2024-12-25 163729](https://github.com/user-attachments/assets/d4558271-4ee4-477d-a700-d2008e62ff2f)




![Screenshot 2024-12-25 164720](https://github.com/user-attachments/assets/02f24083-d930-4447-8c5c-7a4d4c31ea36)


![Screenshot 2024-12-25 163750](https://github.com/user-attachments/assets/db734691-5619-451a-8423-9674d384c375)


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
