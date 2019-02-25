<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.navbar {
    overflow: hidden;
    background-color: rgb(128, 128, 128);
    font-family: Arial, Helvetica, sans-serif;
}
.navbar a {
    float: left;
    font-size: 16px;
    color: rgb(255, 255, 255);
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}
.dropdown {
    float: left;
    overflow: hidden;
}
.dropdown .dropbtn {
    font-size: 16px;
    border: none;
    outline: none;
    color: white;
    padding: 14px 16px;
    background-color: inherit;
    font-family: inherit;
    margin: 0;
}
.navbar a:hover, .dropdown:hover .dropbtn {
    background-color: red;
}
.dropdown-content {
    display: none;
    position: absolute;
    background-color: lightgray;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}
.dropdown-content a {
    float: none;
    color : gray;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}
.dropdown-content a:hover {
    background-color: #ddd;
}
.dropdown:hover .dropdown-content {
    display: block;
}
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}
.avatar {
    vertical-align: middle;
    width: 350px;
    height: 300px;
    border-radius: 50%;
}
.hero-image {
  background-image: url("a.jpg");
  background-color: #cccccc;
  height: 850px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}
.hero-text {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}
.button {
    background-color: "#663300";
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: rgba(143, 140, 140, 0.301);
  color: rgb(5, 5, 5);
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}
#myBtn:hover {
  background-color: #555;
}
</style>
</head>
<body>
    <script>
        window.onscroll = function() {scrollFunction()};
function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    document.getElementById("navbar").style.top = "0";
  } else {
    document.getElementById("navbar").style.top = "-50px";
  }
}
        // When the user scrolls down 20px from the top of the document, show the button
        window.onscroll = function() {scrollFunction()};
        function scrollFunction() {
            if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                document.getElementById("myBtn").style.display = "block";
            } else {
                document.getElementById("myBtn").style.display = "none";
            }
        }
        // When the user clicks on the button, scroll to the top of the document
        function topFunction() {
            document.body.scrollTop = 0;
            document.documentElement.scrollTop = 0;
        }
        </script>



<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>



</style>
</head>
<body >

    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#news">My Projects</a>
        <div class="dropdown">
          <button class="dropbtn">Dropdown
            <i class="fa fa-caret-down"></i>
          </button>
          <div class="dropdown-content">
            <a href="#">Part 1</a>
            <a href="#">Part 2</a>
            <a href="#">Part 3</a>
          </div>
        </div>
      </div>
<div class="hero-image">
  <div class="hero-text">
    <h1 style="font-size:50px">Hi, I am Mangu Adrian-Constantin</h1>
    <h3>And I'm a Programmer</h3>
    <a href="#" class="button">Home</a>
    <a herf="#" class="button">Look at my projects</a>
  </div>
</div>
<p align = "center"><img src="b.jpg" alt="Avatar" class="avatar"></p>
<h1 style = "font-size:15px";>Hi my name is Adrian and Welcome to my Website!</h1>
<h1 style = "font-size:15px">I have worked on many independent projects alongside my formal education.</h1>
<h1 style = "font-size:15px">I have advance knowledge with python, java and c++ , i have finished code academy java/python course and almost c++ at wellcode</h1>
<h1 style = "font-size:15px">As well as building this website using responsive web technologies from scratch.</h1>
<h1 style = "font-size:15px">My hobby is to play basketball, I also love LeBron James</h1>

<div class="w3-container">
  <h2>Software</h2>

  <div class="w3-panel w3-red">
    <p align = "left"><b>Java</b></p>
    <p>Over 2 months of experience</p>
    <p align = "right"><b>C++</b></p>
    <p align = "right">Over one year of experience</p>
    <p align = "center"><b>C#</b></p>
    <p align = "center">Over one year of experience with c# in Unity Game Engine</p>
    <p align = "center"><b>Python</b></p>
    <p align = "center"><b>Over 1,5 year of experience</b></p>


  </div>

</div>
<p align = "center"><img src="c.jpg" width ="700" height="400" ></p>

<p align = "center"><h1><b>Programing languages used for this Web Page</b></h1></p>
<p align = "right"><h1>-back-end : Python</h1></p>
<p align = "right"><h1>-front-end : html and css</h1></p>
<p align = "middle"><h1><b>The main porpose of this website</b></h1></p>
<h1 style ="font-size:25px";>This is just for fun</h1>
<p align = "center"><img src= "e.jpg" width="1200" height="750" ></p>
<h1 style = "font-size:10";>New content every week</h1>
<p align = "center"><img src="d.jpg" width="1000" height="500" ></p>
<h1 align = "center"><b>#JUST_LIKE THIS</b></h1>
<p align = "center" ><img src = "f.jpg" width="1000" height="500" > </p>
<p align = "center" ><img src = "g.jpg" width = "600" height = "350" ></p>
<h1 align = "center"><b>PYTHON PROJECTS</b></h1>
<h1>1)PYA game</h1>
<h1>2)Tic-Tac-Toe</h1>
<h1>3)CHAT BOT</h1>
<h1>4)Auto web browser pages</h1>
<p align = "center"><img src = "h.jpg" width="200" height="300"></p>
<h1 align = "center"><b>C++ PROJECTS</b></h1>
<h1>1)Data bases</h1>
<h1>2)2048 GAME</h1>
<p align = "center"><img src = "j.jpg" width="200" height="500"></p>
<h1 align = "center"><b>JAVA.....NO PROJECTS AT THIS MOMENT</b></h1>
<p align = "center"><img src = "k.png" width="400" height="400" ></p>
<h1 align = "center"><b>C# in Unity Engine</b></h1>
<h1>1)Cube Game</h1>
<h1>2)Labirint</h1>
<h1>3)Get the banana</h1>
<h1>4)The SnowMan</h1>






</body>
</html>
