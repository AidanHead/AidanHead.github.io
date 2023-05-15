<!DOCTYPE html>
<html>
<head>
	<title>My Website Title</title>
	<link rel="stylesheet" href="style.css">
	<link rel="icon" type="image/x-icon" href="favicon.ico">
	<style>
		/* Your existing CSS styles here */

		@keyframes soccerBallAnimation {
			from {
				transform: translateX(-100%);
			}
			to {
				transform: translateX(100%);
			}
		}

		.soccer-ball {
			animation: soccerBallAnimation 4s linear infinite;
			position: relative;
		}
	</style>
	<script>
		window.addEventListener('DOMContentLoaded', function() {
			const images = document.querySelectorAll('nav ul li a img');
			images.forEach(function(image) {
				image.classList.add('soccer-ball');
			});
		});
	</script>
</head>
<body>
	<h1>Homepage</h1>
	<nav>
		<ul>
			<li><a href="benzema2.html"><img src="download12.png" alt="The Flash" title="The Flash"></a></li>
			<li><a href="website2.html"><img src="batman.png" alt="Batman" title="Batman"></a></li>
			<li><a href="Aidan.html"><img src="captainamerica.png" alt="Captain America" title="Captain America"></a></li>
			<li><a href="neymar2.html"><img src="thor.png" alt="Thor" title="Thor"></a></li>
		</ul>
	</nav>
</body>
</html>
