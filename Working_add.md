##working Add for M_M Viynl project

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link type="text/css" ref="index" href="index.css">
<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital@1&display=swap');
* {
box-sizing: border-box;
}
//Create a column layout with flex box//
.row {
display:flex;
}

// left column (menu) //
.left {
flex: 35%;
padding: 15px 0;
}
.left h2 {
padding-left: 8px;
}

// right column (page Content) //
.right {
flex: 65%;
padding: 15px;
}

// Search Box Styling //
#mySearch {
width: 100%;
font-size: 18px;
padding: 11px;
border:1px solid black;
}

// style the nav menu //
#myMenu {
list-style-type: none;
padding: 0;
margin: 0;
}
#myMenu li a {
padding: 12px;
text-decoration: none;
color: black;
display: block;
}

#myMenu li a:hover {
color:black;
background-color:pink;
}
</style>
<title>
M $ M Vinyl and Embrodery 
</title>
</head>
<body>
<header>
<h1>
M & M
</h1>
<p> Vinyl and Embrodery </p>
<nav>
<div class="row">
<div class="left" style="background-color: ####;">
<h2>Menu</h2>
<input type="text" id="mySearch" onkeyup="myFunction()" placeholder="Search" title="Type in a Category">
<ul id="myMenu">
<li><a href="#">Menu</a></li>
<li><a href="#">Menu</a></li>
<li><a href="#">Menu</a></li>
<li><a href="#">Menu</a></li>
</ul>
</div>
<div class="right" style="background-color: ####;">
<h2>Page Content</h2>
<p> blah blah blah </p>
<p> blah blah blah </p>
<p> blah blah blah </p>
</div>
</div>
</nav>
</header>
<main>
<section>
<h2> "Search Menu" </h2>
<p1></p1>
<img id="" src="">
<p2></p2>
</section>
</main>
<footer>
2020 Site Map
</footer>
<script>
function myFunction() {
var input, filter, ul, li, a, i;
input = document.getElementById("mySearch");
filter = input.value.toUpperCase();
ul = document.getElementById("myMenu");
li = ul.getElementsByTagName("li");
for (i = 0; i < li.length; i++) {
a = li[i].getElementsByTagName("a')[0];
if (a.innerHTML.toUpperCase().indexOf(filter) > -1) {
li[i].style.display = "";
} else {
li[i].style.display = "none";
}
}
}
</script>
</body>
</html>
