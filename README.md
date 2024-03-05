<!DOCTYPE html>
<html>
<head>
<style>
/*header*/
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}

/*footer*/
footer {
  padding: 40px 0;
  color: white;
  background: black;
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  
}

footer li {
  float: left;
  padding: 0 10px;
  list-style: none;
}

footer a {
  color: white;
}

footer p {
  float: right;
}


</style>
</head>

<body>

<ul>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>
<main-container>
<form action="starter.php", method="get">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value=""><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value=""><br><br>
  <input type="submit" value="Submit">
</form> 

<?php echo $_GET["fname"] ?> <br>
<?php echo $_GET["lname"] ?>
</main-container>


<footer>
        <div id = 'footer-id', class='container-footer'>
        <div class='row'>
            <div class='col-md-12'>
                <ul>
                    <li><a href='#'>Terms</a></li>
                    <li><a href='#'>Privacy</a></li>
                    <li><a href='#'>Contact</a></li>
                    <li><a href='#'></a></li>
                    <p>&copy; Copyright 2024</p>
                </ul>
            </div>
        </div>
        </div>
    </footer>
	
	
</body>
</html>
