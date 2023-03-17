<?php>
<form id="fcadastro"></form>

Nome: <br>

<input type="text" name="nome" id="note" class="required"> <br> E-mail: <br>

<input type="text" name="email" id="email" class="required email"> <br> 
Login: <br> <input type="text" name="login" id="login" class="required"> <br>

Senha:<br>

<input type="password" name="senha" id="senha" class="required"> <br> <br>

Confirme a Senha:<br>

<input type="password" name="confirmasenha")

class="required" equalTo-"#senha"> <br>

<input type="button" value="Cadastran" id="btncadastrar">

</form> <div id="conteudo">

</div>

</body>


<?php

Sservidor "localhost";

Susuario "root";

*Spassword="";

Sbanco = "publica2"; // o valor da senha na conexão e vazio, pois o meu mysql está sem senha, 1) mas fazendo as variavels fora como o exemplo visto no thiago.. esta dando conflito com o campo senha do W/ formulario.

Scon- mysqli_connect($servidor, Susuario, $senha, $banco);

<!-- ao publicarmos este site.. teremos o cuidado de modificar

estes endereços... -->
