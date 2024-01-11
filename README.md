<!DOCTYPE html>
<html>
<head>
	<title>Portfolio</title>
	<!-- css files -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css">
	<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.3.1/css/bulma.min.css">
	<link rel="stylesheet" type="text/css" href="assets/css/styles.css">

	<link rel="icon" type="image/x-icon" href="assets/img/favicon.png">
	<meta name="author" content="Hassan Ali">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
	<body>
		<!-- Navbar -->
		<nav class="nav container void-background">
			<!-- This "nav-menu" is hidden on mobile -->
			<!-- Add the modifier "is-active" to display it on mobile -->
			<div class="nav-left">
				<a href="" class="nav-item">
					<span class="icon">
						<i class="fa fa-medium"></i>
					</span>
				</a>
				<a href="https://github.com/NAVEENKUMAR-M-RESEARCHER/" class="nav-item">
					<span class="icon">
						<i class="fa fa-github"></i>
					</span>
				</a>
				<a href="" class="nav-item">
					<span class="icon">
						<i class="fa fa-twitter"></i>
					</span>
				</a>				
			</div>

			<div class="nav-right nav-menu">
				<a class="nav-item" href="./index.html">Home</a>
				<a class="nav-item" href="#about">About</a>
				<a class="nav-item" href="#projects">Projects</a>
				<a class="nav-item" href="./htmltool/main.html" target="_blank">HTML Tool</a>
			</div>

			<!-- This "nav-toggle" hamburger menu is only visible on mobile -->
			<!-- You need JavaScript to toggle the "is-active" class on "nav-menu" -->
			<span class="nav-toggle">
				<span></span>
				<span></span>
				<span></span>
			</span>
		</nav>
				
		<!-- About Me -->
		<section id="about" class="section section-1">
			<div class="container has-text-centered">
				<!-- Source: https://flic.kr/p/pAZBNK -->
				<img class="avatar" src="assets/img/profile.jpg">
			</div>
			<div class="container"></br>
				<p class="intro">
					Dr Naveenkumar Mahamkali holds the esteemed position of Assistant Professor at SRM University,Andhra Pradesh, where his rich academic journey and expertise shine through. He earned his Doctorate from the renowned </b>National Institute of Technology, Tiruchirappalli</b>, located in the culturally vibrant state of Tamil Nadu, India. Specializing in cutting-edge areas such as Computer Vision, Image Processing, and Machine Learning/Deep Learning applications, Dr. Naveenkumar is at the forefront of research and innovation. His dedication to advancing these fields is evident in the numerous articles he has published in reputable journals and presented at esteemed conferences.
				</p>
			</div>
		</section>
		
		<!-- Projects -->
		<section  id="projects" class="section section-2">
			<div class="container">
				<div class="has-text-centered">
					<h3 class="title is-3">Projects</h3>
				</div>
				
				<div class="columns is-multiline is-desktop">
					<!-- Project 1 -->
					<div class="column">
						<div class="box project-text">
							<article>
								<div>
									<figure class="image project-figure">
										<img src="assets/img/project-1.jpg" alt="Image">
									</figure>
								</div>
								<div>			
									<p>
										They don’t want us to eat. I told you all this before, when you have a swimming pool, do not use chlorine, use salt water, the healing, salt water is the healing.
									</p>
								</div>
							</article>
						</div>
					</div>
					<!-- Project 2 -->
					<div class="column">
						<div class="box project-text">
							<article>
								<div>
									<figure class="image project-figure">
										<img src="assets/img/project-2.jpg" alt="Image">
									</figure>
								</div>
								<div>			
									<p>
										Bless up. Another one. How’s business? Boomin. Don’t ever play yourself. Life is what you make it, so let’s make it.
									</p>
								</div>
							</article>
						</div>
					</div>
				</div>
			</div>
		</section>

		<!-- Social -->
		<section id="social" class="section section-3">
			<div class="container">
				<div class="has-text-centered">					
					<h3 class="title is-3">Let's Socialize</h3>
				</div>
				<div class="social-container columns">
					<div class="column is-6 has-text-centered">
						<a target="_blank" href="https://www.linkedin.com/in/naveenkumar-m-researcher/"><img class="" src="assets/img/linkedin.png"></a>
					</div>
					<div class="column is-6 has-text-centered">
						<a target="_blank" href="https://www.facebook.com/profile.php?id=100000746840343&mibextid=ZbWKwL"><img class="" src="assets/img/facebook.png"></a>
					</div>
				</div>
			</div>
		</section>	
		
		<!-- Footer -->
		<section class="section-4 has-text-centered container">
			<a href="">Dr M NaveenKumar</a>
		</section>
		
		<!-- Scripts  -->
		<script src="controller.js"></script>		
	</body>	
</html>
