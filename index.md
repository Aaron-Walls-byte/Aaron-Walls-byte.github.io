

<body>

<div class="topnav responsive" id="myTopnav">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars fa-2x"></i>
  </a>
  <a class="underline" href="#">Software Design</a>
  <a class="underline" href="#">Data Structures and Algorithms</a>
  <a class="underline" href="#">Database Management</a>
  <a class="box" href="#">Contact</a>
</div>

<div class="main">
  <div class="banner">
	<img src="./assets/images/greenPC.jpg" class="stretch" alt=""/>
	<div class="bannerMessage">
	Software Development
	<ul class="Sigline">
		<li>By Aaron J Walls</li>
		<li>Nov 23, 2021</li>
	</ul>
	</div>
  </div>
</div>

<script>
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>


</body>
