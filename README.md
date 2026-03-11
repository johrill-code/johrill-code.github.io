<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Puerto Princesa Subterranean River</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            scroll-behavior: smooth;
        }

        /* Hero/Header Section */
        header {
            background: url('images/river-hero.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 200px 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        header h1 {
            font-size: 3rem;
            font-weight: bold;
        }

        header p {
            font-size: 1.5rem;
            font-style: italic;
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

        /* Section headings */
        h2 {
            margin-bottom: 30px;
        }

        /* Description styling */
        .description {
            max-width: 800px;
            margin: 20px auto;
            font-size: 1.2rem;
            line-height: 1.8;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">Puerto Princesa River</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header -->
    <header id="home">
        <h1>Puerto Princesa Subterranean River</h1>
        <p>The New 7 Wonders of Nature</p>
    </header>

    <!-- Description Section -->
    <section class="bg-light">
        <div class="container description text-center">
            <p>
                Nestled in the heart of Palawan, Philippines, the <strong>Puerto Princesa Subterranean River</strong> is a UNESCO World Heritage Site and one of the <strong>New 7 Wonders of Nature</strong>. 
                Visitors can explore its majestic limestone karst landscapes and navigate a spectacular underground river that stretches over 8 kilometers. 
                This natural wonder is home to diverse wildlife, unique cave formations, and pristine tropical surroundings, making it a must-visit destination for nature lovers, adventurers, and eco-tourists.
            </p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container">
        <h2>About the River</h2>
        <p>
            The Puerto Princesa Subterranean River flows directly into the South China Sea and is renowned for its remarkable stalactites, stalagmites, and underground cave system. 
            Tours allow visitors to appreciate its natural beauty while learning about the ecological importance of this protected park.
        </p>
        <img src="images/river-about.jpg" class="img-fluid rounded" alt="River Image">
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

    <!-- Projects Section -->
    <section id="projects" class="container">
        <h2>Projects</h2>
        <p>
            This section can showcase interactive projects, research about the river, conservation efforts, or photo essays. 
            You can also include tables, charts, or embedded multimedia to make it more engaging for viewers.
        </p>
        <!-- Example table -->
        <table class="table table-bordered">
            <thead>
                <tr>
                    <th>Feature</th>
                    <th>Description</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Length</td>
                    <td>8.2 km of underground river</td>
                </tr>
                <tr>
                    <td>UNESCO Status</td>
                    <td>World Heritage Site</td>
                </tr>
                <tr>
                    <td>Wildlife</td>
                    <td>Diverse flora and fauna including bats, monkeys, and birds</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-light container">
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
        &copy; 2026 Johrill | All Rights Reserved
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

    <!-- Custom JS -->
    <script>
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message!');
        });
    </script>

</body>
</html>
