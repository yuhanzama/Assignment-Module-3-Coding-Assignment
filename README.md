<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Bootstrap Layout</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-md bg-light navbar-light">
        <a class="navbar-brand" href="#">Food, LLC</a>
        <!-- Mobile Menu Button -->
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#menu">
            <span class="navbar-toggler-icon"></span>
        </button>
        <!-- Mobile Dropdown Menu -->
        <div class="collapse navbar-collapse" id="menu">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#">Chicken</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Beef</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Sushi</a></li>
            </ul>
        </div>
    </nav>
    
    <!-- Page Heading -->
    <div class="container text-center mt-5">
        <h1 class="mb-4">Our Menu</h1>
    </div>
    
    <!-- Content Section -->
    <section class="container-fluid bg-light py-5">
        <div class="container">
            <div class="row">
                <div class="col-xs-12">
                    <!-- Your content goes here -->
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec convallis arcu at libero vehicula, ac tincidunt lorem tincidunt.</p>
                    <!-- Repeat the content to make the section tall enough for scrolling -->
                    <!-- ... -->
                </div>
            </div>
        </div>
    </section>
    
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
