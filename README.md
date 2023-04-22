<!DOCTYPE html>
<html>
<head>
	<title>Mi página web</title>
	<style>
		body {
			background-color: #f2f2f2;
			font-family: Arial, sans-serif;
			color: #333;
		}

		h1 {
			text-align: center;
			margin-top: 50px;
		}

		form {
			margin: 50px auto;
			width: 50%;
			background-color: #fff;
			padding: 20px;
			border-radius: 5px;
			box-shadow: 0px 2px 5px #ccc;
		}

		label {
			display: block;
			margin-bottom: 10px;
			font-weight: bold;
		}

		input[type=text], input[type=tel], input[type=file] {
			width: 100%;
			padding: 10px;
			border: 1px solid #ccc;
			border-radius: 5px;
			margin-bottom: 20px;
		}

		input[type=submit] {
			background-color: #333;
			color: #fff;
			padding: 10px 20px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
		}

		input[type=submit]:hover {
			background-color: #555;
		}
	</style>
</head>
<body>
	<h1>Mi página web</h1>

	<form>
		<label for="nombre">Nombre:</label>
		<input type="text" id="nombre" name="nombre">

		<label for="direccion">Dirección:</label>
		<input type="text" id="direccion" name="direccion">

		<label for="telefono">Teléfono:</label>
		<input type="tel" id="telefono" name="telefono">

		<label for="cartilla">Cartilla Médica:</label>
		<input type="file" id="cartilla" name="cartilla">

		<input type="submit" value="Enviar">
	</form>
</body>
</html>
