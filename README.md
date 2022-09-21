# ProjectOne


/* Considerar apenas o que está abaixo */


<!DOCTYPE html>
<html>
<head>
<title> js01Projectone </title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<meta charset="utf-8"/>
</head>
<body>
<h3>Programa de Boas Vindas!</h3>
<!-- Definição de Formulário -->
<form name="FormConcatena" action=" " method="post">
 Digite o nome............: <input type="text" name="f_nome" /><br/>
 Digite o sobrenome...: <input type="text" name="f_sobrenome" /><br/>
 Digite o nome completo...: <input type="text" name="f_nome completo" /><br/>
 Digite o CEP...: <input type="text" name="f_CEP" /><br/>
 Digite o Endereco...: <input type="text" name="f_Endereco" /><br/>
 <input type="button" name="btn_concatena" value="Concatenar" onclick="concatena()" />
 <input type="reset" name="btn_cancela" value="Cancelar" />
</form>

<!--
/* Objetivo: Capturar nome e sobrenome do usuário, concatenar (juntar) os campos e
apresentar uma saudação personalizada
Elementos de Entrada: método form do objeto document
Elementos de Saída: método alert do objeto window
*/
/* Definição das Variáveis */
var js_nome;
var js_sobrenome;
var js_nomecompleto;
var js_endereco;
function concatena( ) 
{
/* Entrada de Dados */
js_nome = document.FormConcatena.f_nome.value;
js_sobrenome = document.FormConcatena.f_sobrenome.value;
/* Processamento de Dados */
js_nomecompleto = js_nome + ' ' + js_sobrenome;
/* Saída de Dados */
window.alert('Ol\u00e1 ' + js_nomecompleto);
}
//-->
</body>
</html>
