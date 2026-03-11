<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My One-Page Website</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            scroll-behavior: smooth;
        }

        header {
            background: url('images/your-header-image.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 150px 20px;
        }

        section {
            padding: 80px 20px;
        }

        footer {
            background: #222;
            color: #fff;
            text-align: center;
            padding: 40px 20px;
        }

        nav a {
            color: white;
            margin-right: 15px;
        }

        nav a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">MySite</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header -->
    <header>
        <h1>Welcome to My Website</h1>
        <p class="lead">A simple one-page site using HTML, CSS, Bootstrap, and JavaScript</p>
    </header>

    <!-- About Section -->
    <section id="about" class="container">
        <h2>About Me</h2>
        <p>This section introduces you to the website or your topic. Add some text about your project, hobbies, or interests.</p>
        <img src="images/about-image.jpg" class="img-fluid rounded" alt="About Image">
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="bg-light">
        <div class="container">
            <h2>Gallery</h2>
            <div class="row">
                <div class="col-md-4">
                    <img src="images/gallery1.jpg" class="img-fluid rounded mb-3" alt="Gallery 1">
                </div>
                <div class="col-md-4">
                    <img src="images/gallery2.jpg" class="img-fluid rounded mb-3" alt="Gallery 2">
                </div>
                <div class="col-md-4">
                    <img src="images/gallery3.jpg" class="img-fluid rounded mb-3" alt="Gallery 3">
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container">
        <h2>Contact</h2>
        <form id="contactForm">
            <div class="mb-3">
                <label for="name" class="form-label">Name:</label>
                <input type="text" class="form-control" id="name" required>
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email:</label>
                <input type="email" class="form-control" id="email" required>
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">Message:</label>
                <textarea class="form-control" id="message" rows="4" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2026 MySite | All Rights Reserved
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

    <!-- Custom JS -->
    <script>
        // Contact form alert
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message!');
        });
    </script>

</body>
</html>
