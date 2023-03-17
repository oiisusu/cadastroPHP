<?php
// pegar os dados vindos.. neste caso do javaScript

$nome = $_POST["nome"];

$email = $_POST["email"]; $login $_POST["login"];
=
$senha = $_POST["senha"];

// abrir a conexao

include_once conexao.php';

// montar a instrução para gravar.

$sql "insert into usuario values(null, '".$nome."','".$email."','".$login."

// executar

if (mysqli_query($con, $sql)) { echo "gravado com sucesso";

} else { echo "erro ao gravar";
}
// fecho a conexão
 ?>
<script src="js/jquery.min.js"></script>

<script src="js/jquery.validate.js"></script> ]

<script>

$(document).ready(function(){

$("#btncadastrar").click(function(){

// alert("ok");

// Caso os dados não contenham erro, ele entra no if if($("#fcadastro").valid()){

// o javascript pega os dados do formulario,

var vnome = $("#nome").val();
var vemail = $("#email").val(); 
var vlogin = $("#login").val();

<body>

<form id="fcadastro">

body>divfconteudo

Nome: <br>

<input type="text" name="nome" id="note" class="required"> <br> E-mail: <br>
<input type="text" name="email" id="email" class="required email"> <br> Login: <br> 
<input type="text" name="login" id="login" class="required"> <br>
Senha:<br>
<input type="password" name="senha" id="senha" class="required"> <br>
 <br>

Confirme a Senha:<br>

<input type="password" name="confirmasenha")

class="required" equalTo-"#senha"> <br>

<input type="button" value="Cadastran" id="btncadastrar">
</form> <div id="conteudo">
</div>
</body>
</html>

Confirme a Senha:<br>
<input type="password" name="confirmasenha" class="required" equalto=
<input type="button" value="Cadastrar" id="btncadastrar">
</form> <div id="conteudo">
