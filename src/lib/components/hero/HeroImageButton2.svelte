<!DOCTYPE html>
<html>
	<head>
		<style>
			.hero {
				position: relative;
				width: 100%;
				height: 400px;
				background-color: #f2f2f2;
				overflow: hidden;
			}

			.hero-image {
				width: 100%;
				height: 100%;
				object-fit: cover;
			}

			.hero-content {
				position: absolute;
				top: 50%;
				left: 50%;
				transform: translate(-50%, -50%);
				text-align: center;
				color: #ffffff;
			}

			.hero-button {
				padding: 12px 24px;
				font-size: 18px;
				background-color: #ff6600;
				color: #ffffff;
				border: none;
				border-radius: 4px;
				cursor: pointer;
			}
		</style>
	</head>
	<body>
		<div class="hero">
			<img src="path/to/your-image.jpg" alt="Hero Image" class="hero-image" />
			<div class="hero-content">
				<h1>Welcome to the Hero Component</h1>
				<p>This is a sample hero component with an image and a button.</p>
				<button class="hero-button">Learn More</button>
			</div>
		</div>
	</body>
</html>
