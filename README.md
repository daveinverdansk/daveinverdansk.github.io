<!DOCTYPE html>
<html>
<head>
	<title>davenevis</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<h1>Dave Nevis</h1>
		<nav>
			<ul>
				<li><a href="#about">About</a></li>
				<li><a href="#projects">Projects</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav>
	</header>

	<main>
		<section id="about">
			<h2>davenevis</h2>
			<p>Write a short bio about yourself.</p>
		</section>

		<section id="projects">
			<h2>projects</h2>
			<ul>
				<li>
					<h3>Project 1</h3>
					<p>A brief description of project 1.</p>
					<a href="#">View Code</a>
				</li>
				<li>
					<h3>Project 2</h3>
					<p>A brief description of project 2.</p>
					<a href="#">View Code</a>
				</li>
				<!-- Add more projects as needed -->
			</ul>
		</section>

		<section id="contact">
			<h2>Contact Me</h2>
			<form>
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" required>
				<label for="email">Email:</label>
				<input type="email" id="email" name="email" required>
				<label for="message">Message:</label>
				<textarea id="message" name="message" required></textarea>
				<input type="submit" value="Send">
			</form>
		</section>
	</main>

	<footer>
		<p>Copyright © 2023 davenevis</p>
	</footer>
</body>
</html>
