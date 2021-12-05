

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
	<div class="banner stripes">
		<div class="colorbar">
			<div class="bannerMessage">
			Aaron Walls
				<div class="stack" style="--stacks: 3;">
					<span style="--index: 0;">Software Engineer &</span>
					<span style="--index: 1;">Software Engineer &</span>
					<span style="--index: 2;">Software Engineer &</span>
				</div>
				<div class="stack" style="--stacks: 3;">
					<span style="--index: 0;">Cyber Security Analyst</span>
					<span style="--index: 1;">Cyber Security Analyst</span>
					<span style="--index: 2;">Cyber Security Analyst</span>
				</div>
				<span class="right">Updated on December 2, 2021</span>
			</div>
			<div class="fastBars">	
			</div>
		</div>
	</div>
</div>
<div class="Main2">
	<div class="content-left">
		<img class="cartoonify" src="./assets/images/cartoonify.png">
		<h2>About Me:</h2>
		<p class="red">
		I am currently employed as a Cyber Security Analyst for the United States Air Force. It is as cool as it sounds, but it isn't my only skill set. 
		Computer technology is a passion of mine, and soon I'll earn my software engineering degree (End of December 2021). I started coding in Java when 
		I was 13, and have been learning and using development skills ever since. I started my professional career in computer technology as <i>the</i> IT guy and
		used my coding skills to create administrative scripts in powershell, bash, and python. After 3 years of IT support, I moved into the cyber security realm. 
		Around the sametime, I enrolled into college to persue my original passion: Software Development. Working full-time and attending school online as a full-time 
		student never felt overwhelming because the content of the work were very closely related. </p>
		<p>
		This portfolio highlights some of the skills gained as a cyber security professional, and demonstrates projects I have completed as apart of my course work.
		</p>
	</div>
	<div class="content-right">
		<h2>Skills: </h2>
		<div class="skills">
			<div class="details">
				<span class="icon"><img src="./assets/icons/HTML5.svg" width="100" height="100"></span>
			</div>
			<div class="bar">
				<div id="html-bar"></div>
			</div>
			<div id="years">4 years</div>
		</div>
		<div class="skills">
			<div class="details">
				<span class="icon"><img src="./assets/icons/CSS3.svg" width="100" height="100"></span>
			</div>
			<div class="bar">
				<div id="css-bar"></div>
			</div>
			<div id="years">4 years</div>
		</div>
		<div class="skills">
			<div class="details">
				<span class="icon"><img src="./assets/icons/JS.svg" width="100" height="100"></span>
			</div>
			<div class="bar">
				<div id="js-bar"></div>
			</div>
			<div id="years">4 years</div>
		</div>
		<div class="skills">
			<div class="details">
				<span class="icon"><img src="./assets/icons/java.svg" width="100" height="100"></span>
			</div>
			<div class="bar">
				<div id="java-bar"></div>
			</div>
			<div id="years">several years</div>
		</div>
	</div>
</div>
<div class="Main3">
	<input type="checkbox" class="read-more-state" id="post-1" />
	<div class="readmore">
		<p class="red">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
		</p>
		<span class="readmore-link"></span>
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
