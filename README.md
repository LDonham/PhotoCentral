<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PhotoCentral📷</title>
    <!-- compiled and minified css -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- latest compiled JavaScript -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" rel="stylesheet">
    <!-- Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>

<body>
    <!-- navbar -->
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid bg-dark">
            <a class="navbar-brand text-info" href="#">Photo Central📷</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link active text-info" aria-current="page" href="#">Home</a>
                    <a class="nav-link text-info" href="#photos">Photos</a>
                    <a class="nav-link text-info" href="#footer">Log In</a>
                    <a class="nav-link text-info" href="#footer">Subscribe</a>
                </div>
            </div>
        </div>
    </nav>
    <div class="card text-bg-dark overflow-hidden">
        <img src="img/graffiti-wall.jpg" class="card-img" style="height: 840px;" alt="...">
        <div class="card-img-overlay">
            <h5 class="card-title display-2 fw-bold text-info">Photo Central📷</h5>
            <p class="card-text text-light fs-2">Come see how the professionals play!</p>
        </div>
    </div>
    <!-- tryout -->
    <!-- <div class="container-fluid">
        <img style="width: 100%;height: 692px;" src="img/graffiti-wall.jpg" class="img-fluid" alt="train">
        <h1></h1>
    </div> -->
    <div class="container-fluid overflow-hidden" id="photos">
        <h1 class="display-1 text-info text-center">Photos</h1>
        <div class="row gx-5">
            <div class="col-2 card mb-3 pt-3 bg-secondary" style="margin-left:45px">
                <img src="img/hand-grandmother.jpg" class="card-img-top rounded text-center" alt="...">
                <div class="card-body">
                    <h5 class="card-title ">Black & White</h5>
                    <!-- <p class="card-text">Price: $12050</p> -->
                    <button class="btn btn-sm btn-info btn-outline-dark text-light">View More</button>
                </div>
            </div>
            <div class="col-1"></div>
            <div class="col-2 card mb-3 pt-3 bg-secondary" style="margin-left: 10px;">
                <img src="img/dance-prom-girl-dress.jpg" class="card-img-top rounded text-center" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Prom & Formal</h5>
                    <!-- <p class="card-text">Price: $12050</p> -->
                    <button class="btn btn-sm btn-info btn-outline-dark text-light">View More</button>
                </div>
            </div>
            <div class="col-1"></div>
            <div class="col-2 card mb-3 pt-3 bg-secondary">
                <img src="img/bride-woman-wedding-single.jpg" class="card-img-top rounded text-center" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Wedding</h5>
                   <!-- <p class="card-text">Price: $12050</p> -->
                   <button class="btn btn-sm btn-info btn-outline-dark text-light">View More</button>
                </div>
            </div>
            <div class="col-1"></div>
            <div class="col-2 card mb-3 pt-3 bg-secondary">
                <img src="img/city-and-urban-moscow.jpg" class="card-img-top rounded text-center" alt="...">
                <div class="card-body">
                    <h5 class="card-title ">Landscape</h5>
                    <!-- <p class="card-text">Price: $12050</p> -->
                    <button class="btn btn-sm btn-info btn-outline-dark text-light">View More</button>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-9"></div>
            <div class="col-3">
                <button class="btn btn-lg btn-outline-info float-end mb-3">Want More Styles?</button>
            </div>
        </div>
    </div>
    <footer class="overflow-hidden" id="footer">
        <div class="bg-info text-center text-secondary p-5">
            <h1 class="display-5">Want to follow us for more?</h1>
            <div class="row">
                <div class="col fs-5">
                    <i class="bi bi-facebook"></i>
                    <i class="bi bi-snapchat"></i>
                    <i class="bi bi-pinterest"></i>
                    <i class="bi bi-tiktok"></i>
                    <i class="bi bi-github"></i>
                </div>

            </div>
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <h1 class="fs-4 text-light">We would love to her from you!!</h1>
                        <p>Sign in today for better experience</p>
                    </div>
                    <div class="col-6">
                        <h1 class="fs-4 text-light text-end">Subscribe for MORE!</h1>
                    </div>
                    <div class="col-9">
                        <form>
                            <div class="row">
                                <div class="col-3">
                                    <div class="form-group">
                                        <label for="email">Email:</label>
                                        <input class="form-control" type="email">
                                    </div>
                                </div>
                                <div class="col-3">
                                    <div class="form-group">
                                        <label for="password">Password:</label>
                                        <input class="form-control" type="password">
                                    </div>
                                </div>
                                <div class="col-3">
                                    <div class="d-flex justify-content-between text-center mt-3">
                                        <div class="form-check">
                                            <input class="form-check-input" type="checkbox">
                                            <label for="form-check-label">Remember Me!</label>
                                        </div>
                                        <button type="submit" class="btn btn-secondary">Log In</button>
                                    </div>
                                </div>
                            </div>
                        </form>
                    </div>
                    <div class="col-3">
                        <form>
                            <div class="form-group">
                                <label for="email">Email:</label>
                                <input class="form-control" type="email">
                            </div>
                            <button type="submit" class="btn btn-secondary">Subscribe</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</body>

</html>
