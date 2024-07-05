## Program

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        a, i {
            padding-left: 10px;
            padding-top: 10px;
        }
        a:hover {
            text-decoration: none;
            color: skyblue;
        }
        .icon-container a, .icon-container i {
            margin-right: 10px; /* Adjust margin to create spacing between icons */
        }
        .col-3 img {
            transition: transform 0.3s ease;
        }
        .col-3 img:hover {
            transform: scale(1.1); /* Increase size by 10% on hover */
        }
        .heart-clicked {
            color: red; /* Color for clicked heart */
        }
    </style>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <div class="card my-2">
        <div class="card-header bg-dark text-white" style="display: flex;">
            <div class="col-1"><img src="dribbble.png" alt="" width="70px"></div>
            <div class="col-9 icon-container">
                <a href="">Shots</a>
                <a href="">Designer</a>
                <a href="">Teams</a>
                <a href="">Community</a>
                <a href="">Jobs</a>
                <i class="bi bi-three-dots"></i>
            </div>
            <div class="col-2 my-2">
                <a href="">Sign Up</a>
                <a href="">Sign In</a>
                <input style="width: 100px;" type="text" placeholder="Search">
            </div>
        </div>
        <div class="sk my-3" style="padding-top: 10px;">
            <div class="text-center my-2 text-white" style="background-color: black;">What are you working on ? Dribbble is show and tell for designers  
                <button class="btn btn-primary">Learn more</button>
                <button class="btn btn-danger">Sign up</button>
            </div>
        </div>
        <div class="sk1 my-3 text-center">
            <a href="">popular</a>
            <a href="">Shots</a>
            <a href="">Now</a>
        </div>
        <div class="my-3" style="display: flex;">
            <div class="col-3 mx-2">
                <img src="movies.jpg" alt="" width="300px"><br>
                <center>
                    <i class="bi bi-link-45deg"></i>Movies 
                    <i class="bi bi-eye"></i> 
                    <i class="bi bi-suit-heart-fill" onclick="toggleHeartColor(this)"></i> 
                    <i class="bi bi-chat-dots-fill"></i>
                </center>
            </div>
            <div class="col-3 mx-2">
                <img src="cars.jpg" alt="" width="300px"><br>
                <center>
                    <i class="bi bi-link-45deg"></i>Cars 
                    <i class="bi bi-eye"></i> 
                    <i class="bi bi-suit-heart-fill" onclick="toggleHeartColor(this)"></i> 
                    <i class="bi bi-chat-dots-fill"></i>
                </center>
            </div>
            <div class="col-3 mx-2">
                <img src="temples.jpg" alt="" width="300px"><br>
                <center>
                    <i class="bi bi-link-45deg"></i>Temples 
                    <i class="bi bi-eye"></i> 
                    <i class="bi bi-suit-heart-fill" onclick="toggleHeartColor(this)"></i> 
                    <i class="bi bi-chat-dots-fill"></i>
                </center>
            </div>
            <div class="col-3 mx-2">
                <img src="travel.jpg" alt="" width="300px"><br>
                <center>
                    <i class="bi bi-link-45deg"></i>Travels 
                    <i class="bi bi-eye"></i> 
                    <i class="bi bi-suit-heart-fill" onclick="toggleHeartColor(this)"></i> 
                    <i class="bi bi-chat-dots-fill"></i>
                </center>
            </div>
        </div>

        <div class="my-3" style="display: flex;">
            <div class="col-3 mx-2">
                <img src="mobile.jpg" alt="" width="300px"><br>
                <center>
                    <i class="bi bi-link-45deg"></i>Products 
                    <i class="bi bi-eye"></i> 
                    <i class="bi bi-suit-heart-fill" onclick="toggleHeartColor(this)"></i> 
                    <i class="bi bi-chat-dots-fill"></i>
                </center>
            </div>
            <div class="col-3 mx-2">
                <img src="promo.jpg" alt="" width="300px"><br>
                <center>
                    <i class="bi bi-link-45deg"></i>Promotions 
                    <i class="bi bi-eye"></i> 
                    <i class="bi bi-suit-heart-fill" onclick="toggleHeartColor(this)"></i> 
                    <i class="bi bi-chat-dots-fill"></i>
                </center>
            </div>
            <div class="col-3 mx-2">
                <img src="games.jpg" alt="" width="300px"><br>
                <center>
                    <i class="bi bi-link-45deg"></i>Games 
                    <i class="bi bi-eye"></i> 
                    <i class="bi bi-suit-heart-fill" onclick="toggleHeartColor(this)"></i> 
                    <i class="bi bi-chat-dots-fill"></i>
                </center>
            </div>
            <div class="col-3 mx-2">
                <img src="sports.jpg" alt="" width="300px"><br>
                <center>
                    <i class="bi bi-link-45deg"></i>Sports 
                    <i class="bi bi-eye"></i> 
                    <i class="bi bi-suit-heart-fill" onclick="toggleHeartColor(this)"></i> 
                    <i class="bi bi-chat-dots-fill"></i>
                </center>
            </div>
        </div>
    </div>

    <script>
        function toggleHeartColor(heart) {
            heart.classList.toggle('heart-clicked');
        }
    </script>
</body>
</html>
