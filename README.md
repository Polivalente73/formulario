<!DOCTYPE html>
<html>
<head>
	<title>Formulário de Cadastro</title>
</head>
<body>
	<div>
		<h2>Cadastro Online</h2>
		<form>
			<label>Nome:</label><br>
			<input type="text" name="nome"><br>

			<label>Sobrenome:</label><br>
			<input type="text" name="sobrenome"><br>

			<label>Email:</label><br>
			<input type="email" name="email"><br>

			<label>Senha:</label><br>
			<input type="password" name="senha"><br>

			<input type="submit" value="Cadastrar">
		</form>
	</div>
</body>
</html>

Este é o esqueleto simples, mas você pode adicionar mais campos, como Data de Nascimento, Sexo, Cidade, Estado, etc.

Para torná-lo responsivo, você pode abordar diferentes métodos, mas aqui está um método simples:

<!DOCTYPE html>
<html>
<head>
	<title>Formulário de Cadastro</title>
	<!--Adicione uma meta tag-->
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<!--Adicione o arquivo CSS Bootstrap-->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
	<!--Adicione o arquivo JavaScript Bootstrap-->
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body>
	<div class="container">
		<h2>Cadastro Online</h2>
		<form>
			<div class="form-group">
				<label>Nome:</label>
				<input type="text" name="nome" class="form-control" placeholder="Digite seu nome">
			</div>

			<div class="form-group">
				<label>Sobrenome:</label>
				<input type="text" name="sobrenome" class="form-control" placeholder="Digite seu sobrenome">
			</div>

			<div class="form-group">
				<label>Email:</label>
				<input type="email" name="email" class="form-control" placeholder="Digite seu email">
			</div>

			<div class="form-group">
				<label>Senha:</label>
				<input type="password" name="senha" class="form-control" placeholder="Digite sua senha" autocomplete="new-password">
			</div>

			<input type="submit" value="Cadastrar" class="btn btn-success">
		</form>
	</div>
</body>
</html>

