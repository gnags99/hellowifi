<!DOCTYPE html>
<html>
<head>
	<title>Box Example</title>
	<style>
		body {
			display: flex;
			flex-direction: column;
			min-height: 100vh;
			margin: 0;
		}
		
		.container {
			flex: 1;
			display: flex;
			justify-content: center;
			align-items: flex-end;
		}

		.box {
			background-color: #eee;
			border: 1px solid #ccc;
			padding: 10px;
			max-width: 500px;
			line-height: 1.5;
			font-size: 16px;
			font-family: Arial, sans-serif;
		}
	</style>
</head>
<body>
	<div class="container">
		<div class="box">
			<ul>
				<li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
				<li>Donec ac fermentum quam.</li>
				<li>Nullam ullamcorper, mauris sit amet suscipit interdum, ipsum ante volutpat libero, vitae pretium nisi lorem non nisl.</li>
				<li>Sed malesuada sollicitudin nulla, eu faucibus felis pellentesque at.</li>
				<li>Fusce et sapien nisi.</li>
				<li>Nullam posuere malesuada mi, ut tristique massa tempus eget.</li>
				<li>Fusce aliquet sapien vitae dolor tincidunt dignissim.</li>
			</ul>
		</div>
	</div>
</body>
</html>
