##working Add for M_M Viynl project

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link type="text/css" ref="index" href="index.css">
<style>
.fa {
padding: 20px;
font-size: 30px;
width: 50px;
text-align: center;
text-decoration: none;
margin: 5px 2px;
}
.fa:hover {
opacity: 0.7;
}
.fa-facebook {
background: #3B5998;
color:white;
}
.fa-instagram {
background: #125688;
color: white;
}
.fa-pinterest {
  background: #cb2027;
  color: white;
  }
 .fa-venmo {
  background: #45bbff;
  color: white;
  }
  .fa-paypal {
  background: 
  color: white;
  }
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
M $ M Vinyl and Embroidery 
</title>
</head>
<body>
<header>
<h1>
M & M
</h1>
<h2> Custom Vinyl and Embroidery </h2>
<nav>
<div class="row">
<div class="left" style="background-color: ####;">
<h2>Menu</h2>
<input type="text" id="mySearch" onkeyup="myFunction()" placeholder="Search" title="Type in a Category">
<ul id="myMenu">
<li><a href="#">Merchandise</a></li>
  // <li>Shirts</li>
  // <li>Hats</li>
  // <li>Bags</li>
  // <li>Bottles</li>
  // <li>Wall Decals</li>
  // <li>Head Bands</li>
  // <li>Cups</li>
  // <li>Magnets</li>
  // <li>Custom Ideas</li>
  <li><a href="#">Designs</a></li>
   // <li>Coming Soon!</li>
    <li><a href="#">Templates</a></li>
       // <li>Disney Characters</li>
       // <li>NFL</li>
       // <li>NCAA</li>
       // <li>Super Heros</li>
       // <li>Villains</li>
    <li><a href="#">Testimonies</a></li>
      // 
</ul>
</div>
<div class="right" style="background-color: ####;">
<h2>Page Content</h2>
 <p> Our goal is to make your creative thoughts and needs on the product of your choice. The possibilities can go as far as your imagination can take you. </p>
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
  <ul>
    <li><a href="#">Contact Us</a></li>
      <li><a href="#">FAQ</a></li>
        <li><a href="#">2020 Site Map</a></li>
           <li><a href="#">Disclaimer</a></li>
  </ul>
  <a href="#" class="fa fa-facebook"></a>
  <a href="#" class="fa fa-instagram"></a>
  <a href="#" class="fa fa-pinterst"></a>
  <a href="#" class="fa fa-paypal"></a>
  <a href="#" class="fa fa-venmo"></a>

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
