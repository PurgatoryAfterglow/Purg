
<html>
  <head>
    <title>Startup</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">

    <!-- Note that the below Bootstrap file is a specific version. If you grab the most
    current from Bootstrap website, you will see the button grow transition being a lot faster
    than in my video.  Use whichever style sheet you like best! -->
    <!-- Bootstrap CSS from a CDN. This way you don't have to include the bootstrap file yourself -->
<!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">    <!-- My own stylesheet -->
    <link href="style.css" rel="stylesheet">
  </head>
  <body>
   <div class="container d-flex align-items-center text-center justify-content-center h-100">
       <header class="row">
          <h1 class="text-uppercase">THE BIGGEST STARTUP EVENT OF THE YEAR</h1>
       </header>
   </div>
   <hr>
    <div class="myDiv2">
       <button type="button" class="btn btn-primary btn-xl">SIGN UP</button>
    </div>
  </body>
</html>
body,html {
  width: 100%;
  height: 100%;
  font-family: 'Montserrat', sans-serif;
  background: url(header.jpg) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: vh;
}

.text-center {
  text-align: center;
  margin: auto;
  height: 70%;
  width: 40%;
}



h1 {
  font-size: 3rem;
  color: #ffffff;
}

hr {
  border-color: #f05f44;
  border-width: 3px;
  max-width: 64px;
}

.myDiv2 {
  text-align: center;
  margin: auto;
  height: 70%;
  width: 40%;
}

.btn {
  font-weight: 700;
  border-radius: 500px;
  text-transform: uppercase;
}

.btn-xl {
  padding: 0.8rem 3rem;
}

.btn-primary {
  background-color: #f05f44;
  border-color: #f05f44;
}

.btn-primary:hover {
  background-color: #ee4b08;
  border-color: #ee4b08;
  border-width: 4px;
}
