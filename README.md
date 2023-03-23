# Are_u-Free-
<!DOCTYPE html>
<html>
<head>
	<title>Mời bạn đi ăn</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="container">
		<h1>Tuần sau bạn có rảnh không?</h1>
		<div class="buttons">
			<button><a href="yes.html">Có</a></button>
			<button>Không</button>
		</div>
	</div>
</body>
</html>
-----------------------------
body {
	margin: 0;
	padding: 0;
	font-family: Arial, sans-serif;
	background-color: #f8f8f8;
}

.container {
	width: 80%;
	max-width: 800px;
	margin: 0 auto;
	text-align: center;
	padding-top: 100px;
}

h1 {
	font-size: 48px;
	margin-bottom: 40px;
}

.buttons {
	display: flex;
	justify-content: center;
	align-items: center;
	flex-wrap: wrap;
}

button {
	border: none;
	background-color: #ff6347;
	color: #fff;
	font-size: 24px;
	padding: 10px 20px;
	border-radius: 10px;
	margin: 20px;
	cursor: pointer;
	transition: all 0.3s ease-in-out;
}

button:hover {
	background-color: #f56a51;
}
