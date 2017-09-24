<html>
<head>
  <title>IzGame</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="bootstrap-3.3.7-dist\css\bootstrap.min.css">
  <link rel="stylesheet" href="bootstrap-3.3.7-dist\css\mystyle.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body onload="func()">

<div class="container-fluid">
<div class="well">
  <h1>IzGame</h1>
</div>

<nav class="navbar navbar-inverse">
  <ul class="nav navbar-nav">
    <li class="active"><a class="list-group-item" href="index.html">Main</a></li>
    <li><a class="list-group-item" href="projects.html">Projects</a></li>
    <li><a class="list-group-item" href="developers.html">Developers</a></li>
    <li><a class="list-group-item" href="partnership.html">Partnership</a></li>
    <li><a class="list-group-item" href="contact.html">Contact</a></li>
    <li><a class="list-group-item" id="afterclick" href="#" onclick="myfunction()">Switch Colors</a></li>
  </ul>
</nav>

<div class="jumbotron">
  <p>
  Our company is based on mobile games. We are developing in Android since 2015. We are looking for oportunities to get a place in IOS Appstore and virtual-augmented reality sector.
  </p>
  <br>
  <h2>
    VISION
  </h2>
   <p>
  Be one of the best companies in the sector by something.
  </p>
    <h2>
    MISSION
  </h2>
   <p>
  We develop games that improve people's skill such as reflex, caution, memory and patience.
  </p>
</div>

</div>

<script>
function myfunction() {
document.body.classList.toggle('nightmode');
localStorage.setItem("mode", document.body.className);
}
function func() {
var x = localStorage.getItem("mode");
if (x == 'nightmode') {
document.body.className = 'nightmode';
}
}
</script>

</body>
</html>