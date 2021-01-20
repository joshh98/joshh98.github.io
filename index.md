
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>Hello World!</title>
	</head>
	<body>
		<h1>Hello World!</h1>
	</body>
</html>

<html lang="en">
	<head> 
		<meta charset="utf-8">
		<!--Formatting will be handled in this line!!!!-->
		<title>Joshh98's CV</title>
	</head>
	<body>
		<div id="page-banner" class="banner">
			<header>
				<h1 id="title">Joshua T Heldreth's Curriculum Vitae</h1>
				<nav>
					<a href="#contact-info">Contact Information</a>
					<a href="#education">Education</a>
					<a href="#skills">Skills/Qualifications</a>
					<a href="#employment">Employment</a>
				</nav>
				<!--Creates Navigation tabs to different parts of the resume-->
			</header>
		</div>
		<!--End of the banner of webpage-->

		<div id="main-resume">
			<section id="contact-info" class="resume-section">
				<h2 class="section-headers">Contact Information</h2>
				<p id="name">Joshua T Heldreth</p>
				<address id="home-address" class="address">
					<h3 class="subsec-header">Address</h3> 
					<p class="street-address">
						<!--This is actually the address to Domino's on Main St-->
						<span class="address street">905 N Main St.<br></span>
						<span class="address city">Blacksburg</span>
						<span class="address state">VA, </span>
						<span class="address postal-code">24060<br></span>
					</p>
					<!--Puts all of my address together, AKA Domino's address-->
				</address>
				<!--Blacksburg address-->
				<address class="cell-phone">
					<!--This is actually the phone number to Domino's on Main St-->
					<a href="tel:540-953-4600">Cell-Phone: 540-953-4600</a>
				</address>
				<!--Cell-phone Number-->
				<address class="email">
					<!--Virginia Tech email-->
					<a href="mailto:joshh98@vt.edu">E-mail: joshh98@vt.edu</a>
				</address>
				<!--Email address-->
			</section>
			<!--contact-info-->


			<section id="education" class=" credentials resume-section">

				<h2 class="section-headers">Education</h2>

				<ul>
					<li class="degree">Virginia Tech Single Degree with Minor, GPA: 3.15
						<ul>
							<li>August 2017 - May 2021 (4 Years)</li>
							<li>Bachelor of Science - Applied Discrete Mathematics, Minor - Computer Science</li>
						</ul>
					</li>
				</ul>
				<!--Grouping together important aspects of my College Education-->

			</section>
			<!--education-->

			<section id="skills" class=" credentials resume-section">

				<h2 class="section-headers">Skills/Qualifications</h2>

				<div id="programming-languages" class="skills-section">
					<h3 class="subsec-header skill-header">Programming Languages</h3>
					<ul class="skill-list">
						<li>Java</li>
						<li>Python</li>
						<li>C++</li>
					</ul>
					<!--List of programming languages-->
				</div>
				<!--Grouping for coding background-->

				<div id="mathematics-background" class="skills-section">
					<h3 class="subsec-header skill-header">Mathematical Background</h3>
					<ul class="skill-list">
						<li>Combinatorics, Graph Theory, and Number Theory</li>
						<li>Cryptography 1 and 2</li>
						<li>Advanced Calculus (Calc 5)</li>
						<li>Statistics for EE (Stat 4714)</li>
					</ul> 
					<!--List of relevant Mathematics Courses-->
				</div>
				<!--Grouping 2 for mathematic background-->

			</section>
			<!--skills-->

			<section id="employment" class="credentials resume-section">
				<h2 class="section-headers">Employment</h2>
				<div id="jackcrete" class="company-employed-by">
					<!--Spacing will be handled by CSS-->
					<h3 class="subsec-header work-header">JackCrete VA Hampton Va December 2018 - Current</h3>
					<ul>
						<li class="job-title">Jr. Project Manager - Managed salesmen,
						estimated and sold work to major clients </li>
						<!--job title with short description of work-->
						<ul>
							<li>Gained confidence developing and presenting proposals to multiple customers</li>
							<li> Learned to think on my feet and keep a level head when dealing with challenging
							customers</li>
						</ul>
						<!--Lists skills gained from the position-->
						<li class="job-title">Solution Specialist – Lifted and leveled 
						concrete using polyurethane foam injection</li>
						<!--Listed job title with short descrption of work-->
						<ul>
							<li>Kept high moral in difficult conditions, learned to solve problems quickly</li>
							<li>Managed and Organized the warehouse</li>
							<li>Ensured crews left the shop promptly for every job</li>
						</ul>
						<!--Lists skills gained from the position-->
					</ul>
				</div>
				<!--Section talking about my roles at JackCrete-->
				<div id="poquoson-pharmacy" class="company-employed-by">
					<!--Spacing will be handled by CSS-->
					<h3 class="subsec-header work-header">Poquoson Pharmacy Poquoson VA June 2016 - July 2018</h3>
					<ul>
						<!--Gives job title, discription, and skills learned from the position-->
						<li class="job-title">Clerk – Trained new employees, maintained store</li>
						<ul>
							<li>Learned communication skills, working with a team, and developed my work ethic</li>
						</ul>
					</ul>
				</div>
				<!--Section talking about my roles at Poquoson Pharmacy-->
			</section>
			<!--Employment-->
		</div>
		<!--End of main-resume section-->
	</body>
	<!--Ends the body of the content-->
</html>
