# Project Responsive Web Design using Bootstrap
## Date:28-05-2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile Products</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <!-- Header -->
    <header class="bg-primary text-white text-center py-4 mb-3">
        <h1>Mobile Products</h1>
    </header>

    <!-- Navigation Pane -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark mb-4">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Mobiles</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Offers</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Main Content -->
    <div class="container mb-5">
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <!-- Example Product Card -->
            <div class="col">
                <div class="card h-100">
                    <img src="nothing.jpg" class="card-img-top" alt="Mobile 1">
                    <div class="card-body">
                        <h5 class="card-title">Nothing Phone 2</h5>
                        <p class="card-text">It stands out with its distinctive design, capable performance, and clean
                            software experience.A great mobile with awesome features.</p>
                    </div>
                </div>
            </div>
            <!-- Repeat for more products -->
            <div class="col">
                <div class="card h-100">
                    <img src="s25.jpg" class="card-img-top" alt="Mobile 2">
                    <div class="card-body">
                        <h5 class="card-title">Galaxy S25 Ultra</h5>
                        <p class="card-text">The Galaxy S25 Ultra emphasizes its advanced camera system, powerful
                            performance, and integration of AI features.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">
                    <img src="iphone.jpg" class="card-img-top" alt="Mobile 3">
                    <div class="card-body">
                        <h5 class="card-title">iPhone 16 </h5>
                        <p class="card-text"> The iPhone 16 introduces features like the Action button (previously
                            Pro-exclusive) and a new Camera Control button. Its vertically aligned cameras enable
                            spatial video capture for Apple Vision Pro.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-secondary text-white text-center py-3 mt-4">
        <div>
            <strong>&copy; 2025 Kannadhasan</strong> &mdash; All rights reserved.
        </div>
        <div>
            <small>Follow us:
                <a href="#" class="text-white ms-2 me-1"><i class="bi bi-facebook"></i> Facebook</a> |
                <a href="#" class="text-white ms-1 me-1"><i class="bi bi-twitter"></i> Twitter</a> |
                <a href="#" class="text-white ms-1"><i class="bi bi-instagram"></i> Instagram</a>
            </small>
        </div>
    </footer>
    <!-- Optionally add Bootstrap Icons CDN for social icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css">

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
```


## OUTPUT:

![alt text](<Screenshot 2025-05-19 102805.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
