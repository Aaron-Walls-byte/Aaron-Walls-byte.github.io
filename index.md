

<body>

<div class="topnav" id="myTopnav">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <a class="underline" href="#">Software Design</a>
  <a class="underline" href="#">Data Structures and Algorithms</a>
  <a class="underline" href="#">Database Management</a>
  <a class="box" href="#">Contact</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars fa-2x"></i>
  </a>
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
  <div class="Main2">
  <div class="content-left">
      <p class="red">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
  </div>
  <div class="content-right">
      <p class="blue">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
     </p>
  </div>
</div>
<div class="Main3">
	<input type="checkbox" class="read-more-state" id="post-1" />
	  <div class="readmore">
		  <p class="blue">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
		 </p>
		 <span class="readmore-link"></span>
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
