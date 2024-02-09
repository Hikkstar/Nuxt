<template>
  <div>
    <!-- Custom Styles -->
    <!-- <style>
        body {
            padding-top: 56px; /* Add height of navbar */
        }

        .hero-section {
            background: url('https://via.placeholder.com/1600x600') center/cover no-repeat;
            color: #fff;
            text-align: center;
            padding: 100px 20px;
        }

        .service-section {
            padding: 80px 20px;
        }
    </style> -->

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
        <a class="navbar-brand" href="#">Your Logo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Services</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="hero-section">
    <div class="container">
        <h1 class="display-4">Welcome to Our Responsive Website</h1>
        <p class="lead">Discover amazing things with Bootstrap 5</p>
        <a class="btn btn-primary btn-lg" href="#" role="button">Learn More</a>
    </div>
</section>

<!-- Service Section -->
<section class="service-section">
    <div class="container">
        <h2>Our Services</h2>
        <div class="row">
            <div class="col-lg-4 mb-4">
                <div class="card">
                    <img src="@/assets/img/cp01.jpg" class="card-img-top" alt="Service 1">
                    <div class="card-body">
                        <h5 class="card-title">Service 1</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 mb-4">
                <div class="card">
                    <img src="@/assets/img/cp02.jpg" class="card-img-top" alt="Service 2">
                    <div class="card-body">
                        <h5 class="card-title">Service 2</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 mb-4">
                <div class="card">
                    <img src="@/assets/img/cp03.jpg" class="card-img-top" alt="Service 3">
                    <div class="card-body">
                        <h5 class="card-title">Service 3</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Form -->
<section class="contact-section">
    <div class="container">
        <h2>Contact Us</h2>
        <form>
            <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name" placeholder="Your Name">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" placeholder="Your Email">
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">Message</label>
                <textarea class="form-control" id="message" rows="4" placeholder="Your Message"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>
</section>
</div>
</template>
