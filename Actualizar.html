<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="user.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css" media="all">
    <title>C'ALL</title>
	
	<style>
	
		body{
		text-align: center;
		background-color: white;
		color: black;
		font-family: calibri;
		font-size: 10pt;
		}
		
		a{
			color: black;
		}
		
		form > label{
		margin-top: 20px;
		color: white;
		}
		
		table, td{
		border-top: 1px solid black;
		border-bottom: 1px solid black;
	}
	
	table, th, td{
		
		width: 100%;
		padding: 1%;
		text-align: left;
	}
	
	td:hover{
		color: white;
		background-color: black;
		cursor: pointer;
	}
		
		.tres{
		margin: 0% 30% 0% 30%;
		background-color: black;
		padding: 4%;
		color: black;
		}
	</style>
    
</head>
<body>

	
    
    <header class="container"></header> 
	<a href="index.php">Voltar</a>
    <main class="container1">
	
	<img src="users.png" width="150px" height="150px"> 
	
	
	<!ACTUALIZAR USUARIOS!>
	<h1>Actualize ou altera algum dado de um membro da édetudotrap</h1>

	<form method="POST" action="Actualizar.php" class="tres">
	<label for="">Codigo: </label>
	<input type="number" name="codigo">
	</br>
	</br>
	<label for="">Nome: </label>
	<input type="text" name="nome">
	</br>
	</br>
	<label for="">E-mail: </label>
	<input type="e-mail" name="email">
	</br>
	</br>
	<label for="">Senha: </label>
	<input type="password" name="senha">
	</br>
	</br>
	<button>Alterar</button>
	</form>
	</br>
	</br>
	<?php
	/* ACTUALIZAR USUARIOS */
	
	include("conexao.php");
	
	$codigo=$_POST['codigo'];
	$novonome=$_POST['novonome'];	
	$novoemail=$_POST['novoemail'];
	$novasenha=$_POST['novasenha'];
	
	
	$sql="UPDATE cadastro SET 
		nome = '$novonome', 
		email= '$novoemail', 
		senha= '$novasenha' WHERE
		codigo= $codigo";
		
	if(mysqli_query($conexao, $sql) == TRUE){
		echo "Usuario actualizado com sucesso. <br><br>";
	}
	else{
		echo "Erro na actulização do usuario".mysqli_error($conexao);
	}
	
	$sql="SELECT nome, email, senha, codigo FROM cadastro ";
	
	$resultado=mysqli_query($conexao, $sql);

	if(mysqli_num_rows($resultado)){
		echo"<table class='table'>
		<tr>
		   <th>nome:</th>
		   <th><th>email:</th></th>
		   <th>senha:</th>
		<th><th>codigo:</th></th>";

		while($row=mysqli_fetch_assoc($resultado)){
			echo"<tr><td>".$row['nome']."<td/>
			<td>".$row['email']."<td/>
			<td>".$row['senha']."<td/>
			<td>".$row['codigo']."<td/>
		</tr>";
		}

		echo"</table>";
	}
	else{
		echo"Zero resultados";
	}
	mysqli_close($conexao);

?>

	
    </main>
    <footer></footer>
    <br><br><br><br>
</body>
</html>