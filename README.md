<!doctype html>
<html lang="en">
  <head>
    <title>Title</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="C:\Users\KARTHIK\C\octanet\style.css"

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  </head>
  <body>
      <div class="bg-container">
        <div class="nav d-flex flex-row justify-content-between">
            <h1 class="main-heading">Planetary</h1>
            <a href="" class="home anchor">Home</a>
            <a href="" class="contact anchor">Contact Us</a>
            <a href="" class="about anchor">about</a>
        </div>
        <h1 class="welcome">welcome!</h1>
        <div class="content">
            <form>
                <input  class="email block" type="email" name="email" placeholder="enter your email"/><br>
                <input  class="email block" type="password" name="password" placeholder="enter your password"/><br>
                <button class="btn btn-primary button block">Submit</button>
            </form>    
        </div>
      </div>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  </body>
</html>


css:
*{
    font-family:Roboto;
}
.bg-container{
    background-image:url("https://img.freepik.com/premium-photo/colorful-various-autumn-fallen-leaves-dark-black-background_1032986-82922.jpg?w=740");
    background-size:cover;
    height:100vh;
}
.anchor{
    text-decoration:none;
    color:orange
}
.nav{
    background-color:black;
    color:white;
}
.welcome{
    font-family:Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    color:orange;
    padding:12px;
}
.filling{
    display:block;
}
.block{
    display:block;
}
.content{
    margin:80px;
}
.email{
    height:40px;
    width:250px;
    border-radius:12px;
}
.main-heading{
    color:green;
}
